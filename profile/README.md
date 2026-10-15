# Data Legion

B2B people and company data to enrich, search, and license. We build the data. You build the rest.

Match a person by email, phone, name, or social URL, or a company by domain, name, or ticker. Search with SQL filters or plain English, or license the full datasets as monthly files. Person data covers the United States; company data covers companies worldwide. The data is cross-checked across sources and rebuilt monthly.

## Ways in

| Surface | Get started |
| --- | --- |
| REST API | `https://api.datalegion.ai` · [API reference](https://www.datalegion.ai/docs/api-reference/overview) |
| MCP server | `https://api.datalegion.ai/mcp` for Claude, ChatGPT, Codex, Cursor, Gemini, and other MCP clients · [Setup](https://www.datalegion.ai/docs/integrations/mcp-server) |
| Python SDK | `pip install datalegion` · [Docs](https://www.datalegion.ai/docs/sdks/python) |
| Node SDK | `npm install datalegion` · [Docs](https://www.datalegion.ai/docs/sdks/node) |
| CLI | `brew install datalegion-ai/tap/datalegion-cli` or `pip install datalegion-cli` · [Docs](https://www.datalegion.ai/docs/integrations/cli) |
| Claude plugin | [datalegion-plugin](https://github.com/datalegion-ai/datalegion-plugin) |
| Bulk datasets | CSV, JSON, Parquet, or Delta to Amazon S3, Google Cloud Storage, Azure Blob Storage, or SFTP · [Formats](https://www.datalegion.ai/docs/getting-started/delivery-formats) |

## Try it

```bash
curl -X POST https://api.datalegion.ai/person/enrich \
  -H "API-Key: $DATALEGION_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"email": "jane.doe@example.com"}'
```

A request with no match costs nothing. [Sign up](https://www.datalegion.ai/sign-up) for self-serve credits, see [pricing](https://www.datalegion.ai/pricing), or [talk to sales](https://www.datalegion.ai/get-started) about search, discovery, and bulk licenses.

[Website](https://www.datalegion.ai) · [Docs](https://www.datalegion.ai/docs/getting-started/quickstart) · [For agents](https://www.datalegion.ai/agents) · hello@datalegion.ai
