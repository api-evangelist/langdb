# LangDB (langdb)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
