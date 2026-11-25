# ![Reza Hajizadeh · AI Engineer](assets/profile-header.svg)

Istanbul, Türkiye · [LinkedIn](https://www.linkedin.com/in/rezahajizade) · [WordPress developer profile](https://profiles.wordpress.org/rezaplus/#content-plugins)

I build multilingual AI assistants and the backend systems they depend on. I have eight years of software engineering experience. My work spans document retrieval, API design and operating services in production.

**Product ownership.** At [BaTimo](https://batimo.ai/), I own the workflow from a customer’s first message to a confirmed booking. I define what the assistant can do, when staff take over and how the CRM and calendar stay in sync.

## Engineering skills

| Specialty | Engineering work |
| --- | --- |
| **Retrieval and evaluation** | Built retrieval-augmented generation (RAG) with Python and Qdrant. Wrote regression tests for outdated documents, irrelevant matches and accidental retrieval across customer accounts. |
| **LLM integration** | Built tool-calling workflows with OpenAI and Anthropic APIs. Designed an [MCP server](https://docs.batimo.ai/help/integrations/ai-connections) that limits each tool to the connected company and the user’s permissions. |
| **System architecture** | Designed multi-tenant services in Laravel and Node.js. Used Redis to detect duplicate WhatsApp events before sending work to RabbitMQ. Designed MySQL schemas and role-based APIs for a mentorship platform. |
| **Production engineering** | Deployed Docker services on AWS. Used Sentry for errors, Laravel Horizon for queues and Telescope to trace requests. Automated releases with GitHub Actions. |

**Languages and tools** · Python (FastAPI), PHP (Laravel, Yii2), JavaScript and TypeScript (Node.js), Go, PostgreSQL, pgvector and Ollama.

## Experience

- **GuruDesk · 2022–2026.** Progressed from senior backend development to AI engineering. Led the backend team for two years. Maintained platforms serving **300M+ requests per month in total** and built provisioning tools for over 100 servers.
- **Culter Media Hub · 2021–2022.** Built booking and editorial tools in Laravel and WordPress. Reduced backend response times by **35–55%** on key sites.
- **Parlak Market · 2018–2021.** Built a WooCommerce platform that processed **1,000–1,200 orders per month**. Cut page load time from 3.5 to 1.2 seconds.

**Education** · B.Sc. in Information Technology, Tabriz Industrial Management Institute.

## Selected public code

| Project | What to look at |
| --- | --- |
| [Studio](https://github.com/rezaplus/Studio) | Python workflows for multilingual video production. The [request router](https://github.com/rezaplus/Studio/blob/main/scripts/agent/route_request.py) maps each request to a script and identifies steps that need approval. |
| [ChatRoom](https://github.com/rezaplus/ChatRoom) | A Laravel messaging API. The [route definitions](https://github.com/rezaplus/ChatRoom/blob/main/routes/api.php) show room permissions, join approvals and rate limits. |
| [TWChat](https://github.com/rezaplus/TWChat-Two-Way-Chat-plugin-for-WordPress) · [Orders Pro](https://github.com/rezaplus/WooCommerce-Orders-pro) | Two open-source WooCommerce plugins. TWChat connects order support to WhatsApp. Orders Pro shows staff which items to pack. |
| [CommentRating](https://github.com/rezaplus/CommentRating) | A Laravel package and [companion WordPress plugin](https://github.com/rezaplus/Comment-Rating-wordpress-plugin) for collecting comments and calculating average ratings. |
