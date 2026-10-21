# Kodza for Cursor

[Kodza](https://kodza.dev) is a free library of premium UI components and effects in plain HTML,
CSS and vanilla JavaScript. No framework, no build step, no API key.

This plugin gives Cursor the Kodza MCP server. Ask for "a magnetic button" or "a sticky header
that hides on scroll": the agent finds the component, gets its exact code and wires it into your
page, WordPress theme, Shopify section or React app.

## What's inside

One file that matters, `mcp.json`:

```json
{
  "mcpServers": {
    "kodza": { "url": "https://kodza.dev/api/mcp" }
  }
}
```

Hosted, stateless. Nothing runs on your machine. Prefer running it locally? `npx -y kodza-mcp`.

## Elsewhere

Claude Code, Codex, VS Code, Claude Desktop: [kodza.dev/docs](https://kodza.dev/docs/).

Missing a component? [Request it](https://github.com/kodza-dev/requests/discussions/new?category=requests).

## License

The plugin files are free to use. The components follow the [Kodza License](LICENSE):
use them anywhere, don't resell them.
