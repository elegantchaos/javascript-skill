# Module Organization and State

Use this file when shaping JavaScript or TypeScript modules.

- Favor clear module boundaries and explicit data flow.
- Avoid hidden mutable global state.
- Keep domain logic separate from framework glue, CLI entry points, or browser bootstrapping code.
- Keep interfaces small and unsurprising, especially around stateful modules.
