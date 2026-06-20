# LangDB (langdb)

LangDB is an AI gateway and governance platform that routes requests across 250+ models from providers such as OpenAI, Anthropic, Google, Meta, Mistral, and DeepSeek through a single project-scoped, OpenAI-compatible REST API. It layers routing, guardrails, tracing, cost control, and an MCP (Model Context Protocol) gateway on top of that unified interface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/langdb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/langdb/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- AI Gateway
- Routing
- Governance
- MCP

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### LangDB Chat Completions / Routing API

OpenAI-compatible chat completions routed across 250+ models from OpenAI, Anthropic, Google, Meta, Mistral, and DeepSeek, with SSE streaming, tool calling, structured outputs, fallback/load-balancing routing, and attachable MCP servers.

- **Human URL:** [https://docs.langdb.ai/api-reference/ai-gateway-api/](https://docs.langdb.ai/api-reference/ai-gateway-api/)
- **Base URL:** `https://api.us-east-1.langdb.ai/{project_id}/v1`

#### Tags

- Chat
- Completions
- Routing
- LLM

#### Properties

- [Documentation](https://docs.langdb.ai/getting-started/working-with-api/)
- [API Reference](https://docs.langdb.ai/api-reference/ai-gateway-api/)
- [OpenAPI](openapi/langdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/langdb-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### LangDB Embeddings API

OpenAI-compatible embeddings endpoint that creates vector representations of input text or token arrays via any embedding model routed through the gateway.

- **Human URL:** [https://docs.langdb.ai/api-reference/ai-gateway-api/](https://docs.langdb.ai/api-reference/ai-gateway-api/)
- **Base URL:** `https://api.us-east-1.langdb.ai/{project_id}/v1`

#### Tags

- Embeddings
- Vectors

#### Properties

- [API Reference](https://docs.langdb.ai/api-reference/ai-gateway-api/)
- [OpenAPI](openapi/langdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LangDB Images API

OpenAI-compatible image generation endpoint producing images from text prompts using image-capable models routed through the gateway.

- **Human URL:** [https://docs.langdb.ai/api-reference/ai-gateway-api/](https://docs.langdb.ai/api-reference/ai-gateway-api/)
- **Base URL:** `https://api.us-east-1.langdb.ai/{project_id}/v1`

#### Tags

- Images
- Generation
- Multimodal

#### Properties

- [API Reference](https://docs.langdb.ai/api-reference/ai-gateway-api/)
- [OpenAPI](openapi/langdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LangDB Models API

Lists the models available to a project through the gateway in an OpenAI-compatible shape, spanning 250+ models across the supported providers.

- **Human URL:** [https://docs.langdb.ai/api-reference/ai-gateway-api/](https://docs.langdb.ai/api-reference/ai-gateway-api/)
- **Base URL:** `https://api.us-east-1.langdb.ai/{project_id}/v1`

#### Tags

- Models
- Catalog

#### Properties

- [API Reference](https://docs.langdb.ai/api-reference/ai-gateway-api/)
- [OpenAPI](openapi/langdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LangDB Threads / Messages API

Retrieves the ordered messages and aggregated per-thread cost for a conversation thread, grouped by the X-Thread-Id supplied on chat requests.

- **Human URL:** [https://docs.langdb.ai/concepts/thread](https://docs.langdb.ai/concepts/thread)
- **Base URL:** `https://api.us-east-1.langdb.ai`

#### Tags

- Threads
- Messages
- Observability

#### Properties

- [Documentation](https://docs.langdb.ai/concepts/thread)
- [API Reference](https://docs.langdb.ai/api-reference/ai-gateway-api/)
- [OpenAPI](openapi/langdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LangDB Analytics / Usage API

Returns time-series analytics, aggregated summaries, total usage, and per-model usage (cost and token counts) for a project over preset reporting windows.

- **Human URL:** [https://docs.langdb.ai/features/usage](https://docs.langdb.ai/features/usage)
- **Base URL:** `https://api.us-east-1.langdb.ai`

#### Tags

- Analytics
- Usage
- Cost
- FinOps

#### Properties

- [Documentation](https://docs.langdb.ai/features/usage)
- [API Reference](https://docs.langdb.ai/api-reference/ai-gateway-api/)
- [OpenAPI](openapi/langdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/langdb.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/langdb.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LangDB MCP Gateway API

Attaches virtual and custom MCP servers (over SSE or WebSocket transport) to chat requests via the mcp_servers array, exposing their tools to the routed model and bundling multiple tools behind a single MCP URL.

- **Human URL:** [https://docs.langdb.ai/features/mcp-support](https://docs.langdb.ai/features/mcp-support)
- **Base URL:** `https://api.us-east-1.langdb.ai/{project_id}/v1`

#### Tags

- MCP
- Tools
- Gateway

#### Properties

- [Documentation](https://docs.langdb.ai/features/mcp-support)
- [Documentation](https://docs.langdb.ai/concepts/virtual-mcp-servers/)
- [OpenAPI](openapi/langdb-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/langdb)
- [LinkedIn](https://www.linkedin.com/company/langdb)
- [Website](https://langdb.ai)
- [Documentation](https://docs.langdb.ai)
- [Plans](plans/langdb-plans-pricing.yml)
- [Rate Limits](rate-limits/langdb-rate-limits.yml)
- [Fin Ops](finops/langdb-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
