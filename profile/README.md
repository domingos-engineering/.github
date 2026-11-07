<p align="center">
  <img src="https://raw.githubusercontent.com/domingos-engineering/.github/main/profile/assets/banner.png" alt="Domingos — Software Engineering & Intelligent Systems" width="100%" />
</p>

We design, build and run custom systems for companies that have outgrown off-the-shelf
tools: stores that handle the whole order on their own, partner programs where a wrong
number means wrong money in someone's pocket, multilingual institutional portals, and AI
agents that talk to customers in production.

<p align="center">
  <img src="https://raw.githubusercontent.com/domingos-engineering/.github/main/profile/assets/numbers.png" alt="30,772 WhatsApp messages handled by Kamo, May–Aug 2026 · 86 architecture decision records on a single client codebase · 3 languages in one editorial pipeline (PT, RU, EN) · 4 open-source libraries extracted from our production systems" width="100%" />
</p>

<br/>

### What we do

<p align="center">
  <img src="https://raw.githubusercontent.com/domingos-engineering/.github/main/profile/assets/capabilities.png" alt="Custom software · Enterprise systems · AI and automation · Systems integration · SaaS development · Software architecture" width="100%" />
</p>

<br/>

### Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/domingos-engineering/kamo-showcase"><img src="https://raw.githubusercontent.com/domingos-engineering/.github/main/profile/assets/case-kamo.png" alt="Kamo — our own SaaS: an AI agent that answers car dealerships' WhatsApp" width="100%" /></a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/domingos-engineering/4life-nutrition-showcase"><img src="https://raw.githubusercontent.com/domingos-engineering/.github/main/profile/assets/case-4life-store.png" alt="4Life Nutrition — custom e-commerce from checkout to tax invoice and shipping label" width="100%" /></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/domingos-engineering/4life-creators-showcase"><img src="https://raw.githubusercontent.com/domingos-engineering/.github/main/profile/assets/case-creator-army.png" alt="4Life Creator Army — influencer platform with coupons, campaigns and commissions" width="100%" /></a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Dowgg18/camara-brasil-russia-showcase"><img src="https://raw.githubusercontent.com/domingos-engineering/.github/main/profile/assets/case-camara.png" alt="Brazil–Russia Chamber — institutional portal in Portuguese, Russian and English" width="100%" /></a>
    </td>
  </tr>
</table>

<sub>Client code stays with the client. Each case study shows screens, architecture and
the decisions behind the system, uses demo data wherever a screen would show real people,
and says plainly what is in production, what is ready for release and what is still being
built.</sub>

<br/>

### How we work

- **Specs before code.** Every feature starts as a written spec, and every decision that shapes the system is recorded with its reasons, so the next engineer, or the client, can see why.
- **The machine decides money, a person decides doubt.** Payments only count when the gateway confirms them; anything suspicious waits for a human instead of being silently blocked or approved.
- **Built to recover.** Jobs are idempotent and re-runnable, integrations fail loudly, and a stuck order can be resumed instead of rebuilt by hand.
- **Reviewed before it ships.** Releases go through CI, adversarial review and, where the stakes are high, penetration testing in production.
- **AI with guardrails.** Models handle language; deterministic code handles rules, prices and money, and replay tests catch it when that line is crossed.

<br/>

### Open source, extracted from production

| | |
|---|---|
| [**burstq**](https://github.com/Dowgg18/debounced-webhook-pipeline) | Collapses a burst of chat webhooks into one ordered unit of work per conversation, and survives a crash in the middle of it. |
| [**replaygate**](https://github.com/Dowgg18/agent-replay-gate) | A pre-deploy regression gate for conversational agents: replay conversations with every I/O boundary sealed. |
| [**proven**](https://github.com/Dowgg18/unhealthy-until-proven) | A health check has three outcomes, not two: measured, stale and unknown. |
| [**reachable**](https://github.com/Dowgg18/covered-but-unreachable) | Finds code your tests execute and your users can never reach. |

<br/>

### Technology

**Backend** Python · FastAPI · Node.js · TypeScript · PostgreSQL · Redis Streams · Supabase · Medusa  
**Frontend** Next.js · React · Tailwind CSS  
**AI** Claude and other LLM APIs · agent evaluation and replay testing  
**Operations** Docker · Traefik · GitHub Actions · Playwright

<br/>

### Work with us

We take on a small number of projects at a time, from a first architecture review to
building and running the whole system.

**Douglas Domingos**, founder · [LinkedIn](https://www.linkedin.com/in/douglas-c-domingos/) · [douglascunhadomingos@gmail.com](mailto:douglascunhadomingos@gmail.com)
