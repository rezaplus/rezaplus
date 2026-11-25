# ![Reza Hajizadeh · AI Engineer](https://raw.githubusercontent.com/rezaplus/rezaplus/fb6e36c47debe851f34fc1c36cad0ebe31e127f8/assets/profile-header.svg)

I have 8+ years in software engineering. I build AI systems that answer from a company’s own documents and act through its APIs. At GuruDesk, I led a backend team for two years and took the **Paycell** and **Forex.com.tr** integrations from architecture through production support.

[LinkedIn](https://www.linkedin.com/in/rezahajizade) · [BaTimo](https://batimo.ai/) · [AI integration docs](https://docs.batimo.ai/help/integrations/ai-connections)

## AI engineering

I spent two years developing **BaTimo**, a multilingual assistant for WhatsApp, Instagram and web chat. I owned the inquiry-to-booking workflow from requirements to release. I built both the assistant’s CRM and booking tools and the dashboards staff use to review its work.

- **Retrieval and evaluation.** I built a retrieval-augmented generation (RAG) service with Qdrant. Each search runs against one company’s documents. My regression tests cover outdated policies, passages from another tenant and irrelevant matches that score highly in vector search.
- **Tool use and permissions.** I built an MCP server that lets ChatGPT and Claude work with leads, bookings and customer follow-ups. Each action checks the connected company and the user’s permissions. [Tool reference](https://docs.batimo.ai/help/ai-connections/mcp-tools-reference)
- **Human review.** I combined keyword rules with a classifier that handles ambiguous messages. Staff can see which check flagged a message and decide how to respond. [Message Guard](https://docs.batimo.ai/help/conversations/message-guard)
- **Event-driven architecture.** I connected the messaging channels to Laravel and Node.js services. Redis detects duplicate WhatsApp events before workers receive them through RabbitMQ.

## Engineering experience

**GuruDesk · 2022–2026**  
Alongside the client integrations, I maintained production services for **İntegral Yatırım**. I added retrieval and tool calling to backend workflows using OpenAI and Anthropic APIs. I also built the hosting sales platform and automated provisioning and monitoring for **100+ servers**.

**IFPE Academy · AI agents for internal operations**  
I worked with academy staff to identify manual tasks, then deployed agents they now use in their daily work. The academy recognized this work with its 2026 AI Innovation & Digital Transformation certificate.

**E-Mentorship · Erasmus+**  
I led backend architecture and database design for a platform that pairs preschool teachers with experienced mentors. The portal handles matching, training and progress reviews. [Project partner report](https://www.ilabour.eu/news/e-mentorship-recognised-as-an-erasmus-good-practice/)

**Core stack** · Python, FastAPI, Qdrant, pgvector, TypeScript, Node.js, PHP, Laravel, PostgreSQL, Redis, RabbitMQ, Docker and AWS.
