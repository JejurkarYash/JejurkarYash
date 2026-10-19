### About me

* 🛠️ Systems & Backend Engineer primarily focusing on **Go**, **TypeScript**, and **Distributed Systems**. I specialize in building low-latency APIs, rate limiters, reverse proxies, and concurrent worker pipelines.
* ⚡ Freelance Software Engineer building production backend infrastructure, PostgreSQL schemas, and real-time tracking engines for digital agencies.
* 🚀 Built **Setu**, a high-throughput Go LLM proxy benchmarked at **5,170 req/s** with a **2.88ms p95 latency** under peak load.
* 🏆 Hackathon builder — created **LogFix** (automated Render-to-Slack log debugging) at 2Fast2MCP '26[cite: 2].

---

### Products & Systems (Open Source)

* **[Setu](https://github.com/Jejurkar-Yash/Setu)** — A high-performance Golang LLM Proxy Gateway built with Go, Redis, and PostgreSQL[cite: 2].
  * Benchmarked across 1.55M+ requests (sustaining 5,170 req/s peak load at 2.88ms p95 latency) with 0% failure rate[cite: 2].
  * Built an async telemetry pipeline using goroutine worker pools to prevent blocking heavy SSE streams[cite: 2].
  * Uses atomic Redis Lua scripts for instant budget tracking and AES-256-GCM for credential security[cite: 2].

* **[Throttlr](https://throttlr.yashjejurkar.me/)** — Distributed Rate Limiting SDK and Infrastructure Platform[cite: 2].
  * Published `@throttlr/sdk` on npm for zero-dependency single-line backend middleware integration[cite: 2].
  * Implemented Fixed & Sliding Window algorithms via atomic Redis Lua scripts to eliminate race conditions under high concurrency[cite: 2].
  * Built normalized PostgreSQL schemas with indexed analytics queries[cite: 2].

* **[LynxDraw](https://lynx-draw-frontend.onrender.com/)** — Real-time collaborative engine built on WebSockets & Redis Pub/Sub[cite: 2].
  * Load-tested with 100 concurrent WebSocket connections maintaining a 110ms p95 synchronization response time[cite: 2].
  * Synchronized distributed client states across server nodes using Redis Pub/Sub messaging[cite: 2].
  * Structured as a Turborepo monorepo with shared TypeScript contracts[cite: 2].

* **[LogFix](https://github.com/JejurkarYash/ai-sre-agent)** — Automated log analyzer built for 2Fast2MCP 2026 that intercepts Render service logs and pushes automated bug fixes directly to Slack[cite: 2].

---

### Technical Stack

* **Languages:** Go (Golang), TypeScript, JavaScript, SQL, Python[cite: 2]
* **Backend & Systems:** Concurrency (Goroutines/Channels), REST, WebSockets, SSE, Reverse Proxies, Rate Limiting, Microservices[cite: 2]
* **Databases & Caching:** PostgreSQL, Redis (Lua Scripts & Pub/Sub), MongoDB, sqlc, Goose, Prisma[cite: 2]
* **Tools & Infrastructure:** Docker, Linux, Turborepo, Git, Postman, Vercel, Render[cite: 2]

---

📫 **Get in touch:** `yashjejurkar.dev@gmail.com` | [Twitter/X](https://x.com/YashJejurkar) | [LinkedIn](https://linkedin.com/in/yash-jejurkar)[cite: 2]
