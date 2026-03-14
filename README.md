# Hyperliquid MCP Server

Hosted MCP server for **Hyperliquid** — giving AI agents direct access to Hyperliquid analytics data and operations.

> Powered by [Junct](https://junct.dev) — the agent-readiness layer for DeFi.

## Quick Connect

Add to your MCP client config (Claude Desktop, Cursor, Windsurf, etc.):

```json
{
  "mcpServers": {
    "hyperliquid": {
      "url": "https://hyperliquid.mcp.junct.dev/mcp"
    }
  }
}
```

**No setup required** — the server is hosted and maintained by Junct.

## Endpoint

| | |
|---|---|
| MCP URL | `https://hyperliquid.mcp.junct.dev/mcp` |
| Transport | Streamable HTTP |
| Domain | analytics |
| Tools | 2 |
| Docs | [llms.txt](https://hyperliquid.mcp.junct.dev/llms.txt) |
| OpenAPI | [openapi.json](https://hyperliquid.mcp.junct.dev/openapi.json) |

## Tools (2)

| Tool | Description |
|---|---|
| `query_info` | Query information endpoint — Unified endpoint for querying various types of information. The request body `type` field d |
| `execute_exchange` | Execute exchange operations — Unified endpoint for all trading and account operations. Requires EIP-712 signature for au |

## Links

- [Junct Dashboard](https://junct.dev/servers/hyperliquid)
- [Server Info](https://hyperliquid.mcp.junct.dev/)
- [llms.txt](https://hyperliquid.mcp.junct.dev/llms.txt)
- [agents.md](https://hyperliquid.mcp.junct.dev/agents.md)
- [MCP Discovery](https://hyperliquid.mcp.junct.dev/.well-known/mcp/server.json)

---

*This server is automatically generated, hosted, and maintained by [Junct](https://junct.dev).*
