---
name: javascript
description: Applies general JavaScript and TypeScript guidance outside framework-specific specialist skills. Use when reading, writing, or reviewing JavaScript or TypeScript code that needs baseline module, runtime, async, state, or tooling guidance.
---

# JavaScript

Use this skill for baseline JavaScript and TypeScript guidance that sits below framework-specific specialist skills.
It covers language choice, module boundaries, runtime expectations, async behavior, state management, dependencies, and validation.

Load only the references that matter for the task:

1. Read `references/toolchain.md` for JavaScript versus TypeScript expectations and runtime assumptions.
2. Read `references/organization.md` for module boundaries, state ownership, and project structure guidance.
3. Read `references/async-and-state.md` for promises, async flows, and external input boundaries.
4. Read `references/tooling-and-validation.md` for dependencies, scripts, and validation expectations.
5. Read `references/sources.md` when JavaScript or TypeScript technical decisions depend on external references, runtime semantics, or platform APIs.
6. If framework-specific behavior is central to the task, treat the relevant specialist skill or project guidance as the source of truth and use this skill only for residual baseline JavaScript or TypeScript questions.
7. If source selection, policy guidance, or general engineering tradeoffs are central to the task, pair this skill with `coding-standards`.

## References

- `references/toolchain.md` - TypeScript preference, runtime assumptions, and baseline platform expectations.
- `references/organization.md` - module boundaries, explicit data flow, and state ownership.
- `references/async-and-state.md` - promises, async behavior, input validation, and runtime failures.
- `references/tooling-and-validation.md` - dependencies, scripts, build setup, and validation expectations.
- `references/sources.md` - primary JavaScript, TypeScript, and runtime sources.
