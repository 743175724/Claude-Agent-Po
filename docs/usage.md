# Usage Guide

This project packages Claude agents, commands, and skills tailored for a cross-disciplinary workflow spanning Windows driver development, UI/UX, reverse engineering, web, and game development disciplines.

## Getting Started
1. Review `.claude-plugin/marketplace.json` to discover available plugins and their roles.
2. Start with the **Project Management Orchestrator** plugin to dispatch work:
   - Deploy the `Intelligent Task Dispatcher` agent.
   - Use `prioritize-backlog` to rank incoming requests.
   - Generate execution packets with `handoff-brief`.
3. Engage the **Quality Assurance & Remediation** plugin once defects or code reviews are required:
   - Assign the `Bug Fix Specialist` for deep remediation.
   - Route changes through the `Senior Code Reviewer` to enforce the rework loop.

## Recommended Flow
- Dispatcher creates a domain context map and milestone plan.
- Specialist executes the bugfix playbook, leveraging diagnostics skills.
- Reviewer runs compliance audits, issues rework tasks if criteria are unmet, and signs off when complete.

## Extending
Add new domain-specific plugins by mirroring the existing structure (`agents/`, `commands/`, `skills/`) and registering them in the marketplace manifest.
