# ✈️ flightOracle

**Travel MCP Server** — 8 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-8-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Free-2196F3?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/flight/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "flightoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/flight/mcp/"]
    }
  }
}
```

## Tools (8)

| Tool | Description |
|------|-------------|
| `flight_search` | Search round-trip or one-way flights between airports. Returns best flights, pri |
| `cheapest_flights` | Find the cheapest flights across a full month. Returns price-sorted options with |
| `one_way_search` | Search one-way flights with all filters. |
| `multi_city` | Price a multi-city route with 2+ legs. Returns per-leg pricing and total cost ra |
| `price_calendar` | Weekly price calendar for a route. Find the cheapest week to fly. |
| `route_compare` | Compare flight prices by airline for a route. Shows cheapest per airline, stops, |
| `airport_hub` | Find airport IATA codes for a city. Returns nearby airports and common codes. |
| `health_check` | Server status, API connectivity, supported features. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 100 calls/day | €0 |
| Pro | 10,000 calls/day | €29/month |
| Enterprise | Unlimited | Custom |

> Free tier includes all tools with rate limiting. Upgrade for higher limits and priority support.

## Part of ToolOracle

flightOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.



**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/flight/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
