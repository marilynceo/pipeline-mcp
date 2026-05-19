# pipeline-mcp

AI-native ETL: transform, join, filter, aggregate, and load data between sources. Pandas + sqlglot, zero external API.

## Quick Start

```bash
git clone https://github.com/marilynceo/pipeline-mcp.git
cd pipeline-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://pipeline.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/pipeline-mcp

# Or connect directly via MCP client
# Endpoint: https://pipeline.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
