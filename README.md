<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=620&lines=Software+Engineer;Full-Stack+%C2%B7+Mobile+%C2%B7+Systems;TypeScript+%C2%B7+Python+%C2%B7+Java+%C2%B7+C%2B%2B" alt="Typing SVG" />
</h1>

<p align="center">
  <strong>Heechan Yang</strong>
</p>
<p align="center">
  BSc Computer Science & AI @ Loughborough University · 2024 – 2027
</p>

<p align="center">
  <a href="https://linkedin.com/in/heechan02"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:heechanyang02@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>

---

I'm a final-year Computer Science & AI student (First Class average) and the sole engineer at **BALLR**, where I lead a sports social app end to end — Postgres schema design, Stripe payments live in two countries, and App Store / Google Play releases — for 2,000+ users. I like owning a system from the database to the pixel, shipping under pressure (four hackathons in 2026: one win, one top-6 finish), and I bias towards depth over breadth.

<br>

## 🏆 Highlights

<table>
  <tr>
    <td align="center" width="50%">
      <h3>💼 BALLR Ltd</h3>
      <strong>Lead Software Engineer — sole engineer</strong><br>
      2,000+ users · 1,500+ bookings · Stripe live in 2 countries<br>
      <a href="https://apps.apple.com/gb/app/ballr-club/id6762270628">App Store</a> · <a href="https://play.google.com/store/apps/details?id=com.ballrapp.app">Google Play</a>
    </td>
    <td align="center" width="50%">
      <h3>🥇 Microsoft Embrace × Midlands Hackathon 2026</h3>
      <strong>Winner</strong><br>
      Lighthouse — AI career advisor, shipped end to end in 5 hours
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <h3>🏅 ETH Oxford 2026</h3>
      <strong>Top 6 Finalist — Final Stage Pitch</strong><br>
      350+ hackers → 6 teams on stage
    </td>
    <td align="center" width="50%">
      <h3>⛓️ Summer of Bitcoin 2026</h3>
      <strong>All 3 Challenges Completed</strong><br>
      Low-level systems work: binary parsing, transaction construction, chain analysis
    </td>
  </tr>
</table>

<br>

## 💼 Experience

**Lead Software Engineer · BALLR Ltd** — Remote · Aug 2026 – Present
- Lead end-to-end development of a sports social app pairing footballers with similar-level training partners and coaches, driving growth to 2,000+ users across international markets
- Own the full stack as sole engineer: Supabase (Postgres) schema design, Stripe payments live in 2 countries, and App Store / Google Play releases via Expo EAS
- Shipped sessions, coach bookings, friend connections and location-based push alerts, driving 1,500+ bookings

<a href="https://apps.apple.com/gb/app/ballr-club/id6762270628"><img src="https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=appstore&logoColor=white" /></a>
<a href="https://play.google.com/store/apps/details?id=com.ballrapp.app"><img src="https://img.shields.io/badge/Google_Play-414141?style=flat-square&logo=googleplay&logoColor=white" /></a>

**Full-Stack Developer Intern · Neuro Notion (Startup)** — Remote · Apr 2025 – Aug 2025
- Owned end-to-end delivery of Stripe payments for a product with 500+ users: REST API integration and Node.js webhooks keeping the React frontend and PostgreSQL consistent under asynchronous transactions

*Also: Social Secretary of the Loughborough Computer Science Society — ran 15 events for 200 students; the society won Loughborough Academic Award 2026: Department of the Year.*

<br>

## ⚡ Featured Builds

<!-- PROJECT CARD: Lighthouse -->
<details open>
<summary><h3>🔦 <a href="https://github.com/heechan02/lighthouse">Lighthouse — AI Career Advisor for Students</a>&nbsp;&nbsp;<code>Microsoft Embrace × Midlands Hackathon 2026 · Winner</code></h3></summary>
<br>

