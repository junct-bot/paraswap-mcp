# ParaSwap MCP Server

Hosted MCP server for **ParaSwap** — giving AI agents direct access to ParaSwap DEX aggregation.

> Powered by [Junct](https://junct.dev) — the agent-readiness layer for DeFi.

## Quick Connect

Add to your MCP client config (Claude Desktop, Cursor, Windsurf, etc.):

```json
{
  mcpServers: {
    paraswap: {
      url: https://paraswap.mcp.junct.dev/mcp
    }
  }
}
```

## About

ParaSwap is a DEX aggregator that finds the best swap rates across multiple decentralized exchanges. This MCP server provides AI agents with tools to access ParaSwap's API for token swaps, price quotes, and liquidity data.

## Links

- **MCP endpoint:** https://paraswap.mcp.junct.dev/mcp
- **Server page:** https://junct.dev/servers/paraswap
- **ParaSwap:** https://paraswap.io
