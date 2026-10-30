# Kushal Sapkota

**AI-native automation engineer · Python/Django developer**

<a href="https://kushal.aafaiai.com"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=C6F432&vCenter=true&width=640&lines=I+build+backends+that+think+and+automate.;AI-Native+Automation+Engineer;Django+Backend+Developer;n8n+%C2%B7+LLM+Agents+%C2%B7+PostgreSQL" alt="Animated tagline: I build backends that think and automate. AI-native automation engineer, Django backend developer, n8n, LLM agents, PostgreSQL" /></a>

I build backend applications, AI agents and automation workflows that solve practical business problems. Based in Panauti, Nepal; BICT student at Virinchi College; independent developer under the Aafai AI name.

[Portfolio](https://kushal.aafaiai.com) · [Case studies](https://kushal.aafaiai.com/#case) · [kushalsapkota577@gmail.com](mailto:kushalsapkota577@gmail.com)

---

## What I build

| | |
|---|---|
| **Backend engineering** | Python, Django, REST APIs, PostgreSQL, data modelling, validation and business rules |
| **AI systems** | LLM integrations, tool calling, structured output, and guardrails written as code |
| **Workflow automation** | n8n, webhooks, WhatsApp and Telegram integrations, API orchestration |
| **Business software** | Billing and ledgers, admin panels, customer-facing websites |

## Selected work

| Project | Problem | What I engineered | Status |
|---|---|---|---|
| **Karki'z Cakes AI agent** <br>[case study](https://kushal.aafaiai.com/#case) | A cake shop takes orders in Nepali, Roman Nepali and English, with voice notes and photos. | An n8n agent (98 nodes across 5 workflows, WhatsApp and web chat). The model calls SQL tools and proposes; code validates, prices and saves. It cannot mark an order paid. <br>`n8n` `PostgreSQL` `OpenRouter` `360dialog` `Docker` | In production for a client. Source is private (client system). |
| **[KusBill](https://github.com/kushal867/billing)** | Small shops keep accounts on a paper billpad. | A ledger where balances are derived from history in SQL (never stored), with BS/AD dates, a per-business advisory lock for concurrent writes, and PDF/Excel/CSV export. 148 automated tests. <br>`Next.js` `TypeScript` `Prisma` `PostgreSQL` | In production |
| **[Affaiai](https://www.aafaiai.com)** <br>founder | Small businesses answer the same WhatsApp questions all day, and a bot that invents prices is worse than none. | A multi-tenant platform (Django, DRF, Celery, Redis, PostgreSQL, React, TypeScript) where replies are grounded in the business's own FAQ and products. Uncertain questions are handed to a person. It has tenant isolation, encrypted credentials, an automation editor, and an MCP server so AI assistants can manage a workspace. <br>`Django` `Celery` `PostgreSQL` `React` `Docker` | In development (early). Source is private. |
| **[Nexus AI](https://github.com/kushal867/chatbot)** | Triggering n8n workflows from a chat interface. | A React chat front end for n8n webhooks, with voice and attachments. <br>`React` `Vite` `n8n` | Live demo |
| **[College Finder](https://github.com/kushal867/collge--finder-backend)** | Comparing colleges is slow. | A Django REST backend with AI-assisted comparison using a local Llama model. <br>`Django` `DRF` `Ollama` | Prototype |

More, honestly labelled by status: [kushal.aafaiai.com/#work](https://kushal.aafaiai.com/#work). Live client websites I have built are listed under [Client work](https://kushal.aafaiai.com/#clients).

## Stack

- **Languages:** Python, JavaScript, TypeScript
- **Backend and data:** Django, Django REST Framework, Next.js, Prisma, PostgreSQL, SQLite
- **Automation and AI:** n8n, webhooks, OpenRouter, Ollama, LangChain, tool calling, structured output
- **Frontend:** React, Vite, Tailwind CSS
- **Tooling:** Git, GitHub, Docker, Vitest

## GitHub activity

<!--START_SECTION:stats-->
<p>
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=kushal867&show_icons=true&theme=dark&hide_border=true&bg_color=05060A&title_color=C6F432&icon_color=7C5CFF&text_color=F4F6FB&count_private=true" alt="Kushal's GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kushal867&layout=compact&theme=dark&hide_border=true&bg_color=05060A&title_color=C6F432&text_color=F4F6FB" alt="Most used languages" />
</p>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=kushal867&theme=dark&hide_border=true&background=05060A&ring=C6F432&fire=7C5CFF&currStreakLabel=2DD4FF" alt="Contribution streak" />
<!--END_SECTION:stats-->

## How I engineer software

1. Understand the business problem before writing code.
2. Design a system the owner can maintain.
3. Put business rules in code, not in prompts.
4. Integrate external services defensively.
5. Test the behaviour that matters (KusBill's suite runs against a real PostgreSQL database).
6. Ship early, then improve from real use.

## Work with me

Founder of [Affaiai](https://www.aafaiai.com). Open to junior backend and AI-automation roles, and to freelance work: AI automation, Django backends, business software and API integrations.
Email **kushalsapkota577@gmail.com** or start from the [portfolio](https://kushal.aafaiai.com).
