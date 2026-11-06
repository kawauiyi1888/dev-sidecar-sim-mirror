# Two-repository release simulation

- Upstream: `kawauiyi1888/dev-sidecar-sim-upstream`
- Mirror: `kawauiyi1888/dev-sidecar-sim-mirror`
- The sync workflow polls every five minutes and can also be run manually.
- `custom/patches/001-inject-custom-code.patch` is intentionally applied during the mirror build.
- A tag pushed with `SYNC_TOKEN` starts the build workflow once; the build creates a text release asset.
