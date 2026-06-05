# AI Gateway (ai-gateway)

An API Evangelist landscape index of AI gateways — the LLM routers, prompt firewalls, model fallback proxies, cost-control planes, and policy engines that sit between applications and AI providers. AI gateways unify access across OpenAI, Anthropic, Google, AWS Bedrock, Azure OpenAI, and self-hosted models behind a common interface and apply caching, routing, guardrails, observability, rate limiting, budgets, RBAC, and audit controls. This index catalogs commercial SaaS gateways, open-source projects, API gateway AI plugins, and cloud-provider AI proxies, with a shared schema and vocabulary for describing model routes, fallbacks, guardrails, and budgets across vendors.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ai-gateway/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ai-gateway/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- AI Gateway
- LLM Router
- LLM Proxy
- Model Routing
- Prompt Firewall
- Guardrails
- AI Observability
- Cost Controls
- AI Governance
- API Gateway

## Timestamps

- **Created:** 2026-05-22
- **Modified:** 2026-05-22

## APIs

### Portkey

Portkey is a production-grade AI gateway and control plane that fronts 1,600+ LLMs with unified routing, fallbacks, semantic caching, guardrails, cost attribution, and prompt management. The open-source Portkey Gateway is MIT-licensed; a hosted SaaS adds governance, observability, and enterprise controls.

