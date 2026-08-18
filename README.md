# SagaSmith UI

[Website](https://sagasmithai.github.io) · [Platform overview](https://github.com/SagaSmithAI/.github/blob/main/profile/README.md) · [Hosted service](https://github.com/SagaSmithAI/SagaSmith-service) · [Content catalog](https://github.com/SagaSmithAI/SagaSmith-dnd-content-library)

**Cross-system client exploration for the SagaSmithAI platform.** This repository is where shared TTRPG interface concepts can be tested before they become stable system-specific workbenches.

## Scope

The shared UI should eventually provide system-neutral surfaces for:

- Agent/channel presence and authenticated table identity;
- campaign selection, branch continuity, events, and snapshots;
- party and actor knowledge boundaries;
- source-aware rule and module navigation;
- plugin-provided system panels for D&D, CoC, and future systems.

System mechanics do not belong here. D&D combat, CoC SAN/chases, character schemas, and content parsers remain in their system runtimes and MCP services. The browser must never access domain databases directly.

## Current status

Prototype. The D&D-specific product direction is being validated first in [sagasmith-dnd-ui](https://github.com/SagaSmithAI/sagasmith-dnd-ui). Shared components should move here only after their contracts are proven across at least two systems.

## Development

Requires Node.js 22.12+.

```bash
npm install
npm run dev
npm run build
npm run preview
```

## License

Apache-2.0
