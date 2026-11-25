# Tappet

**A single-binary workflow automation engine written in Rust.** Build automations visually or as code,
run AI agents with tools and MCP, and import workflows exported from n8n without Node.js.

- **Fast and small**: one static binary with the web UI embedded, SQLite by default, Postgres for HA.
- **Compatible**: imports n8n workflow JSON and reports, node by node, what runs natively.
- **Connected**: a declarative connector format makes adding an integration a YAML file, not a package.
- **Open**: Apache-2.0, no feature gating.

| Repository | What it is |
|---|---|
| [tappet](https://github.com/tappet-dev/tappet) | Engine, server, CLI, web UI, connectors, docs |
| [helm-charts](https://github.com/tappet-dev/helm-charts) | Helm repository (`https://charts.tappet.dev`) |
| [homebrew-tap](https://github.com/tappet-dev/homebrew-tap) | `brew install tappet-dev/tap/tappet` |

Website: [tappet.dev](https://tappet.dev)
