## Domingos — Software Engineering & Intelligent Systems

Domingos is a software engineering company based in Espírito Santo, Brazil. We design,
build and operate custom systems for companies that have outgrown off-the-shelf tools:
online stores that run the whole order on their own, partner programs with money on the
line, multilingual institutional portals, and AI agents that talk to customers in
production.

The systems below are live with real users. Each case study says plainly what is in
production, what is ready and waiting for release, and what is still being built.

### What we do

- **Custom software engineering**: web platforms built around how the business works, not around a template.
- **Enterprise systems and integrations**: payment gateways, tax invoicing, shipping, ERP and messaging, wired so no one copies data between systems.
- **AI and automation**: LLM agents with deterministic guardrails, regression gates and human handoff.
- **SaaS development**: multi-tenant products, from data model to billing.
- **Software architecture**: decision records, specs before code, and systems split along real ownership lines.

### Selected work

| Project | What it is | Stack |
|---|---|---|
| [**Kamo**](https://github.com/domingos-engineering/kamo-showcase) | Our own multi-tenant SaaS. An AI agent answers car dealerships' WhatsApp, collects financing details and hands qualified leads to salespeople. 30,772 messages and 1,602 customers between May and August 2026. | FastAPI · Redis Streams · Supabase · Next.js |
| [**4Life Nutrition — store**](https://github.com/domingos-engineering/4life-nutrition-showcase) | Custom e-commerce for a Brazilian supplement brand. Payment, tax invoice, shipping label and customer alerts run without manual steps; recurring subscriptions on top. | Next.js · Medusa v2 · PostgreSQL |
| [**4Life — Creator Army**](https://github.com/domingos-engineering/4life-creators-showcase) | Influencer program on its own platform: application queue, per-creator coupons, product campaigns and an idempotent commission sweep. | Next.js · PostgreSQL · Medusa Admin API |
| [**Brazil–Russia Chamber of Commerce**](https://github.com/Dowgg18/camara-brasil-russia-showcase) | Institutional portal in Portuguese, Russian and English. Editors paste raw text and get a translated, SEO-ready article for review. | Next.js · Supabase |

Client code stays with the client. These repositories are case studies: screens,
architecture and the decisions behind each system, with demo data wherever a screen
would show real people.

### Engineering we open-sourced

Problems our production systems surfaced, extracted and published by our founder:

- [burstq](https://github.com/Dowgg18/debounced-webhook-pipeline): collapses bursts of chat webhooks into one ordered unit of work per conversation.
- [replaygate](https://github.com/Dowgg18/agent-replay-gate): a pre-deploy regression gate for conversational agents.
- [proven](https://github.com/Dowgg18/unhealthy-until-proven): health checks with three outcomes, not two.
- [reachable](https://github.com/Dowgg18/covered-but-unreachable): finds code your tests cover and your users cannot reach.

### Technology

Python · FastAPI · TypeScript · Next.js · React · Node.js · PostgreSQL · Redis ·
Supabase · Medusa · Docker · Traefik · GitHub Actions · Playwright · Claude and other LLM APIs

### Contact

Douglas Domingos, founder · [LinkedIn](https://www.linkedin.com/in/douglas-c-domingos/) · douglascunhadomingos@gmail.com
