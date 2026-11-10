### Hi 👋 I'm **Shahbaz Hasan Raja**

Backend & applied AI engineer (4+ years, Bengaluru). I build AI agents, MCP servers
and the multi-tenant backends they run on, currently at [Drivetrain.ai](https://drivetrain.ai);
previously [WeWork India](https://wework.co.in) and [LetsTransport](https://letstransport.com).

🌐 **[shahbazhraja.com](https://shahbazhraja.com/)**: my portfolio, with an AI agent you can question about my work

---

## Recent work at Drivetrain.ai

- **Heimdall**: MCP gateway that lets anyone at the company ask Claude about customer calls, support conversations and product data. Used by nearly half the company, 100K+ tool calls
- **Support Bot**: the classifier behind every customer Slack/Teams channel (TypeSafe's Jev first, Claude for hard cases), one ticket intake for all channels, decisions reviewed into an eval set
- **Drive AI**: data access and user memory for Drivetrain's AI assistant. A read-only BigQuery endpoint where the assistant runs SQL it writes itself (no-write account, single-SELECT validator, cost and row caps), plus saved user preferences applied in every chat, hardened against prompt injection
- **Stringer**: call intelligence across 8K+ sales and customer calls; Claude reaches it through Heimdall
- **MCP OAuth**: designed the sign-in for Drivetrain's customer-facing MCP server (OAuth 2.0, PKCE, Dynamic Client Registration)
- **RBAC audit logging**: across 500+ companies, with search, CSV export and a read-only auditor role

## Side projects ([details](https://shahbazhraja.com/#projects))

- 🤖 **[Ask about Shahbaz](https://shahbazhraja.com/projects/ask-about-shahbaz)**: agentic RAG over my portfolio. A PydanticAI agent with filesystem tools, hybrid search (pgvector + full-text, RRF), and a free-LLM fallback chain (Groq → Cloudflare Workers AI → Gemini)
- 🏗️ **[Personal Developer Platform](https://shahbazhraja.com/projects/personal-platform)**: NestJS + FastAPI services, an MCP server for Claude, self-hosted on Coolify over Tailscale + Cloudflare Tunnel, end-to-end request tracing
- 🎬 **[YouTube.ai](https://shahbazhraja.com/projects/youtube-ai)**: video-intelligence backend (distributed Whisper, map-reduce summarization, HLS, Kafka outbox)

## 🧰 Stack

**Languages:** Python • Java • TypeScript • C++
**Backend:** FastAPI • Spring Boot • NestJS • Node.js
**AI:** Claude API • Claude Agent SDK • MCP • PydanticAI • RAG • LLM evals • LangChain
**Data:** PostgreSQL (pgvector) • ClickHouse • Redis • MongoDB • OpenSearch
**Infra & eventing:** AWS • GCP • Docker • Kafka • BullMQ • SQS • Airflow

---

## 🌐 Reach me

- 🌍 [shahbazhraja.com](https://shahbazhraja.com) · 💼 [LinkedIn](https://linkedin.com/in/shahbazhraja) · ✉️ [shahbazhraja.work@gmail.com](mailto:shahbazhraja.work@gmail.com)
- 📝 [Medium](https://medium.com/@deathblade1104) · 🧮 [LeetCode](https://leetcode.com/u/deathblade1104/) (Knight, 2000+, top 2.5%) · 🟢 [GeeksforGeeks](https://www.geeksforgeeks.org/profile/shahbaz1104) (#1 in university)

![](https://github-readme-stats.vercel.app/api/top-langs/?username=deathblade1104&theme=dark&hide_border=true&layout=compact)
