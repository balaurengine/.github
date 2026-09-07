<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/balaurengine/balaur/main/docs/assets/logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/balaurengine/balaur/main/docs/assets/logo-light.svg">
  <img src="https://raw.githubusercontent.com/balaurengine/balaur/main/docs/assets/logo-light.svg" alt="Balaur" width="84" height="84">
</picture>

# Balaur

**A 2D &amp; 3D node-based game engine, fully deterministic, with scripts that reload in milliseconds.**

Written in Rust. One file to ship.

[**Docs**](https://balaurengine.org/docs/intro) · [Features](https://balaurengine.org/features) · [Principles](https://balaurengine.org/docs/principles) · [Download](https://balaurengine.org/download) · [Roadmap](https://balaurengine.org/docs/roadmap) · [Discord](https://discord.gg/v649emcpAu)

[![CI](https://github.com/balaurengine/balaur/actions/workflows/runner.yml/badge.svg)](https://github.com/balaurengine/balaur/actions/workflows/runner.yml) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) [![Discord](https://img.shields.io/discord/1138836561102897172?logo=discord&logoColor=white&label=Discord&color=5865F2)](https://discord.gg/v649emcpAu)

</div>

## Features

- **Nodes and scenes** — a tree of named nodes with scripts attached; scenes are plain TOML.
- **Rune scripting** — Rust's syntax, no build step, async/await, debugger in the editor.
- **Hot reload** — save a script while the game runs; live in milliseconds, state intact.
- **Determinism** — same inputs, same bits, every platform. Record a session and replay it.
- **Physics** — Rapier in 2D and 3D, stepped on a fixed 60 Hz tick.
- **Rendering** — wgpu: windowed, offscreen for CI screenshots, or headless.
- **Animation** — clips and tweens, 2D bones with skinned polygons, glTF rigs, two-bone IK.
- **Editor** — itself a Balaur project: scene tree, inspector, gizmos, timeline, play-in-editor.
- **Networking** — HTTP, WebSocket and WebTransport, delivered into the simulation once per tick.
- **Platforms** — Windows, macOS, Linux; iOS, Android and web cross-compiled in CI on every push.
- **Export** — one self-contained binary per target: bytecode, scenes and assets fused onto the runtime.

## Documentation

At [balaurengine.org](https://balaurengine.org):
[getting started](https://balaurengine.org/docs/getting-started) ·
[manual](https://balaurengine.org/docs/manual/scenes) ·
[reference](https://balaurengine.org/docs/reference) ·
[architecture](https://balaurengine.org/docs/architecture) ·
[roadmap](https://balaurengine.org/docs/roadmap) ·
[changelog](https://balaurengine.org/docs/changelog)

## Community

[Discord](https://discord.gg/v649emcpAu) ·
[Discussions](https://github.com/balaurengine/balaur/discussions) ·
[Issues](https://github.com/balaurengine/balaur/issues)

## Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=balaurengine/balaur&type=date&legend=top-left)](https://star-history.dera.page/#balaurengine/balaur&type=date&legend=top-left)
