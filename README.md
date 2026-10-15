# Awesome-AI-Gateway-Routing

# Top AI Gateway & Routing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Multi-Provider Routing, Fallback Logic & Unified Model Endpoints*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Gateway & Routing**. These tools sit between your application and model providers—normalizing APIs, routing requests intelligently, handling failover, enforcing budgets, and giving you a single endpoint for Claude, GPT, Gemini, Llama, and everything else.

**Examples** include Portkey, Helicone, LiteLLM Cloud, Cloudflare AI Gateway, Kong AI Gateway, Martian, Langfuse, PromptLayer, Maxim AI, and OmniRoute (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, multi-provider gateways, and open routing infrastructure—ideal for AI engineers, platform teams, and developers seeking transparent, vendor-independent model access.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Portkey](https://portkey.ai/)**  
  **Blazing fast AI gateway with 1,600+ models and 45+ guardrails.** Features **routing strategies** (fallback, load balance, conditional), **caching**, **retries**, and **observability**. SOC 2, HIPAA, GDPR compliant. **The most feature-rich managed AI gateway for production.**

- **[Helicone](https://www.helicone.ai/)**  
  YC W23. **Proxy-first observability**—change `api.openai.com` to `oai.helicone.ai` for zero-code logging. Also supports async SDK mode. Features **caching, 100+ models, cost tracking**, and growing eval/prompt capabilities. **Acquired by Mintlify in March 2026 and in maintenance mode** .

- **[LiteLLM Cloud](https://www.litellm.ai/)**  
  Managed version of the open-source LiteLLM proxy. **100+ LLM APIs through OpenAI-compatible interface.** Features **cost tracking per key/user/team**, **rate limiting**, **fallback routing**, **load balancing**, **caching**, and **budget enforcement**. **The most widely adopted managed gateway** for teams wanting hosted LiteLLM.

- **[Cloudflare AI Gateway](https://www.cloudflare.com/developer-platform/ai-gateway/)**  
  **Cloudflare's AI gateway** for observability, caching, and rate limiting across providers. Features **analytics**, **cost tracking**, and **fallback**. **The most cloud-native managed gateway.**

- **[Kong AI Gateway](https://konghq.com/products/kong-ai-gateway)**  
  **Kong's AI gateway** extending the Kong Gateway platform with AI-specific plugins. Features **multi-provider routing**, **semantic caching**, **prompt guarding**, and **observability**. **Best for teams already using Kong Gateway.**

- **[Martian](https://withmartian.com/)**  
  **AI routing and optimization platform.** Routes queries to the best model based on cost, quality, and latency—with proprietary router that adapts to your use case. **The most specialized routing-only managed service.**

- **[PromptLayer](https://promptlayer.com/)**  
  **Prompt management and observability platform.** Features prompt versioning, evaluation, and collaboration. **The most focused managed prompt engineering platform.**

- **[Maxim AI](https://www.getmaxim.ai/)**  
  **AI evaluation and observability platform.** Features agent simulation, evaluation workflows, and production monitoring.

- **[Langfuse Cloud](https://langfuse.com/)**  
  Managed version of the open-source Langfuse platform. Features tracing, evaluations, prompt management, and datasets. **Acquired by ClickHouse in January 2026 with commitment to keep it open source.**

## Open-Source GitHub Projects

- **[LiteLLM](https://github.com/BerriAI/litellm)**  
  **The most comprehensive open-source multi-provider gateway** — **100+ LLM APIs through OpenAI-compatible interface** (MIT). **20,000+ GitHub stars.** Features **cost tracking per key/user/team**, **rate limiting**, **fallback routing**, **load balancing**, **caching**, and **budget enforcement**. **The de facto standard for multi-model orchestration** — powers many other aggregators including LibreChat, Open WebUI, and Dify . **The most widely deployed open-source AI gateway.**

- **[Portkey Gateway](https://github.com/Portkey-AI/gateway)**  
  **Blazing fast AI gateway** with **250+ models and 45+ guardrails** (Apache-2.0) . **10,000+ GitHub stars.** Features **routing strategies** (fallback, load balance, conditional), **caching**, **retries**, and **observability**. **The most feature-rich open-source AI gateway for production.**

- **[RouteLLM](https://github.com/lm-sys/RouteLLM)**  
  **Framework for serving and evaluating LLM routers** (Apache-2.0) . **The leading open-source cost-optimized router** —route queries to appropriate model based on complexity. Features **cost-quality tradeoff optimization**, **framework compatibility** (OpenAI client, LangChain), and **pre-trained routers** based on human preference data. **Achieves significant cost savings without quality degradation.**

- **[AI Gateway (Cloudflare)](https://github.com/cloudflare/ai-gateway)**  
  Open-source AI gateway for **observability, caching, and rate limiting** across providers (MIT) . Features **analytics**, **cost tracking**, and **fallback** .

- **[OmniRoute](https://github.com/diegosouzapw/OmniRoute)**  
  **Free AI gateway providing access to 90+ free API providers** for Claude Code and other agent harnesses (open-source) . **The most accessible open-source gateway for free model access.** Features **automatic fallback** when providers rate-limit, **model switching** without manual intervention, and **integration with compression tools** like RTK and Caveman . Works with FreeClaude Code (open-source Claude Code harness) to provide free AI coding without subscription . **Note**: Requires community-maintained provider list—availability varies by region and provider status .

- **[Bifrost (Maxim AI)](https://github.com/maximhq/bifrost)**  
  **Fastest enterprise-grade LLM gateway** (open-source) . **Claims to be the fastest LLM gateway in the market** with drop-in OpenAI-compatible replacement for OpenAI, Anthropic, Bedrock, and 15+ providers. Features **automatic failover**, **load balancing**, **semantic caching**, **budget management**, and **observability** .

- **[Langfuse](https://github.com/langfuse/langfuse)**  
  **Open-source LLM engineering platform** (MIT core) with tracing, evaluations, prompt management, and datasets . **35,000+ GitHub stars.** Self-hostable. **Acquired by ClickHouse in January 2026 with commitment to keep it open source** .

- **[OpenRouter](https://openrouter.ai/)**  
  **The dominant AI model aggregator** — **400+ models from 60+ providers** through a single OpenAI-compatible API . Features **automatic failover** when providers are down, **cost-optimized routing** (pick cheapest provider for same model), **BYOK (Bring Your Own Keys)** support, and **provider-level preferences** . **The de facto standard for multi-model access** — most open-source aggregators integrate with OpenRouter as a provider rather than building direct provider connections.

- **[Portkey Gateway (Self-Hosted)](https://github.com/Portkey-AI/gateway)**  
  See Portkey above.

### Additional Strong Open-Source Options

- **[Kong AI Gateway (Open Source)](https://github.com/Kong/kong)** — Kong Gateway with AI plugins (Apache-2.0) . Features multi-provider routing, semantic caching, and prompt guarding.
- **[Apache APISIX AI Gateway](https://github.com/apache/apisix)** — APISIX with AI proxy plugins (Apache-2.0) . **The most widely deployed open-source API gateway** with AI capabilities.
- **[Envoy AI Gateway](https://github.com/envoyproxy/ai-gateway)** — Envoy-based AI gateway (Apache-2.0) . **The most standards-based approach** —builds on Envoy's battle-tested proxy.
- **[Semantic Router](https://github.com/aurelio-labs/semantic-router)** — Open-source semantic routing library (MIT) for intent-based model selection.
- **[GPTCache](https://github.com/zilliztech/GPTCache)** — Open-source semantic caching for LLMs (MIT) . **The most widely used caching layer for AI gateways.**
- **[Envoy AI Gateway](https://github.com/envoyproxy/ai-gateway)** — See above.
- Community **n8n** workflows for AI gateway monitoring and cost alert automation.

**Frameworks for building custom systems**: Combine **LiteLLM** for multi-provider gateway with **Portkey Gateway** for production routing and guardrails, **RouteLLM** for cost-optimized model selection, **GPTCache** for semantic caching, and **Langfuse** for observability—creating a fully self-hosted, enterprise-grade AI gateway platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AI gateways handling prompts and API keys must comply with data protection regulations (GDPR, CCPA, etc.) and provider terms of service.
- **Open-source AI gateways are mature and production-ready.** LiteLLM (20K+ stars) powers multi-provider orchestration for many other tools . Portkey (10K+ stars) provides production-grade routing and guardrails . RouteLLM provides cost-optimized model selection . **These are genuine alternatives to managed platforms.**
- **OpenRouter is the dominant aggregator for a reason.** 400+ models, automatic failover, cost-optimized routing, and BYOK support — most open-source aggregators integrate with OpenRouter as a provider rather than building direct provider connections .
- **RouteLLM is the open-source cost optimization leader.** Route queries to appropriate model based on complexity — achieving significant cost savings without quality degradation . **This is the most sophisticated open-source approach to model selection.**
- **Self-hosted gateways require key management discipline.** LiteLLM and Portkey both support virtual keys with budgets and rate limits. **Never embed provider API keys directly in applications** — route through the gateway and issue scoped virtual keys per team, application, or user.
- Self-hosted open-source solutions require proper security hardening, API key management, and ongoing maintenance. AI gateways handle sensitive credentials — access controls and audit trails are essential.

---

**Made for AI engineers, platform teams, and developers building transparent AI gateway solutions.**  
Let's make AI Gateway & Routing more open, data-driven, and provider-independent.
