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

## Integrations

| Platform | What you get |
| --- | --- |
| Snowflake Marketplace | People and company data you query in place from your own account, a free company dataset, and the Data Legion Enrich native app · [Docs](https://www.datalegion.ai/docs/integrations/snowflake) |
| Apify | The [Data Legion Enrichment](https://apify.com/datalegion/data-legion-enrichment) Actor, billed per matched record · [Docs](https://www.datalegion.ai/docs/integrations/apify) |
| Clay | Person and company enrichment as a column in any Clay table · [Docs](https://www.datalegion.ai/docs/integrations/clay) |
| Firecrawl Alexandria | Enrichment for agents already on Firecrawl, billed in Firecrawl credits · [Docs](https://www.datalegion.ai/docs/integrations/firecrawl) |
| Zapier | The [Data Legion app](https://zapier.com/apps/data-legion/integrations): Find Person, Find Company, and free data tools in any Zap · [Docs](https://www.datalegion.ai/docs/integrations/zapier) |
| n8n | [`n8n-nodes-datalegion`](https://www.npmjs.com/package/n8n-nodes-datalegion), a verified community node for workflows and n8n's AI Agent · [Docs](https://www.datalegion.ai/docs/integrations/n8n) |

## Try it

```bash
curl -X POST https://api.datalegion.ai/person/enrich \
  -H "API-Key: $DATALEGION_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"email": "jane.doe@example.com"}'
```

A request with no match costs nothing. [Sign up](https://www.datalegion.ai/sign-up) for self-serve credits, see [pricing](https://www.datalegion.ai/pricing), or [talk to sales](https://www.datalegion.ai/get-started) about search, discovery, and bulk licenses.

[Website](https://www.datalegion.ai) · [Docs](https://www.datalegion.ai/docs/getting-started/quickstart) · [For agents](https://www.datalegion.ai/agents) · hello@datalegion.ai
