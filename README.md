# Suksham Sharma

**Founding Engineer · Full-Stack & Backend**

Backend-focused full-stack engineer building distributed systems — queues, real-time, and orchestration — from API to infrastructure.

**Stack:** TypeScript · Node · Rust · PostgreSQL · Redis · AWS · Kubernetes

📍 Delhi, India &nbsp;·&nbsp; 📫 sukshamever@gmail.com

---

### Currently building

**raven-meetbot**  
A meeting-bot recording & transcription platform. An API enqueues "send a bot to this meeting" jobs; an orchestrator spins up isolated Playwright bot containers on demand — via the Docker socket, with capped concurrency — records the call, transcribes it with Deepgram, and streams the output to Cloudflare R2.  
`Express · BullMQ · Redis · dockerode · Playwright · Deepgram · R2`

**crashpad**  
Frontend error monitoring with a time-travel replay player as the wedge. On an error, the SDK flushes the last 30 seconds of the session — DOM, clicks, network, console — alongside the stack trace; the dashboard scrubs the replay and the trace together.  
`Bun · Elysia · Next 15 · Drizzle · Postgres · Redis · rrweb`

---

### Projects

**[Iceberg](https://github.com/Suksham-sharma/privacy-x-perps)**  
The first confidential perpetual-futures DEX on Solana. Orders are encrypted in the browser, matched inside Arcium's MPC network, and settled on-chain via Anchor — side, size and price never go public. Built for the Solana India Fellowship.  
`Rust · Anchor · Arcium MPC · TypeScript` &nbsp;·&nbsp; [Live](https://iceberg.suksham.xyz)

**[Teleparty](https://github.com/Suksham-sharma/Teleparty)**  
Real-time collaborative video watching — WebSocket sync, HLS transcoding, CDN delivery, and a microservices backend.  
`TypeScript · WebSockets · HLS · microservices`

**[Probo V1](https://github.com/Suksham-sharma/Probo_V1)**  
Opinion-trading platform backend — Redis-backed order queues, WebSocket live updates, PostgreSQL, and S3 archival.  
`TypeScript · Redis · WebSockets · PostgreSQL · S3`

**[not-so-dumb](https://github.com/Suksham-sharma/not-so-dumb)**  
AI research & quiz platform — real-time web search, a "second brain" chat, and quiz generation from YouTube videos and articles.  
`Next.js · AI · TypeScript` &nbsp;·&nbsp; [Live](https://not-so-dumb.vercel.app)

---

More on my [repositories](https://github.com/Suksham-sharma?tab=repositories).
