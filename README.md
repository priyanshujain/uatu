# sanderling

Autonomous property-based testing for mobile and web apps. Specs in TypeScript. Core in Go. Drives native apps through Maestro (UIAutomator / XCTest) and the web through the Chrome DevTools Protocol.

> Alpha. Android, iOS, and web (Chrome). Full scope in the [v0.1.0 roadmap](https://github.com/priyanshujain/sanderling/issues/4).

## Docs

- [Getting started](https://priyanshujain.github.io/sanderling/manual/getting-started.html)
- [Writing specs](https://priyanshujain.github.io/sanderling/manual/writing-specs.html)
- [`sanderling inspect` UI](https://priyanshujain.github.io/sanderling/manual/inspect.html)
- [Architecture](https://priyanshujain.github.io/sanderling/development/architecture.html)

## Example apps

- [`examples/folio`](https://github.com/priyanshujain/sanderling/tree/master/examples/folio) - Kotlin Multiplatform ledger app, runs on Android, iOS, and web (wasmJs).
- [`examples/folio-web`](https://github.com/priyanshujain/sanderling/tree/master/examples/folio-web) - React + Vite version of the same domain, web-only.

After a `sanderling test` run, browse traces locally with `sanderling inspect`. It opens a web UI for stepping through actions, screenshots, snapshots, residual formulas, and exceptions.

---

<img src="docs/_assets/sanderling.jpeg" alt="sanderling" width="420" />

> sanderling, a wading bird that probes the shoreline for bugs that lie beneath.