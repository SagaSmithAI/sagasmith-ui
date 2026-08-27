# SagaSmith UI

> [!IMPORTANT]
> **本仓库已归档。** 它不再是发布输入、兼容回退或新 issue 的接收位置。当前 Hosted 浏览器产品位于 [SagaSmith Web](https://github.com/SagaSmithAI/SagaSmith-service)；领域工作台分别随对应的 vertical repository 发布。
>
> **This repository is archived.** It is no longer a release input, compatibility fallback, or destination for new issues. The current hosted browser product lives in [SagaSmith Web](https://github.com/SagaSmithAI/SagaSmith-service), while domain workbenches ship from their vertical repositories.

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
