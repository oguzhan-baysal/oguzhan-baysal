# Oguzhan Baysal

**I build and run software products end to end** — contracts, backend, ops, and the boring parts that keep them alive 24/7. Solo builder, based in Adana, Türkiye.

---

## What I'm building now

### 🧱 [LaunchpadKit](https://launchpadkit.dev) — launchpad infrastructure for new EVM chains

Deployable bonding-curve launchpad software: immutable Solidity contracts, permanent liquidity lock, on-chain fee split, creator trust layer and a source-available operator console. Every claim is verifiable from chain state — runtime bytecode hashes are recomputed in the browser against a published deployment manifest.

`Solidity · Foundry · OpenZeppelin 5 · Uniswap V2 · Next.js 15 · wagmi/viem`

→ [Live demo](https://demo.launchpadkit.dev) · [Pricing](https://launchpadkit.dev/#pricing) · [On-chain manifest](https://launchpadkit.dev/deployments/base-sepolia.json) · [Terms & delivery criteria](https://launchpadkit.dev/terms/)

### 📈 Copy-trading research lab *(private)*

Multi-strategy research for copy trading, built behind sequential gates: backtest-engine determinism → out-of-sample edge → shadow observation on live data → real fills → sellable track record. Nothing touches real capital until the previous gate passes, and shadow mode is the default. The same pure functions decide in backtest and in production — no "backtest says one thing, live does another".

`Python · walk-forward validation · PostgreSQL · Docker · self-hosted 24/7`

### 🎬 Autonomous content operations *(private, running 24/7)*

Trend research → script → render at $0 per video (stock footage + neural TTS + ffmpeg) → human approval from Telegram → publish to YouTube and Instagram → hourly analytics → daily learning loop that feeds back into topic choice and timing. Also runs a football-statistics Shorts channel fed by live match data.

`TypeScript · Fastify · Prisma · Redis/BullMQ · Playwright · ffmpeg · Oracle Cloud`

### 🛡️ [Protaris: Tower Defense](https://play.google.com/store/apps/details?id=com.oguzhan.protaris) — live on Google Play

Shipped mobile game: grid-based tower defense with 18 maps, 5 upgradeable towers, wave progression, AdMob monetization and Firebase analytics — taken through the full store pipeline (AAB, content rating, data safety, app-ads.txt).

`Godot 4 · GDScript`

---

## Selected public work

| Project | What it is |
|---|---|
| **[visionbridge](https://github.com/oguzhan-baysal/visionbridge)** | Config-driven DOM manipulation — a Go service serves YAML/JSON page configs that a browser library applies at runtime, so layout and content change without redeploying the frontend. |
| **[InvoiceCaseStudy](https://github.com/oguzhan-baysal/InvoiceCaseStudy)** | Full-stack invoicing: ASP.NET Core 8 Web API (JWT, EF Core) + Angular 21 with zoneless architecture and signals. |
| **[memory-card-game-web3](https://github.com/oguzhan-baysal/memory-card-game-web3)** | Full-stack Web3 game — React, Node.js, Solidity contracts, MetaMask wallet flow. |
| **[case-study-zero](https://github.com/oguzhan-baysal/case-study-zero)** | E-commerce built on micro-frontends: Next.js host app with React and Next.js remotes via Module Federation. |
| **[vizio-team-social](https://github.com/oguzhan-baysal/vizio-team-social)** | Team-based social MVP on Next.js 14 + Supabase — [live](https://vizio-team-social.vercel.app). |
| **[kitap-dunyasi-pro](https://github.com/oguzhan-baysal/kitap-dunyasi-pro)** | Book management application — Vue 3, Composition API, Vuex, SCSS — [live](https://kitap-dunyasi-pro-xi.vercel.app). |
| **[guardpot-ssh-terminal](https://github.com/oguzhan-baysal/guardpot-ssh-terminal)** | Browser SSH terminal — React + xterm.js frontend talking to Go/Gin over WebSockets. |

---

## Toolbox

**Languages** — TypeScript · Python · Go · Solidity · C# · GDScript
**Web** — Next.js · React · Vue · Fastify · FastAPI · Express · Prisma · Tailwind
**Data** — PostgreSQL · Redis · MongoDB · Qdrant · ChromaDB
**Blockchain** — Foundry · OpenZeppelin · wagmi/viem · Uniswap V2 · SPL Token-2022
**Ops** — Docker · GitHub Actions · Cloudflare · Oracle Cloud Always Free (self-hosted, 24/7)
**AI** — LangGraph · multi-agent debate · RAG pipelines · LLM orchestration

---

## How I work

- **Ship behind gates.** Determinism tests → out-of-sample validation → shadow mode → production. No gate, no deploy.
- **Verify, don't claim.** Contract bytecode against a published manifest, payment state read from chain, metrics from the platform API — not from screenshots.
- **Near-zero ops cost.** Self-hosted on free tiers, $0 per video render, cron-and-queue infrastructure.
- **Write the offer before the customer.** Pricing, terms, refund policy and delivery criteria exist before the first sale, not after.

---

📫 **hello@launchpadkit.dev** · 🌐 **[launchpadkit.dev](https://launchpadkit.dev)** · 📍 Adana, Türkiye

<sub>Türkçe: EVM zincirleri için launchpad altyapısı, otonom içerik sistemleri ve doğrulama kapılı pazar araştırma yazılımları geliştiriyorum. İş birliği için yazabilirsiniz.</sub>
