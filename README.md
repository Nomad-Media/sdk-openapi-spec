# SDK OpenAPI Spec

This repository contains the OpenAPI 3.0.0 spec for the Nomad Media **client SDK**.

> This is distinct from [`openapi-spec`](https://github.com/Nomad-Media/openapi-spec), which contains the raw REST API specs used in Postman.

---

## Files

| File | Description |
|------|-------------|
| `openapi-docs.yaml` | The SDK spec — version `2026-03`, 236 operations across 30 tags. **Generated — do not edit by hand.** |

The spec is generated from the [`sdk-javascript`](https://github.com/Nomad-Media/sdk-javascript) repository. See its [Developer Workflow](https://github.com/Nomad-Media/sdk-javascript#developer-workflow) section for generation instructions.

---

## How the spec is used

| Consumer | How |
|----------|-----|
| [`sdk-java`](https://github.com/Nomad-Media/sdk-java) | Validated against `openapi-docs.yaml` |
| [`sdk-csharp`](https://github.com/Nomad-Media/sdk-csharp) | Validated against `openapi-docs.yaml` (Coming Soon) |
| [`sdk-python`](https://github.com/Nomad-Media/sdk-python) | Validated against `openapi-docs.yaml` |
| [`dev-docs`](https://github.com/Nomad-Media/dev-docs) | API reference documentation |

---

## Related Repositories

- [`sdk-javascript`](https://github.com/Nomad-Media/sdk-javascript) — Canonical hand-written SDK (source of truth)
- [`sdk-python`](https://github.com/Nomad-Media/sdk-python) — Python SDK
- [`sdk-java`](https://github.com/Nomad-Media/sdk-java) — Java SDK
- [`sdk-csharp`](https://github.com/Nomad-Media/sdk-csharp) — C# SDK (Coming Soon)
- [`openapi-spec`](https://github.com/Nomad-Media/openapi-spec) — Raw REST API specs for Postman
