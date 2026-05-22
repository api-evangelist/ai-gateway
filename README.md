# AI Gateway (ai-gateway)

An API Evangelist landscape index of **AI gateways** — the LLM routers, prompt firewalls, model fallback proxies, cost-control planes, and policy engines that sit between applications and AI providers. AI gateways unify access across OpenAI, Anthropic, Google, AWS Bedrock, Azure OpenAI, and self-hosted models behind a common interface and apply caching, routing, guardrails, observability, rate limiting, budgets, RBAC, and audit controls.

**URL:** [https://github.com/api-evangelist/ai-gateway](https://github.com/api-evangelist/ai-gateway)

**APIs.yml:** [https://raw.githubusercontent.com/api-evangelist/ai-gateway/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ai-gateway/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

AI Gateway, LLM Router, LLM Proxy, Model Routing, Prompt Firewall, Guardrails, AI Observability, Cost Controls, AI Governance, API Gateway

## Timestamps

- **Created:** 2026-05-22
- **Modified:** 2026-05-22

---

## Landscape

The AI gateway category is roughly four overlapping product shapes:

1. **Pure LLM gateways and routers** — purpose-built proxies in front of LLM providers. Examples: **Portkey**, **OpenRouter**, **LiteLLM**, **Helicone**, **LangDB**.
2. **API gateway AI plugins** — existing API gateways (Kong, Apache APISIX, Envoy/Tetrate, Traefik) shipping AI proxy plugins or AI-native gateway products that translate between OpenAI-format clients and many upstream providers.
3. **Cloud-provider AI proxies** — edge or hyperscaler services like **Cloudflare AI Gateway** that wrap arbitrary providers with caching, analytics, and rate limiting.
4. **Inference platforms with router behaviour** — **Together AI**, **Anyscale**, **NVIDIA NIM** — primarily sell inference but expose unified OpenAI-compatible APIs across many models.

All of them tend to converge on the same vocabulary: **routes**, **providers**, **models**, **policies**, **virtual keys**, **caching**, **fallback**, **fanout**, **budgets**, and **guardrails**.

## Comparison Axes

When evaluating an AI gateway, the load-bearing axes are:

| Axis | What to look for |
|---|---|
| **Provider Abstraction** | Number of upstream providers; OpenAI-compatible wire format; per-route model aliasing. |
| **Caching** | Exact-match vs semantic caching; TTL and similarity-threshold controls; claimed cost savings. |
| **Fallback and Fanout** | Multi-backend routes; weighted load balancing; priority-based fallback; fanout to evaluation panels. |
| **Observability** | Per-request token, latency, and cost; OpenTelemetry, Langfuse, Phoenix, Langsmith exports; dashboards. |
| **Guardrails** | PII redaction, prompt-injection detection, jailbreak filters, toxicity, regex, topic, moderation, custom webhooks. |
| **BYOK and Key Management** | Whether the gateway holds your provider keys; virtual keys issued to clients; per-tenant credential isolation. |
| **Multi-Tenant Governance** | Per-tenant budgets, model allowlists, policies, logs, audit retention. |
| **Deployment Model** | Cloud SaaS, self-hosted (Docker/K8s), open source, or edge (Cloudflare Workers). |
| **Licensing** | MIT / Apache-2.0 / proprietary; whether the OSS core is the same as the hosted offering. |

## Gateways in This Index

| Gateway | Deployment | Providers | Notable |
|---|---|---|---|
| [Portkey](https://portkey.ai/) | Cloud, self-host, OSS (MIT) | 1,600+ LLMs across 45+ providers | "Production Stack for Gen AI Builders"; guardrails, prompt management, RBAC. |
| [OpenRouter](https://openrouter.ai/) | Cloud (proprietary) | 400+ models across 60+ providers | "The Unified Interface For LLMs"; pay-as-you-go credits; automatic provider fallback. |
| [LiteLLM](https://www.litellm.ai/) | OSS, self-host, cloud | 100+ providers | "LLM Gateway (OpenAI Proxy) to manage authentication, loadbalancing, and spend tracking across 100+ LLMs"; 47.9k GitHub stars. |
| [Helicone](https://www.helicone.ai/) | Cloud, self-host, OSS | OpenAI, Anthropic, Gemini, DeepSeek, Together, Mistral, Groq, OpenRouter, Azure, LiteLLM | "Build Reliable AI Apps"; observability-first. |
| [Cloudflare AI Gateway](https://developers.cloudflare.com/ai-gateway/) | Cloud (edge) | Workers AI, Anthropic, Gemini, OpenAI, Replicate, others | "Observe and control your AI applications"; available on all Cloudflare plans. |
| [Kong AI Gateway](https://konghq.com/products/kong-ai-gateway) | Cloud, self-host, OSS plugin | 16+ providers including OpenAI, Azure OpenAI, Anthropic, Bedrock, Gemini, Vertex, Cohere, Mistral, Hugging Face, Llama, xAI, Ollama, DeepSeek, Databricks, vLLM | "Transform and proxy requests to a number of AI providers and models"; template-based model selection. |
| [Apache APISIX AI Proxy](https://apisix.apache.org/docs/apisix/plugins/ai-proxy/) | Self-host (Apache-2.0) | OpenAI, DeepSeek, Azure OpenAI, Anthropic, Gemini, Vertex AI, OpenRouter, AIMLAPI, OpenAI-compatible | Open-source AI proxy plugin for APISIX with token-usage logs. |
| [Envoy AI Gateway](https://aigateway.envoyproxy.io/) | OSS, self-host (Apache-2.0) | Multi-provider | CNCF-aligned Envoy extension for K8s-native AI routing. |
| [Tetrate Agent Router Service](https://tetrate.io/products/tetrate-agent-router-service/) | Cloud, self-host | Multi-provider | "Developer's Shortest Path to Models Anywhere — Envoy AI Gateway-as-a-Service, from Its Creators"; MCP gateway included. |
| [Traefik AI Gateway](https://traefik.io/solutions/ai-gateway/) | Self-host, cloud | OpenAI, Anthropic, Azure OpenAI, Bedrock, Cohere, Gemini, Mistral, Ollama | "Enterprise AI Gateway with Built-In, Responsible AI Guardrails"; NVIDIA Safety NIMs, Presidio PII (35+ recognizers), semantic caching claimed 40-70 percent cost savings. |
| [NVIDIA NIM](https://www.nvidia.com/en-us/ai/) | Self-host, cloud | Open-model + NVIDIA-optimized | "NVIDIA NIM microservices for streamlined AI model deployment"; TensorRT-LLM-backed; OpenAI-compatible APIs. |
| [Together AI](https://www.together.ai/) | Cloud | Open-model catalog | "Build what's next on the AI Native Cloud"; serverless inference, batch, dedicated, GPU clusters, fine-tuning. |
| [Anyscale](https://www.anyscale.com/) | Cloud, self-host | BYO models | "Production-scale AI with Ray"; built on Ray (500M+ downloads, 41K+ GitHub stars). |
| [LangDB](https://www.langdb.ai/) | Cloud, self-host | Multi-provider | Enterprise AI gateway for routing and governing LLM traffic; homepage was unreachable during this profiling pass. |
| [Gentrace](https://github.com/gentrace/gentrace) | OSS (archived, MIT) | n/a | AI evaluation product; company shut down, codebase released as MIT open source. |

## Common Properties

- [GitHubOrganization](https://github.com/api-evangelist) — API Evangelist
- [JSON Schema — AI Gateway Route](json-schema/ai-gateway-route-schema.json)
- [JSON Schema — AI Gateway Provider](json-schema/ai-gateway-provider-schema.json)
- [JSON Schema — AI Gateway Policy](json-schema/ai-gateway-policy-schema.json)
- [JSON-LD Context](json-ld/ai-gateway-context.jsonld)
- [Vocabulary](vocabulary/ai-gateway-vocabulary.yml)
- [Blog](https://apievangelist.com/category/ai-gateway/)

## Features

| Name | Description |
|------|-------------|
| Provider Abstraction | A unified, typically OpenAI-compatible API surface across many LLM providers. |
| Model Routing | Route by alias, header, identity, time-of-day, cost, or latency. |
| Fallback and Failover | Retry failed requests against backup providers when a primary upstream is degraded. |
| Load Balancing and Fanout | Weighted, priority-based, or RPM/TPM-aware distribution; fanout to evaluation panels. |
| Response Caching | Exact-match and semantic caching with TTL and similarity thresholds. |
| Cost Controls and Budgets | Per-user, per-team, per-key, per-project budgets and spend tracking. |
| Rate Limiting and Quotas | RPM, TPM, concurrency, and per-key quotas enforced at the gateway. |
| Guardrails and Prompt Firewall | PII redaction, prompt-injection detection, jailbreak filtering, toxicity, topic control. |
| Observability | Token, cost, latency, and trace data exported via OpenTelemetry, Langfuse, Phoenix, Langsmith. |
| Authentication and RBAC | Virtual keys, JWT, OAuth2, SSO, role-based access control. |
| BYOK and Secret Management | Bring-your-own provider keys with gateway-managed injection. |
| Multi-Tenant Governance | Per-tenant isolation of keys, budgets, logs, and policies. |
| MCP Federation | Some gateways also federate Model Context Protocol servers and expose a unified MCP endpoint. |

## Use Cases

| Name | Description |
|------|-------------|
| Provider-Agnostic LLM Access | One API in front of many providers; swap models without changing client code. |
| Cost Containment for AI | Cache, route to cheaper models, and cap spend per team. |
| Reliability and Failover | Survive single-provider outages with automatic backup-model routing. |
| Centralized AI Governance | Enforce content, PII, and policy controls in one place. |
| Observability and FinOps | Attribute cost and latency to teams, projects, and users. |
| Multi-Tenant AI Platforms | Internal AI platforms with per-team virtual keys, budgets, and logs. |

## Integrations

| Name | Description |
|------|-------------|
| OpenAI | GPT, embeddings, and image models behind the gateway. |
| Anthropic | Claude requests with fallback, caching, and observability. |
| Google Gemini and Vertex AI | Gemini and Vertex calls with OpenAI-format translation. |
| AWS Bedrock | OpenAI-format clients bridged to Bedrock-hosted models. |
| Azure OpenAI | Azure-hosted OpenAI deployments with per-region failover. |
| Ollama and vLLM | Self-hosted Ollama and vLLM inference servers for hybrid inference. |
| OpenTelemetry | Token, cost, and trace data to any OTel-compatible backend. |
| Langfuse and Phoenix | Prompts, completions, and evaluations to Langfuse and Arize Phoenix. |
| Model Context Protocol | MCP server federation alongside LLM routes for agent workloads. |

## Artifacts

Machine-readable artifacts describing the AI gateway domain.

### JSON Schema

- [AI Gateway Route Schema](json-schema/ai-gateway-route-schema.json) — A single model route binding a client-facing alias and matchers to upstream provider backends with caching, fallback, fanout, rate limit, budget, and guardrails.
- [AI Gateway Provider Schema](json-schema/ai-gateway-provider-schema.json) — An upstream LLM provider backend registered with the gateway, including base URL, wire-format compatibility, BYOK keys, and model catalog.
- [AI Gateway Policy Schema](json-schema/ai-gateway-policy-schema.json) — A reusable policy describing a guardrail, cost control, rate limit, access rule, data-residency constraint, or audit configuration.

### JSON Structure

- [AI Gateway Route Structure](json-structure/ai-gateway-route-structure.json)
- [AI Gateway Provider Structure](json-structure/ai-gateway-provider-structure.json)
- [AI Gateway Policy Structure](json-structure/ai-gateway-policy-structure.json)

### JSON-LD

- [AI Gateway Context](json-ld/ai-gateway-context.jsonld) — Aligns the AI gateway vocabulary with schema.org, dcterms, and XSD types under the `aigw:` namespace.

### Examples

- [Primary Route with Fallback](examples/ai-gateway-route-example.json)
- [Cost-Optimized Route](examples/ai-gateway-cost-route-example.json)
- [Evaluation Fanout Route](examples/ai-gateway-fanout-route-example.json)
- [Provider Registration (OpenAI)](examples/ai-gateway-provider-example.json)
- [Guardrail Policy — PII Redaction](examples/ai-gateway-policy-pii-example.json)
- [Cost Policy — Monthly Team Budget](examples/ai-gateway-policy-budget-example.json)

## Vocabulary

- [AI Gateway Vocabulary](vocabulary/ai-gateway-vocabulary.yml) — Unified taxonomy mapping 10 resources, 16 actions, 7 workflows, and 4 personas across the operational and capability dimensions of the AI gateway category.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