> An AI career advisor that interviews students conversationally, builds a skills/interests profile, and turns it into personalised career paths, skill-gap analyses and course/summer-work recommendations.

**The Problem:** Most students don't think about career development until the last months of their course — and by then they've never engaged with the university's careers service.

**What I Built:**
- Conversational agent flow that builds a complete student profile from chat, then surfaces tailored career pathways and skill-gap analyses
- Actionable guidance mapped to the target role: optional modules, online courses and summer work
- Shipped end to end in 5 hours: live Vite + React SPA (Tailwind CSS, shadcn/ui, Framer Motion) on Vercel with a Python backend for AI inference

🔗 [Live demo](https://lighthouse-iota-indol.vercel.app)

`TypeScript` `React (Vite)` `Tailwind CSS` `shadcn/ui` `Framer Motion` `Python`

</details>

<!-- PROJECT CARD: NannyCam -->
<details>
<summary><h3>📷 <a href="https://github.com/heechan02/hackprinceton-2026">NannyCam — AI-Powered Eldercare Monitoring</a>&nbsp;&nbsp;<code>HackPrinceton 2026</code></h3></summary>
<br>

> Lets adult children remotely look after elderly parents: camera snapshots are analysed by Gemini vision for medication and activity events, and anomalies reach caregivers over iMessage — no app install required on the parent's side.

**What I Built:**
- Real-time snapshot pipeline on Supabase Realtime + Storage: periodic camera frames analysed by the Gemini vision API for activity and medication-adherence detection
- Knot API integration for agentic transaction monitoring with configurable spending rules that flag unusual purchases across linked accounts
- iMessage agent worker (Spectrum/Photon) running as a separate Node.js process alongside the Next.js app · Vitest test suite

🔗 [Live demo](https://hackprinceton-2026.vercel.app) · [YouTube demo](https://www.youtube.com/watch?v=Q93FDD8e_7c)

`Next.js 16` `TypeScript` `Tailwind CSS` `Supabase (Postgres + Realtime)` `Gemini API` `Knot API` `Vitest`

</details>

<!-- PROJECT CARD: SatShield -->
<details>
<summary><h3>🛡️ <a href="https://github.com/heechan02/SatShield-ETH-Oxford">SatShield — Parametric Disaster-Insurance dApp</a>&nbsp;&nbsp;<code>ETH Oxford 2026 · Top 6 Finalist</code></h3></summary>
<br>

> Automated disaster-relief insurance: when independently verified real-world data crosses a threshold, policyholders are paid — no claims process, no intermediaries.

**The Problem:** Underinsured communities wait weeks for disaster relief payouts, if they receive them at all.

**What I Built:**
- Full-stack platform on Flare Network integrating all four enshrined protocols — live price feeds (FTSO v2), Web2 data attestation (FDC), synthetic-XRP bridge (FAssets) and cross-chain XRP premiums
- 2-of-3 multi-source consensus (USGS, Open-Meteo, GeoNet) verified on-chain via Merkle proofs; tiered Solidity contract pays 25 / 50 / 100% by event severity
- Typed, testable architecture: 15 I/O effects modelled as composable Effect TS services with typed errors — 20 automated tests across 7 services with deterministic mocks

🔗 [Live demo](https://sat-shield-eth-oxford.vercel.app)

`TypeScript` `Effect TS` `Solidity` `React` `Ethers.js v6` `Supabase` `Three.js` `Vitest`

</details>

<!-- PROJECT CARD: Summer of Bitcoin -->
<details>
<summary><h3>⛓️ <a href="https://github.com/heechan02/summer-of-bitcoin-2026">Summer of Bitcoin 2026 — Protocol Engineering Challenges</a>&nbsp;&nbsp;<code>All 3 Completed</code></h3></summary>
<br>

> Three progressively deeper systems challenges — raw binary parsing, transaction construction and heuristic chain analysis — each shipped as a CLI tool, an interactive web UI and an automated test suite.

- **Chain Lens — transaction parser:** raw binary parsing of Bitcoin Core `.dat` files (XOR deobfuscation), SegWit weight/fee calculation (BIP-141), RBF signalling, timelocks (BIP-68), Merkle root verification; web visualiser that explains transactions in plain English
- **Coin Smith — PSBT builder (BIP-174):** Branch-and-Bound + greedy coin selection, iterative fee/change resolution at the dust-threshold boundary (545 vs 546 sats), anti-fee-sniping locktime, RBF signalling (BIP-125)
- **Sherlock — chain-analysis engine:** 9 heuristics over 84+ real mainnet blocks per fixture — common-input ownership, change detection, CoinJoin/consolidation detection, peeling chains — with a deterministic priority-waterfall classifier

`TypeScript` `Node.js` `React` `Binary Parsing` `Algorithms` `Bitcoin Protocol` `Vitest`

</details>

<br>

## 🗂️ Other Projects

| Project | What it is | Tech |
| --- | --- | --- |
| [**SaveAI**](https://github.com/heechan02/saveai) · *Unicorn Mafia Hackathon 2026* | "MyFitnessPal for AI tokens" — real-time dollar / water / CO₂ cost per LLM query, pre-flight cost-cliff detection, and pgvector semantic caching to cut redundant API calls · [Live](https://saveai.onrender.com) | Next.js 14 · TypeScript · Drizzle ORM · PostgreSQL · pgvector · Pydantic AI Gateway |
| [**PHEM**](https://github.com/heechan02/Performance-Hall-Event-Management-System) · *OOP coursework* | Java desktop app for venue event management — admin and customer roles, shopping basket, mock PayPal/card payment gateway; SOLID principles, Strategy pattern, full JUnit suite | Java · Swing · MigLayout · JUnit |
| [**Arduino Payroll**](https://github.com/heechan02/Payroll-Management-System-Arduino) · *Embedded coursework* | Payroll firmware with a 5-state FSM, serial CRUD interface with strict input validation, and an RGB LCD dashboard — all within tight SRAM constraints | C/C++ · Arduino · FSM · Adafruit LCD Shield |

<br>

## 🧰 Tech Stack

<table>
  <tr>
    <td><strong>💻 Languages</strong></td>
    <td>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
      <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
      <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
      <img src="https://img.shields.io/badge/SQL-336791?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td><strong>🖥️ Frontend & Mobile</strong></td>
    <td>
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
      <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
      <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" />
      <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>⚙️ Backend & Data</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
      <img src="https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black" />
      <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square" />
      <img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white" />
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>⛓️ Blockchain</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white" />
      <img src="https://img.shields.io/badge/Ethers.js-2535A0?style=flat-square&logo=ethereum&logoColor=white" />
      <img src="https://img.shields.io/badge/Bitcoin_Protocol-F7931A?style=flat-square&logo=bitcoin&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>🧪 Testing & Tools</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" />
      <img src="https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
      <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white" />
      <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square" />
      <img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" />
    </td>
  </tr>
</table>

<br>

## 📊 GitHub Stats

<!-- <p align="center">
  <img src="https://github-readme-stats-psi-gray-67.vercel.app/api?username=heechan02&show_icons=true&count_private=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58A6FF&icon_color=58A6FF&text_color=c9d1d9" height="165" />
</p> -->

<p align="center">
  <img src="https://github-readme-stats-psi-gray-67.vercel.app/api/top-langs/?username=heechan02&layout=compact&count_private=true&langs_count=8&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=c9d1d9" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=heechan02&theme=github-dark-blue&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" />
</p>

---

<p align="center">
  <em>Open to software engineering internships and 2027 graduate roles.</em><br>
  <strong>Let's build something meaningful →</strong> <a href="mailto:heechanyang02@gmail.com">heechanyang02@gmail.com</a>
</p>
