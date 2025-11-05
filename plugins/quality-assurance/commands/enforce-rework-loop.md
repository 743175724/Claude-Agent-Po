# Command: enforce-rework-loop

## Purpose
Standardize the reviewer's authority to halt delivery, capture actionable feedback, and shepherd fixes through completion.

## Procedure
1. **Log Findings:** Record each issue with severity, affected files, and reproduction or test expectations.
2. **Assign Owners:** Identify the responsible agent (bug fix specialist, feature developer) and set a re-delivery deadline.
3. **Define Exit Criteria:** State measurable conditions for re-approval (tests, screenshots, profiler captures).
4. **Track Progress:** Update status during check-ins; escalate overdue items to the dispatcher.
5. **Closure:** Verify evidence, update the checklist, and document lessons learned.

## Tooling Integration
- Compatible with Git-based review comments, task trackers, and CI status checks.
- Encourages automation hooks (lint, static analysis, driver verifier) before re-submission.
