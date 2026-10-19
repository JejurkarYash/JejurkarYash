### About me

* 🛠️ Systems & Backend Engineer primarily focusing on **Go**, **TypeScript**, and **Distributed Systems**. I specialize in building low-latency APIs, rate limiters, reverse proxies, and concurrent worker pipelines.
* ⚡ Freelance Software Engineer building production backend infrastructure, PostgreSQL schemas, and real-time tracking engines for digital agencies.
* 🚀 Built **Setu**, a high-throughput Go LLM proxy benchmarked at **5,170 req/s** with a **2.88ms p95 latency** under peak load.
* 🏆 Hackathon builder — created **LogFix** (automated Render-to-Slack log debugging) at 2Fast2MCP '26'.

---

### Products & Systems (Open Source)

* **[Setu](https://github.com/Jejurkar-Yash/Setu)** — A high-performance Golang LLM Proxy Gateway built with Go, Redis, and PostgreSQL.
  * Benchmarked across 1.55M+ requests (sustaining 5,170 req/s peak load at 2.88ms p95 latency) with 0% failure rate.
  * Built an async telemetry pipeline using goroutine worker pools to prevent blocking heavy SSE streams.
  * Uses atomic Redis Lua scripts for instant budget tracking and AES-256-GCM for credential security.

* **[Throttlr](https://throttlr.yashjejurkar.me/)** — Distributed Rate Limiting SDK and Infrastructure Platform.
  * Published `@throttlr/sdk` on npm for zero-dependency single-line backend middleware integration.
  * Implemented Fixed & Sliding Window algorithms via atomic Redis Lua scripts to eliminate race conditions under high concurrency.
  * Built normalized PostgreSQL schemas with indexed analytics queries[cite: 2].

* **[LynxDraw](https://lynx-draw-frontend.onrender.com/)** — Real-time collaborative engine built on WebSockets & Redis Pub/Sub.
  * Load-tested with 100 concurrent WebSocket connections maintaining a 110ms p95 synchronization response time.
  * Synchronized distributed client states across server nodes using Redis Pub/Sub messaging.
  * Structured as a Turborepo monorepo with shared TypeScript contracts.

* **[LogFix](https://github.com/JejurkarYash/ai-sre-agent)** — Automated log analyzer built for 2Fast2MCP 2026 that intercepts Render service logs and pushes automated bug fixes directly to Slack.

---

### Technical Stack

* **Languages:** Go (Golang), TypeScript, JavaScript, SQL, Python.
* **Backend & Systems:** Concurrency (Goroutines/Channels), REST, WebSockets, SSE, Reverse Proxies, Rate Limiting, Microservices
* **Databases & Caching:** PostgreSQL, Redis (Lua Scripts & Pub/Sub), MongoDB, sqlc, Goose, Prisma
* **Tools & Infrastructure:** Docker, Linux, Turborepo, Git, Postman, Vercel, Render

---

📫 **Get in touch:** `yashjejurkar.dev@gmail.com` | [Twitter/X](https://x.com/YashJejurkar) | [LinkedIn](https://linkedin.com/in/yash-jejurkar)
