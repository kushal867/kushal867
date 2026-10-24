# Kushal Sapkota

**AI-native automation engineer · Python/Django developer**

*I build backends that think and automate.*

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
| **[Nexus AI](https://github.com/kushal867/chatbot)** | Triggering n8n workflows from a chat interface. | A React chat front end for n8n webhooks, with voice and attachments. <br>`React` `Vite` `n8n` | Live demo |
| **[College Finder](https://github.com/kushal867/collge--finder-backend)** | Comparing colleges is slow. | A Django REST backend with AI-assisted comparison using a local Llama model. <br>`Django` `DRF` `Ollama` | Prototype |

More, honestly labelled by status: [kushal.aafaiai.com/#work](https://kushal.aafaiai.com/#work). Live client websites I have built are listed under [Client work](https://kushal.aafaiai.com/#clients).

## Stack

- **Languages:** Python, JavaScript, TypeScript
- **Backend and data:** Django, Django REST Framework, Next.js, Prisma, PostgreSQL, SQLite
- **Automation and AI:** n8n, webhooks, OpenRouter, Ollama, LangChain, tool calling, structured output
- **Frontend:** React, Vite, Tailwind CSS
- **Tooling:** Git, GitHub, Docker, Vitest

## How I engineer software

1. Understand the business problem before writing code.
2. Design a system the owner can maintain.
3. Put business rules in code, not in prompts.
4. Integrate external services defensively.
5. Test the behaviour that matters (KusBill's suite runs against a real PostgreSQL database).
6. Ship early, then improve from real use.

## Work with me

Open to junior backend and AI-automation roles, and to freelance work: AI automation, Django backends, business software and API integrations.
Email **kushalsapkota577@gmail.com** or start from the [portfolio](https://kushal.aafaiai.com).
