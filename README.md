# webmcp-toolkit

Open tool definitions, safety rules and tooling that help websites become agent-ready with
[WebMCP](https://github.com/webmachinelearning/webmcp). Licensed under Apache-2.0.

## Layout
- `definitions/` — tool definitions per platform (WooCommerce first) and the JSON schema
- `rules/` — safety and quality rules for site owners
- `packages/cli/` — `webmcp-check`, level-1 validation
- `packages/guard/` — `registerGuardedTool()` wrapper: rules, shopper confirmation, hand-off, logging
- `packages/guard-server/` — server that rejects cart changes without a valid approval token
- `examples/store/` — demo shop page that registers WebMCP tools

Status: early. Most folders are placeholders.
