# Command: bugfix-playbook

## Purpose
Guide remediation efforts from triage through verification for complex, multi-platform defects.

## Checklist
1. **Confirm Scope:** Align with dispatcher on affected versions, modules, and customer impact.
2. **Environment Prep:** Provision debug symbols, kernel debugging hooks, engine builds, or web staging targets.
3. **Diagnostic Plan:** Select tooling (WinDbg, IDA, RenderDoc, browser dev tools) and logging instrumentation.
4. **Fix Strategy:** Outline candidate approaches, validation strategy, and rollback plan.
5. **Verification:** Define regression suites, performance baselines, and security checks.
6. **Documentation:** Update issue tracker with findings, patches, and test artifacts.

## Outputs
- Structured remediation plan
- Evidence bundle ready for code review
