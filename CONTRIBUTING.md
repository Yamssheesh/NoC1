# Contributing

Maintainer: Yamss.

Describe the problem, the target, and the resulting behavior. Keep unrelated changes in separate commits.

Before adding a component:

- Record its upstream URL, revision, license, and local changes in `docs/sources.md`.
- Include source and reproducible build instructions, with the required toolchain versions.
- State the device codename, architecture, Android version, and kernel baseline where relevant.
- Separate planned work, successful compilation, boot testing, and runtime validation.

For fixes, include the reproduction steps and relevant logs. Remove personal data and credentials from logs before committing them.

For performance changes, record a baseline and the changed revision under the same workload. Include temperatures, cooling conditions, and run duration. Do not infer universal compatibility from one device.

Use short commit subjects such as `kernel: document beryllium build prerequisites`. Preserve upstream authorship and keep generated binaries in GitHub Releases.
