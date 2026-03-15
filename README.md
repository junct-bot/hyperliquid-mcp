# Hyperliquid MCP Server

MCP server for Hyperliquid. Agent-ready API for Hyperliquid.

Hosted at [hyperliquid.mcp.junct.dev/mcp](https://hyperliquid.mcp.junct.dev/mcp). Free to use. No auth. No API key required.

Part of [Junct](https://junct.dev) — the agent-readiness layer for web3.

## Quick Start

Add to your MCP client config (Claude Desktop, Cursor, Windsurf):

```json
{
  "mcpServers": {
    "hyperliquid": {
      "url": "https://hyperliquid.mcp.junct.dev/mcp",
      "transport": "streamable-http"
    }
  }
}
```

## About

This MCP server is **deterministically generated** from the Hyperliquid API specification. Every tool maps 1:1 to a real API endpoint — no hallucinated endpoints.

- **Protocol:** Hyperliquid
- **Endpoint:** `https://hyperliquid.mcp.junct.dev/mcp`
- **Transport:** Streamable HTTP
- **Auth:** None required
- **Documentation:** [hyperliquid.mcp.junct.dev/llms.txt](https://hyperliquid.mcp.junct.dev/llms.txt)

## Links

- [Junct Dashboard](https://junct.dev/servers/hyperliquid)
- [llms.txt](https://hyperliquid.mcp.junct.dev/llms.txt)
- [agents.md](https://hyperliquid.mcp.junct.dev/agents.md)
- [OpenAPI spec](https://hyperliquid.mcp.junct.dev/openapi.json)

Keywords: Hyperliquid, MCP server, DeFi, AI agent, agent-ready API, crypto tools, Model Context Protocol
