# AI Gateway

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

An API Evangelist landscape index of AI gateways — the LLM routers, prompt firewalls, model fallback proxies, cost-control planes, and policy engines that sit between applications and AI providers. AI gateways unify access across OpenAI, Anthropic, Google, AWS Bedrock, Azure OpenAI, and self-hosted models behind a common interface and apply caching, routing, guardrails, observability, rate limiting, budgets, RBAC, and audit controls. This index catalogs commercial SaaS gateways, open-source projects, API gateway AI plugins, and cloud-provider AI proxies, with a shared schema and vocabulary for describing model routes, fallbacks, guardrails, and budgets across vendors.

**Areas:** AI Gateway · LLM Router · LLM Proxy · Model Routing · Prompt Firewall · Guardrails · AI Observability · Cost Controls · AI Governance · API Gateway

## AI Gateway on APIs.io

Everything profiled for AI Gateway is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ai-gateway/](https://apis.io/providers/ai-gateway/)** — or go straight to one of the APIs or properties below.

### APIs (41)

- [Portkey](https://apis.io/apis/ai-gateway/portkey/) — Portkey is a production-grade AI gateway and control plane that fronts 1,600+ LLMs with unified routing, fallbacks, semantic caching, guardrails, cost…
- [OpenRouter](https://apis.io/apis/ai-gateway/openrouter/) — OpenRouter is a unified inference marketplace exposing 400+ models from 60+ providers behind one OpenAI-compatible API, with automatic provider fallback,…
- [LiteLLM](https://apis.io/apis/ai-gateway/litellm/) — LiteLLM (BerriAI) is an open-source LLM gateway that exposes 100+ LLM providers — OpenAI, Anthropic, Azure, Bedrock, Gemini — through a single…
- [Helicone](https://apis.io/apis/ai-gateway/helicone/) — Helicone is an open-source AI observability and routing platform centered on requests, sessions, prompts, datasets, rate limits, and alerts. Integrates with…
- [Cloudflare AI Gateway](https://apis.io/apis/ai-gateway/cloudflare-ai-gateway/) — Cloudflare AI Gateway is an edge-deployed proxy that fronts AI providers — Workers AI, Anthropic, Google Gemini, OpenAI, Replicate, and more — with caching,…
- [Kong AI Gateway](https://apis.io/apis/ai-gateway/kong-ai-gateway/) — The Kong AI Gateway is delivered as the AI Proxy plugin for Kong Gateway, transforming and proxying requests across 16+ providers including OpenAI, Azure…
- [Apache APISIX AI Proxy](https://apis.io/apis/ai-gateway/apisix-ai-proxy/) — The Apache APISIX ai-proxy plugin streamlines integration with LLMs by converting plugin settings into the appropriate request format for OpenAI, DeepSeek,…
- [Tetrate Agent Router Service](https://apis.io/apis/ai-gateway/tetrate-agent-router/) — Tetrate Agent Router Service is an Envoy AI Gateway-as-a-service from the creators of Envoy, providing an approved LLM catalog, unified model access,…
- [NVIDIA NIM](https://apis.io/apis/ai-gateway/nvidia-nim/) — NVIDIA NIM is a set of inference microservices for streamlined AI model deployment, prebuilt and optimized for low-latency, high-throughput inference on…
- [Traefik AI Gateway](https://apis.io/apis/ai-gateway/traefik-ai-gateway/) — Traefik AI Gateway is an enterprise, self-hosted, Kubernetes-native AI gateway with safety and governance (NVIDIA Safety NIMs, jailbreak detection, content…
- [Together AI](https://apis.io/apis/ai-gateway/together-ai/) — Together AI is a full-stack AI Native Cloud for inference, fine-tuning, and GPU clusters powered by research, exposing serverless inference, batch…
- [Anyscale](https://apis.io/apis/ai-gateway/anyscale/) — Anyscale is the production-scale AI platform built on Ray by the creators of Ray, supporting LLM inference and other data-intensive AI workloads across…
- [LangDB](https://apis.io/apis/ai-gateway/langdb/) — LangDB is an enterprise AI gateway for routing and governing LLM traffic across providers, with observability, cost tracking, and policy enforcement. Public…
- [Envoy AI Gateway](https://apis.io/apis/ai-gateway/envoy-ai-gateway/) — Envoy AI Gateway is an open-source extension to Envoy Proxy and Envoy Gateway, providing a Kubernetes-native AI traffic plane for routing, governing, and…
- [GoModel](https://apis.io/apis/ai-gateway/gomodel/) — GoModel (ENTERPILOT) is an open-source AI gateway written in Go that fronts OpenAI, Anthropic, Gemini, Groq, xAI, Ollama, vLLM, and other providers behind…
- [Bifrost](https://apis.io/apis/ai-gateway/bifrost/) — Bifrost (Maxim AI) is an open-source AI gateway written in Go that exposes 20+ providers, including OpenAI, Anthropic, AWS Bedrock, and Google Vertex,…
- [Spillway](https://apis.io/apis/ai-gateway/spillway/) — Spillway is an open-source, self-hosted AI gateway written in TypeScript, distributed as a single Docker container with an admin UI and SQLite storage. It…
- [Gentrace](https://apis.io/apis/ai-gateway/gentrace/) — Gentrace was an AI evaluation and observability product; the company has shut down and its codebase is now MIT-licensed open source on GitHub. Included here…
- [AI Gateway Analytics API](https://apis.io/apis/ai-gateway/ai-gateway-analytics-api/) — The Analytics API from AI Gateway — 2 operation(s) for analytics.
- [AI Gateway Assistants API](https://apis.io/apis/ai-gateway/ai-gateway-assistants-api/) — The Assistants API from AI Gateway — 1 operation(s) for assistants.
- [AI Gateway Audio API](https://apis.io/apis/ai-gateway/ai-gateway-audio-api/) — The Audio API from AI Gateway — 3 operation(s) for audio.
- [AI Gateway Batches API](https://apis.io/apis/ai-gateway/ai-gateway-batches-api/) — The Batches API from AI Gateway — 2 operation(s) for batches.
- [AI Gateway Completions API](https://apis.io/apis/ai-gateway/ai-gateway-completions-api/) — The Completions API from AI Gateway — 1 operation(s) for completions.
- [AI Gateway Configs API](https://apis.io/apis/ai-gateway/ai-gateway-configs-api/) — The Configs API from AI Gateway — 1 operation(s) for configs.
- [AI Gateway Embeddings API](https://apis.io/apis/ai-gateway/ai-gateway-embeddings-api/) — The Embeddings API from AI Gateway — 2 operation(s) for embeddings.
- [AI Gateway Feedback API](https://apis.io/apis/ai-gateway/ai-gateway-feedback-api/) — The Feedback API from AI Gateway — 1 operation(s) for feedback.
- [AI Gateway Files API](https://apis.io/apis/ai-gateway/ai-gateway-files-api/) — The Files API from AI Gateway — 2 operation(s) for files.
- [AI Gateway Guardrails API](https://apis.io/apis/ai-gateway/ai-gateway-guardrails-api/) — The Guardrails API from AI Gateway — 1 operation(s) for guardrails.
- [AI Gateway Images API](https://apis.io/apis/ai-gateway/ai-gateway-images-api/) — The Images API from AI Gateway — 1 operation(s) for images.
- [AI Gateway Integrations API](https://apis.io/apis/ai-gateway/ai-gateway-integrations-api/) — The Integrations API from AI Gateway — 2 operation(s) for integrations.
- [AI Gateway Logs API](https://apis.io/apis/ai-gateway/ai-gateway-logs-api/) — The Logs API from AI Gateway — 2 operation(s) for logs.
- [AI Gateway MCP API](https://apis.io/apis/ai-gateway/ai-gateway-mcp-api/) — The MCP API from AI Gateway — 2 operation(s) for mcp.
- [AI Gateway Policies API](https://apis.io/apis/ai-gateway/ai-gateway-policies-api/) — The Policies API from AI Gateway — 2 operation(s) for policies.
- [AI Gateway Prompts API](https://apis.io/apis/ai-gateway/ai-gateway-prompts-api/) — The Prompts API from AI Gateway — 6 operation(s) for prompts.
- [AI Gateway Responses API](https://apis.io/apis/ai-gateway/ai-gateway-responses-api/) — The Responses API from AI Gateway — 1 operation(s) for responses.
- [AI Gateway Threads API](https://apis.io/apis/ai-gateway/ai-gateway-threads-api/) — The Threads API from AI Gateway — 3 operation(s) for threads.
- [AI Gateway Workspaces API](https://apis.io/apis/ai-gateway/ai-gateway-workspaces-api/) — The Workspaces API from AI Gateway — 4 operation(s) for workspaces.
- [AI Gateway API Keys API](https://apis.io/apis/ai-gateway/ai-gateway-api-keys-api/) — The API Keys API from AI Gateway — 1 operation(s) for api keys.
- [AI Gateway Chat Completions API](https://apis.io/apis/ai-gateway/ai-gateway-chat-completions-api/) — The Chat Completions API from AI Gateway — 1 operation(s) for chat completions.
- [AI Gateway Fine Tuning API](https://apis.io/apis/ai-gateway/ai-gateway-fine-tuning-api/) — The Fine Tuning API from AI Gateway — 2 operation(s) for fine tuning.
- [AI Gateway Virtual Keys API](https://apis.io/apis/ai-gateway/ai-gateway-virtual-keys-api/) — The Virtual Keys API from AI Gateway — 1 operation(s) for virtual keys.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ai Gateway Agentic Access](https://apis.io/agentic-access/ai-gateway/ai-gateway-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [AIGatewayPolicy](https://apis.io/schemas/ai-gateway/ai-gateway-policy/)
- [AIGatewayProvider](https://apis.io/schemas/ai-gateway/ai-gateway-provider/)
- [AIGatewayRoute](https://apis.io/schemas/ai-gateway/ai-gateway-route/)

#### JSON Structure (3)

Data models expressed in JSON Structure.

- [Ai Gateway Policy Structure](https://apis.io/json-structure/ai-gateway/ai-gateway-policy-structure/)
- [Ai Gateway Provider Structure](https://apis.io/json-structure/ai-gateway/ai-gateway-provider-structure/)
- [Ai Gateway Route Structure](https://apis.io/json-structure/ai-gateway/ai-gateway-route-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ai Gateway Context](https://apis.io/jsonld/ai-gateway/ai-gateway-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Ai Gateway Vocabulary](https://apis.io/vocabularies/ai-gateway/ai-gateway-vocabulary/)

#### Examples (6)

Example requests and responses.

- [Ai Gateway Cost Route Example](https://apis.io/examples/ai-gateway/ai-gateway-cost-route-example/)
- [Ai Gateway Fanout Route Example](https://apis.io/examples/ai-gateway/ai-gateway-fanout-route-example/)
- [Ai Gateway Policy Budget Example](https://apis.io/examples/ai-gateway/ai-gateway-policy-budget-example/)
- [Ai Gateway Policy Pii Example](https://apis.io/examples/ai-gateway/ai-gateway-policy-pii-example/)
- [Ai Gateway Provider Example](https://apis.io/examples/ai-gateway/ai-gateway-provider-example/)
- [Ai Gateway Route Example](https://apis.io/examples/ai-gateway/ai-gateway-route-example/)

#### Collections (24)

Postman and Open Collection request collections.

- [Portkey AI Gateway API](https://apis.io/collections/ai-gateway/open-ai-gateway/)
- [Portkey AI Gateway Analytics API](https://apis.io/collections/ai-gateway/open-ai-gateway-analytics-api/)
- [Portkey AI Gateway Analytics APIKeys API](https://apis.io/collections/ai-gateway/open-ai-gateway-apikeys-api/)
- [Portkey AI Gateway Analytics Assistants API](https://apis.io/collections/ai-gateway/open-ai-gateway-assistants-api/)
- [Portkey AI Gateway Analytics Audio API](https://apis.io/collections/ai-gateway/open-ai-gateway-audio-api/)
- [Portkey AI Gateway Analytics Batches API](https://apis.io/collections/ai-gateway/open-ai-gateway-batches-api/)
- [Portkey AI Gateway Analytics Chat API](https://apis.io/collections/ai-gateway/open-ai-gateway-chat-api/)
- [Portkey AI Gateway Analytics Completions API](https://apis.io/collections/ai-gateway/open-ai-gateway-completions-api/)
- [Portkey AI Gateway Analytics Configs API](https://apis.io/collections/ai-gateway/open-ai-gateway-configs-api/)
- [Portkey AI Gateway Analytics Embeddings API](https://apis.io/collections/ai-gateway/open-ai-gateway-embeddings-api/)
- [Portkey AI Gateway Analytics Feedback API](https://apis.io/collections/ai-gateway/open-ai-gateway-feedback-api/)
- [Portkey AI Gateway Analytics Files API](https://apis.io/collections/ai-gateway/open-ai-gateway-files-api/)
- [Portkey AI Gateway Analytics FineTuning API](https://apis.io/collections/ai-gateway/open-ai-gateway-finetuning-api/)
- [Portkey AI Gateway Analytics Guardrails API](https://apis.io/collections/ai-gateway/open-ai-gateway-guardrails-api/)
- [Portkey AI Gateway Analytics Images API](https://apis.io/collections/ai-gateway/open-ai-gateway-images-api/)
- [Portkey AI Gateway Analytics Integrations API](https://apis.io/collections/ai-gateway/open-ai-gateway-integrations-api/)
- [Portkey AI Gateway Analytics Logs API](https://apis.io/collections/ai-gateway/open-ai-gateway-logs-api/)
- [Portkey AI Gateway Analytics MCP API](https://apis.io/collections/ai-gateway/open-ai-gateway-mcp-api/)
- [Portkey AI Gateway Analytics Policies API](https://apis.io/collections/ai-gateway/open-ai-gateway-policies-api/)
- [Portkey AI Gateway Analytics Prompts API](https://apis.io/collections/ai-gateway/open-ai-gateway-prompts-api/)
- [Portkey AI Gateway Analytics Responses API](https://apis.io/collections/ai-gateway/open-ai-gateway-responses-api/)
- [Portkey AI Gateway Analytics Threads API](https://apis.io/collections/ai-gateway/open-ai-gateway-threads-api/)
- [Portkey AI Gateway Analytics VirtualKeys API](https://apis.io/collections/ai-gateway/open-ai-gateway-virtualkeys-api/)
- [Portkey AI Gateway Analytics Workspaces API](https://apis.io/collections/ai-gateway/open-ai-gateway-workspaces-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [AI Gateway — jsonschema rules](https://apis.io/rules/ai-gateway/ai-gateway-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ai Gateway Authentication](https://apis.io/security/ai-gateway/ai-gateway-authentication/)
- [Ai Gateway Domain Security](https://apis.io/security/ai-gateway/ai-gateway-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Blog](https://apievangelist.com/category/ai-gateway/)

## API Evangelist rating

**Unrated** — no public website could be reached for this company, so there was almost nothing to measure and nothing a reader could check.

This is not a score of zero. No rating is published for this company. If that is wrong because something public exists that we missed, say so on this repository or email [info@apievangelist.com](mailto:info@apievangelist.com) and it will be re-run — free, and no justification needed.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for AI Gateway: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ai-gateway/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