- **Human URL:** [https://portkey.ai/](https://portkey.ai/)
- **Base URL:** `https://api.portkey.ai`

#### Tags

- AI Gateway
- LLM Router
- Guardrails
- Observability
- Prompt Management
- Open Source

#### Properties

- [Portal](https://portkey.ai/)
- [Documentation](https://portkey.ai/docs/)
- [GitHub Repository](https://github.com/Portkey-AI/gateway)
- [GitHub Organization](https://github.com/Portkey-AI)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenRouter

OpenRouter is a unified inference marketplace exposing 400+ models from 60+ providers behind one OpenAI-compatible API, with automatic provider fallback, pay-as-you-go credits, custom data policies, and edge-routed latency optimization. It is a proprietary SaaS service.

- **Human URL:** [https://openrouter.ai/](https://openrouter.ai/)
- **Base URL:** `https://openrouter.ai/api/v1`

#### Tags

- AI Gateway
- LLM Marketplace
- Multi-Provider
- Fallback
- Proprietary

#### Properties

- [Portal](https://openrouter.ai/)
- [Documentation](https://openrouter.ai/docs)
- [Models](https://openrouter.ai/models)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LiteLLM

LiteLLM (BerriAI) is an open-source LLM gateway that exposes 100+ LLM providers — OpenAI, Anthropic, Azure, Bedrock, Gemini — through a single OpenAI-compatible API. The LiteLLM Proxy adds virtual keys, load balancing, RPM/TPM limits, spend tracking, and observability hooks for Langfuse, Phoenix, Langsmith, and OpenTelemetry. Self-hostable via Docker; enterprise support available.

- **Human URL:** [https://www.litellm.ai/](https://www.litellm.ai/)
- **Base URL:** `https://api.litellm.ai`

#### Tags

- AI Gateway
- LLM Proxy
- Open Source
- Cost Tracking
- Load Balancing

#### Properties

- [Portal](https://www.litellm.ai/)
- [Documentation](https://docs.litellm.ai/)
- [GitHub Repository](https://github.com/BerriAI/litellm)
- [Py P I](https://pypi.org/project/litellm/)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Helicone

Helicone is an open-source AI observability and routing platform centered on requests, sessions, prompts, datasets, rate limits, and alerts. Integrates with OpenAI, Anthropic, Google Gemini, DeepSeek, Together AI, Mistral, Groq, Azure, OpenRouter, and LiteLLM. Available as managed cloud or self-hosted.

- **Human URL:** [https://www.helicone.ai/](https://www.helicone.ai/)
- **Base URL:** `https://api.helicone.ai`

#### Tags

- AI Gateway
- Observability
- Prompt Management
- Open Source
- Caching

#### Properties

- [Portal](https://www.helicone.ai/)
- [Documentation](https://docs.helicone.ai/)
- [GitHub Repository](https://github.com/Helicone/helicone)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cloudflare AI Gateway

Cloudflare AI Gateway is an edge-deployed proxy that fronts AI providers — Workers AI, Anthropic, Google Gemini, OpenAI, Replicate, and more — with caching, rate limiting, analytics, and request logging. Available on all Cloudflare plans.

- **Human URL:** [https://developers.cloudflare.com/ai-gateway/](https://developers.cloudflare.com/ai-gateway/)
- **Base URL:** `https://gateway.ai.cloudflare.com`

#### Tags

- AI Gateway
- Edge
- Caching
- Rate Limiting
- Analytics

#### Properties

- [Portal](https://www.cloudflare.com/developer-platform/ai-gateway/)
- [Documentation](https://developers.cloudflare.com/ai-gateway/)
- [Getting Started](https://developers.cloudflare.com/ai-gateway/get-started/)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kong AI Gateway

The Kong AI Gateway is delivered as the AI Proxy plugin for Kong Gateway, transforming and proxying requests across 16+ providers including OpenAI, Azure OpenAI, Anthropic, Amazon Bedrock, Gemini, Vertex AI, Cohere, Mistral, Hugging Face, Llama, xAI, Ollama, Alibaba DashScope, Cerebras, DeepSeek, Databricks, and vLLM. Supports chat, completions, embeddings, assistants, audio, image, video, batches, and files routes with template-based model selection.

- **Human URL:** [https://konghq.com/products/kong-ai-gateway](https://konghq.com/products/kong-ai-gateway)
- **Base URL:** `https://konghq.com`

#### Tags

- AI Gateway
- API Gateway
- Multi-Provider
- Plugin
- Kong

#### Properties

- [Portal](https://konghq.com/products/kong-ai-gateway)
- [Documentation](https://developer.konghq.com/plugins/ai-proxy/)
- [GitHub Organization](https://github.com/Kong)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache APISIX AI Proxy

The Apache APISIX ai-proxy plugin streamlines integration with LLMs by converting plugin settings into the appropriate request format for OpenAI, DeepSeek, Azure OpenAI, Anthropic, Google Gemini, Vertex AI, OpenRouter, AIMLAPI, and OpenAI-compatible services. Supports embedding models, observability of token usage and latency, custom endpoints, and flexible authentication. Apache 2.0 licensed.

- **Human URL:** [https://apisix.apache.org/](https://apisix.apache.org/)
- **Base URL:** `https://apisix.apache.org`

#### Tags

- AI Gateway
- API Gateway
- Open Source
- Apache
- Plugin

#### Properties

- [Portal](https://apisix.apache.org/)
- [Documentation](https://apisix.apache.org/docs/apisix/plugins/ai-proxy/)
- [GitHub Repository](https://github.com/apache/apisix)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tetrate Agent Router Service

Tetrate Agent Router Service is an Envoy AI Gateway-as-a-service from the creators of Envoy, providing an approved LLM catalog, unified model access, automatic fallback, cost management, AI guardrails, and an MCP gateway for agent tool connectivity. Built on Envoy AI Gateway.

- **Human URL:** [https://tetrate.io/products/tetrate-agent-router-service/](https://tetrate.io/products/tetrate-agent-router-service/)
- **Base URL:** `https://tetrate.io`

#### Tags

- AI Gateway
- Envoy
- MCP Gateway
- Guardrails
- Multi-Provider

#### Properties

- [Portal](https://tetrate.io/products/tetrate-agent-router-service/)
- [Documentation](https://docs.tetrate.io/)
- [GitHub Organization](https://github.com/envoyproxy)
- [GitHub Repository](https://github.com/envoyproxy/ai-gateway)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NVIDIA NIM

NVIDIA NIM is a set of inference microservices for streamlined AI model deployment, prebuilt and optimized for low-latency, high-throughput inference on NVIDIA-accelerated infrastructure. Includes TensorRT and TensorRT-LLM-backed engines and exposes stable OpenAI-compatible APIs for self-hosted and cloud deployment.

- **Human URL:** [https://www.nvidia.com/en-us/ai/](https://www.nvidia.com/en-us/ai/)
- **Base URL:** `https://build.nvidia.com`

#### Tags

- AI Gateway
- Inference
- Self-Hosted
- NVIDIA
- GPU

#### Properties

- [Portal](https://build.nvidia.com/)
- [Documentation](https://docs.nvidia.com/nim/)
- [GitHub Organization](https://github.com/NVIDIA)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Traefik AI Gateway

Traefik AI Gateway is an enterprise, self-hosted, Kubernetes-native AI gateway with safety and governance (NVIDIA Safety NIMs, jailbreak detection, content filtering across 22+ categories), multi-LLM support via an OpenAI-compatible interface (Anthropic, Azure OpenAI, AWS Bedrock, Cohere, Gemini, Mistral, Ollama), intelligent routing, credential management, semantic caching with claimed 40-70 percent cost savings, PII protection via Presidio (35+ recognizers), and OpenTelemetry observability.

- **Human URL:** [https://traefik.io/solutions/ai-gateway/](https://traefik.io/solutions/ai-gateway/)
- **Base URL:** `https://traefik.io`

#### Tags

- AI Gateway
- Kubernetes
- Guardrails
- Semantic Caching
- PII Protection

#### Properties

- [Portal](https://traefik.io/solutions/ai-gateway/)
- [Documentation](https://doc.traefik.io/)
- [GitHub Organization](https://github.com/traefik)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Together AI

Together AI is a full-stack AI Native Cloud for inference, fine-tuning, and GPU clusters powered by research, exposing serverless inference, batch processing, dedicated model and container inference, GPU clusters, fine-tuning, managed storage, and code sandboxes for open-source models.

- **Human URL:** [https://www.together.ai/](https://www.together.ai/)
- **Base URL:** `https://api.together.xyz`

#### Tags

- Inference
- Open Models
- GPU
- Multi-Provider
- SaaS

#### Properties

- [Portal](https://www.together.ai/)
- [Documentation](https://docs.together.ai/)
- [GitHub Organization](https://github.com/togethercomputer)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Anyscale

Anyscale is the production-scale AI platform built on Ray by the creators of Ray, supporting LLM inference and other data-intensive AI workloads across distributed GPU clusters. Integrates with vLLM and SkyRL; users bring their own models.

- **Human URL:** [https://www.anyscale.com/](https://www.anyscale.com/)
- **Base URL:** `https://api.endpoints.anyscale.com`

#### Tags

- Inference
- Ray
- GPU
- Open Source
- Self-Hosted

#### Properties

- [Portal](https://www.anyscale.com/)
- [Documentation](https://docs.anyscale.com/)
- [GitHub Organization](https://github.com/anyscale)
- [GitHub Repository](https://github.com/ray-project/ray)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### LangDB

LangDB is an enterprise AI gateway for routing and governing LLM traffic across providers, with observability, cost tracking, and policy enforcement. Public homepage was unreachable for direct verification during this profiling pass; see GitHub for current capabilities.

- **Human URL:** [https://www.langdb.ai/](https://www.langdb.ai/)
- **Base URL:** `https://api.langdb.ai`

#### Tags

- AI Gateway
- LLM Router
- Observability
- Cost Tracking

#### Properties

- [Portal](https://www.langdb.ai/)
- [GitHub Organization](https://github.com/langdb)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Envoy AI Gateway

Envoy AI Gateway is an open-source extension to Envoy Proxy and Envoy Gateway, providing a Kubernetes-native AI traffic plane for routing, governing, and observing LLM calls across providers. Apache 2.0 licensed and CNCF-aligned.

- **Human URL:** [https://aigateway.envoyproxy.io/](https://aigateway.envoyproxy.io/)
- **Base URL:** `https://aigateway.envoyproxy.io`

#### Tags

- AI Gateway
- Envoy
- Kubernetes
- CNCF
- Open Source

#### Properties

- [Portal](https://aigateway.envoyproxy.io/)
- [Documentation](https://aigateway.envoyproxy.io/docs/)
- [GitHub Repository](https://github.com/envoyproxy/ai-gateway)
- [GitHub Organization](https://github.com/envoyproxy)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gentrace

Gentrace was an AI evaluation and observability product; the company has shut down and its codebase is now MIT-licensed open source on GitHub. Included here for historical completeness in the AI gateway-adjacent observability category.

- **Human URL:** [https://github.com/gentrace/gentrace](https://github.com/gentrace/gentrace)

#### Tags

- AI Observability
- Open Source
- Archived
- Evaluation

#### Properties

- [GitHub Repository](https://github.com/gentrace/gentrace)
- [Postman Collection](collections/ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ai-gateway/refs/heads/main/json-schema/ai-gateway-route-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ai-gateway/refs/heads/main/json-schema/ai-gateway-provider-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ai-gateway/refs/heads/main/json-schema/ai-gateway-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/ai-gateway/refs/heads/main/json-structure/ai-gateway-route-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/ai-gateway/refs/heads/main/json-structure/ai-gateway-provider-structure.json)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/ai-gateway/refs/heads/main/json-structure/ai-gateway-policy-structure.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/ai-gateway/refs/heads/main/json-ld/ai-gateway-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/ai-gateway/refs/heads/main/vocabulary/ai-gateway-vocabulary.yml)
- [Examples](https://raw.githubusercontent.com/api-evangelist/ai-gateway/refs/heads/main/examples/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Portal](https://github.com/api-evangelist/ai-gateway)
- [Blog](https://apievangelist.com/category/ai-gateway/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
