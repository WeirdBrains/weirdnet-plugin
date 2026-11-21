# Handoff

Running notes for [weirdnet-plugin](https://github.com/WeirdBrains/weirdnet-plugin), newest first.

## 2026-11-21: v0.1.1, SDK version and public-content release

- What changed: the SDK version moves to 0.1.1. `SDK_VERSION` and the `"sdk"` field that `plugin!` writes into `weirdnet_plugin_info` both read 0.1.1, so the two agree again. Package metadata and docs follow the public-content rules (content commit `3f1803c`). No other code or API changes. [weirdnet-code-spaces](https://github.com/WeirdBrains/weirdnet-code-spaces) 0.1.2 bundles this SDK.
- Commits: `3f1803c` and the `release: v0.1.1` commit tagged [v0.1.1](https://github.com/WeirdBrains/weirdnet-plugin/releases/tag/v0.1.1).
- Checks: cargo fmt, clippy, test and package; the packaged crate was scanned for private terms before publishing.
- Not tested: loading a plugin built against 0.1.1 in a host (covered by code-spaces' own tests).
- Left: 0.1.0 is yanked on [crates.io](https://crates.io/crates/weirdnet-plugin/versions).
- Next: nothing for this release.
