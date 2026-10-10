# Repository conventions

This repository is the NoC1 Project entry point and integration workspace, maintained by Yamss.

The top-level directories separate Android platform work, kernel work, ROM integration, native programs, and host tools. These directories define ownership boundaries; they do not imply implemented features.

Use named subdirectories for independent components and device codenames for device-specific work. A component README should identify its purpose, source origin, supported targets, build steps, runtime requirements, and known limitations.

Pin external dependencies to exact revisions. Keep large upstream source trees in separate repositories and record their relationship here. Do not mix generated output with maintained source.

Add automation once there is a real component and a reproducible check to run. Any future documentation check must be clearly distinguished from kernel, ROM, or native build validation.
