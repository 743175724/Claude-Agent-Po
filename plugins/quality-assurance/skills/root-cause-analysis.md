# Skill: root-cause-analysis

## Description
Structured diagnostic techniques for isolating defects across kernel, rendering, gameplay, and web stacks.

## Tools & Methods
- Kernel debugging (WinDbg, KDNet), driver verifier, ETW traces
- Graphics profilers (RenderDoc, PIX) and UI layout inspectors
- Reverse engineering suites (IDA, Ghidra) for packed/obfuscated binaries
- Web dev tooling (Chrome DevTools, Lighthouse) for frontend regressions

## Process
1. Collect reproduction artifacts and relevant logs.
2. Form hypotheses for failure domains (memory corruption, timing, resource contention, API misuse).
3. Validate hypotheses with instrumentation and targeted tests.
4. Document findings, root cause, and recommended guardrails.
