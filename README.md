<h1 align="center">Sufyan Osamah</h1>

<p align="center">
  <b>Applied-AI engineer.</b> I ship autonomous agentic systems in production —
  Claude Code + MCP orchestration, LLM content pipelines, full-stack on AWS.
</p>

<p align="center">
  <a href="https://sufyanosamah.com">Website</a> ·
  <a href="https://www.linkedin.com/in/REPLACE-ME">LinkedIn</a> ·
  <a href="https://www.npmjs.com/~sufyman">npm</a>
</p>

---

### 🚩 Flagship — an autonomous AI agent organization

I build and solo-operate [**HonestDog**](https://honestdog.de), a German dog
marketplace. To run growth without a team, I built an **AI operating company**: a
CEO agent that reads the business metrics daily, names the single biggest
opportunity, and delegates to a hierarchy of specialist agents that research, write
code, and ship — each fenced behind an explicit, *earned* autonomy model.

→ **[honestdog-ai-ceo](https://github.com/sufyman/honestdog-ai-ceo)** — sanitized
case study: architecture, redacted agent prompts, the Phase 1→2 safety model, and
two production LLM patterns (grounded-generate-then-review; an LLM tie-breaker for
record matching with hallucinated-ID rejection).

### 📦 Published packages

Reusable infrastructure I extracted from production and put on npm:

| Package | What it does |
|---|---|
| [**website-profile-extractor**](https://www.npmjs.com/package/website-profile-extractor) | Fetch a site, hand it to an LLM with a JSON schema, get typed structured data back. Pluggable Anthropic / Gemini / OpenAI backends. |
| [**nextjs-dynamodb-cache**](https://www.npmjs.com/package/nextjs-dynamodb-cache) | Drop-in Next.js 14/15/16 `CacheHandler` storing ISR + tag revalidation in DynamoDB. Survives deploys on ephemeral AWS runtimes. |
| [**directus-sitemap**](https://www.npmjs.com/package/directus-sitemap) | Webhook-driven multi-locale sitemap generator for Directus → S3, with IndexNow ping. |
| [**sitemap-healthcheck**](https://www.npmjs.com/package/sitemap-healthcheck) | Detect silent sitemap corruption in CI — validates index, children, counts, freshness, HTTP status. |
| [**indexnow-notify**](https://www.npmjs.com/package/indexnow-notify) | Tiny zero-dependency IndexNow client — notify Bing/Yandex/Seznam/Naver of URL changes. |
| [**directus-image-presets**](https://www.npmjs.com/package/directus-image-presets) | Resolve Directus file IDs to optimized S3/CloudFront WebP URLs. |
| [**directus-timeouts**](https://www.npmjs.com/package/directus-timeouts) | Opinionated timeout tiers + retry/backoff for Directus clients. |

### 🛠️ What I work on

- **Agentic systems** — Claude Code subagents, MCP tool integrations, multi-agent
  orchestration with safety gates and human-in-the-loop review.
- **LLM in production** — grounded generation, AI review/fact-check gates,
  structured output, LLM-as-judge, multi-locale content pipelines at scale.
- **Full-stack + infra** — Next.js (App Router), NestJS, PostgreSQL, AWS
  (Lambda, ECS, Amplify, DynamoDB, S3, CloudFront).

<p align="center"><i>Open to Applied AI / Solutions Architect / Forward-Deployed Engineer roles.</i></p>
