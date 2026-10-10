# NoC1 Project

Android systems, kernels, custom ROM integration, and native performance tooling.

Developed by **Yamss**. This is the main repository for NoC1 Project.

## Repository layout

| Path | Purpose |
| --- | --- |
| [android/](android/) | Android platform changes, service integration, and root module sources |
| [kernel/](kernel/) | Device-specific kernel work, configurations, and patch series |
| [rom/](rom/) | ROM manifests, overlays, product configuration, and integration notes |
| [native/](native/) | Native tools, daemons, libraries, and their build definitions |
| [tools/](tools/) | Host-side inspection, build, and packaging utilities |
| [docs/](docs/) | Engineering notes, source provenance, and validation records |

Large upstream trees should live in dedicated repositories. Keep their URLs and exact revisions here alongside NoC1 patches and integration instructions.

## Current state

The repository contains the project layout and contribution documentation. No implementation source, build configuration, flashable package, or benchmark dataset has been imported yet.

There is no project-wide build command. Each component must document its toolchain, dependencies, target, and build steps when its source is added. Device support and performance results remain unverified until recorded against a specific revision.

## Engineering

Keep changes scoped to a component and a target. Detect kernel capabilities before using device nodes; skip unsupported controls and record what was applied. Performance work needs measurements of frame time, latency, temperature, power, and sustained behavior under a repeatable workload.

Preserve upstream history, authorship, notices, and license terms. Record the base revision before importing or modifying source.

See [contribution notes](CONTRIBUTING.md), [repository conventions](docs/architecture.md), and [validation requirements](docs/validation.md).

## Licensing

No repository-wide license has been selected. Imported components must retain their original licenses and notices; document their provenance in [docs/sources.md](docs/sources.md).
