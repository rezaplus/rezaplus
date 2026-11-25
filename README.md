# ![Reza Hajizadeh · AI Engineer](https://raw.githubusercontent.com/rezaplus/rezaplus/a45315c3d2da0b928b33e01a1c2761629c4eefe1/assets/profile-header.svg)

**[LinkedIn](https://www.linkedin.com/in/rezahajizade)** &nbsp;·&nbsp; **[WhatsApp](https://wa.me/905528323901)** &nbsp;·&nbsp; **[Telegram](https://t.me/rezaplus)**

I have 8+ years in software engineering. I build multilingual assistants that search company documents, use business APIs and hand decisions to staff. I’m open to AI engineering roles with international teams.

## Experience

**GuruDesk** &nbsp;·&nbsp; AI and backend engineering &nbsp;·&nbsp; 2022–2026  
I led the backend team for two years. For **Paycell** and **Forex.com.tr**, I led integration work from architecture through production support. I also maintained backend services for **İntegral Yatırım**. Within GuruDesk, I added retrieval and tool calling to existing workflows using OpenAI and Anthropic APIs. I built the hosting sales platform and automated provisioning and monitoring for **100+ servers**.

**IFPE Academy** &nbsp;·&nbsp; AI agents for internal operations  
I worked with academy staff to identify which steps in their daily work could be automated. I deployed the agents they now use. The academy recognized this work with its **2026 AI Innovation & Digital Transformation** certificate.

**E-Mentorship** &nbsp;·&nbsp; System architecture for an Erasmus+ programme  
I led backend architecture and database design for a portal that matches preschool teachers with experienced mentors. It supports training, assessments and progress reviews. [Project partner report](https://www.ilabour.eu/news/e-mentorship-recognised-as-an-erasmus-good-practice/)

## BaTimo

I spent two years developing [BaTimo](https://batimo.ai/), a conversational AI product for WhatsApp, Instagram and web chat. I owned the inquiry-to-booking workflow from requirements through release. I built the assistant’s CRM and booking tools and the dashboards staff use to review its work.

- **Retrieval quality.** I scoped Qdrant searches to each company’s documents. My regression tests check for cross-company data leaks, outdated policies and irrelevant passages with high similarity scores.
- **Tool permissions.** I built the MCP server that connects ChatGPT and Claude to leads, bookings and follow-ups. Each action checks the company and the user’s permissions. [MCP tool reference](https://docs.batimo.ai/help/ai-connections/mcp-tools-reference)
- **Human review.** I combined keyword rules with a classifier for ambiguous messages. Staff can see why a message was held and decide how to respond. [Message Guard](https://docs.batimo.ai/help/conversations/message-guard)
- **Message delivery.** I used Redis to detect duplicate WhatsApp events before queuing them in RabbitMQ. Confirmed bookings sync with Google Calendar or Outlook.

## Engineering skills

| Area | Methods and tools |
| --- | --- |
| **Retrieval and evaluation** | RAG, document chunking, embeddings, relevance filtering, regression testing, Qdrant, pgvector, Chroma |
| **LLM applications** | OpenAI and Anthropic APIs, tool calling, MCP, multilingual assistants, message classification, human handoff, local inference with Ollama |
| **System design** | Multi-tenant architecture, microservices, modular monoliths, API contracts, event-driven services, webhook deduplication |
| **Languages and services** | Python and FastAPI, TypeScript and Node.js, PHP and Laravel, Go, REST APIs, WebSockets |
| **Data and messaging** | PostgreSQL, MySQL, MongoDB, Redis, RabbitMQ |
| **Cloud and reliability** | AWS, Cloudflare, Docker, Nginx, GitHub Actions, Sentry, Laravel Horizon and Telescope, PHPUnit, Pest, Jest |
| **Product delivery** | Requirements and workflow design, React and Next.js staff dashboards, cross-functional delivery, production support |
