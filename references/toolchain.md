# Toolchain and Runtime Expectations

Use this file when deciding which language and runtime conventions should apply.

- Prefer TypeScript when the project supports it.
- Keep runtime assumptions explicit: browser, Node, edge, worker, or mixed environments should be clear in module design.
- Follow the project's existing package manager, bundler, and compiler setup unless the task explicitly requires changing them.
