# Validation

No component builds, device tests, or benchmarks have been recorded.

Every validation record should identify the commit, component, target device, OS build, kernel, toolchain, commands, result, and remaining limitations.

## Build and device testing

Record compilation separately from packaging, boot testing, and runtime testing. Include exit status and useful log excerpts. For device changes, check recovery, suspend and resume, networking, charging, and relevant peripherals.

## Performance testing

Record the baseline and changed revision, workload, settings, duration, repetitions, ambient conditions, cooling, and battery or charging state.

Use frame-time distributions and sustained behavior where applicable. Include temperature and power observations. Report regressions and variability alongside improvements; do not publish an FPS claim without its measurement method and data.

## Runtime controls

Record detected interfaces, successful writes, skipped controls, and restoration behavior. Test missing or unwritable nodes. Include thermal behavior and stability in any performance evaluation.
