# opengame-performance

Keep a browser game smooth on an ordinary laptop and a shared GPU, with three.js and WebGPU specifics. Covers frame-time tails counted from frames the engine ran, bare timing runs, cost over frame rate, frame pacing by what lands, draw calls per pass, a fixed light set and warm-up, uploads that never stall, the world lowered before the gameplay layer, and whole-tab memory.

It is one of the [OpenGame](https://opengame.io) agent skills, which teach a coding agent such
as Claude Code, Codex, Cursor or OpenCode to build a browser game and put it online.

## Install

```bash
npx skills add opengamehq/performance
```

The skill installs under its own name, `opengame-performance`. Every OpenGame skill, each under its own
name, installs from [opengamehq/opengame](https://github.com/opengamehq/opengame):

```bash
npx skills add opengamehq/opengame
```

How the skills fit into making and shipping a game is at [docs.opengame.io](https://docs.opengame.io).

## Changes

This is version 1.1.2. [CHANGELOG.md](CHANGELOG.md) lists what changed in each one.

## Issues

OpenGame's release tooling writes this repository from [opengamehq/opengame](https://github.com/opengamehq/opengame),
so a change made here is replaced by the next release, and it does not take pull requests.
Open an issue [there](https://github.com/opengamehq/opengame/issues) for a skill that teaches the wrong thing.

## License

[Apache 2.0](LICENSE).
