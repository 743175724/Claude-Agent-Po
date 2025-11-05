# Command: prioritize-backlog

## Purpose
Provide a repeatable scoring matrix for ranking work across Windows drivers, UI/UX, reverse engineering, and multi-engine game development efforts.

## Inputs
- Candidate tasks with metadata (complexity, risk, customer impact, dependencies)
- Resource availability and specialist bandwidth
- Release or event deadlines (game launches, driver certification windows)

## Steps
1. Collect backlog items from the dispatcher queue and normalize estimation units.
2. Score each item using weighted criteria: severity, platform coverage, revenue/engagement impact, regression risk.
3. Resolve resource conflicts by consulting specialist calendars and skill requirements.
4. Produce a prioritized list with rationale notes and publish to the roadmap.

## Outputs
- Sorted backlog with numeric priority, due dates, and assigned agents
- Risk callouts and mitigation owners
