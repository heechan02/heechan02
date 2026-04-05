<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=1000&color=F7931A&center=true&vCenter=true&width=620&lines=Bitcoin+Protocol+Engineer;Full-Stack+Blockchain+Builder;Solidity+%2B+TypeScript+%2B+React" alt="Typing SVG" />
</h1>

<p align="center">
  <strong>Heechan Yang</strong>
</p>
<p align="center">
  BSc Computer Science & AI @ Loughborough University
</p>

<p align="center">
  <a href="https://linkedin.com/in/heechan02"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:heechanyang02@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
</p>

---

I'm a second-year CS & AI student who builds at the intersection of **Bitcoin protocol engineering** and **full-stack development**. I care about shipping real systems — from raw transaction parsers to on-chain insurance platforms — and I bias towards depth over breadth.

<br>

## 🏆 Highlights

<table>
  <tr>
    <td align="center" width="50%">
      <h3>🥇 ETH Oxford 2026</h3>
      <strong>Top 6 Finalist — Final Stage Pitch</strong><br>
      350+ hackers → 6 teams on stage
    </td>
    <td align="center" width="50%">
      <h3>₿ Summer of Bitcoin 2026</h3>
      <strong>All 3 Challenges Completed</strong><br>
      Global competitive program for Bitcoin open-source dev
    </td>
  </tr>
</table>

<br>

## ⚡ Featured Builds

<!-- PROJECT CARD: SatShield -->
<details open>
<summary><h3>🛡️ <a href="https://github.com/heechan02/Satshield-ETH-Oxford">SatShield — Parametric Insurance dApp</a>&nbsp;&nbsp;<code>ETH Oxford 2026 · Top 6</code></h3></summary>
<br>

> Automated disaster-relief insurance on Flare Network — no claims process, no intermediaries, just trustless payouts when earthquakes hit.

**The Problem:** Underinsured communities wait weeks for disaster relief payouts, if they receive them at all.

**What I Built:**
- Full-stack parametric insurance integrating all 4 Flare enshrined protocols (FTSO v2, FDC, FAssets, Cross-Chain Payment)
- 2-of-3 multi-source consensus (USGS, Open-Meteo, GeoNet) verified on-chain via Merkle proofs
- Tiered smart contract with 25 / 50 / 100% auto-payouts by event severity
- FTSO price feeds auto-refreshing every 5s · 20 automated tests across 7 Effect TS services

`TypeScript` `Solidity` `Effect TS` `React` `Ethers.js v6` `Supabase` `Three.js` `Vitest`

</details>

<!-- PROJECT CARD: Summer of Bitcoin -->
<details>
<summary><h3>₿ <a href="https://github.com/heechan02/summer-of-bitcoin-2026">Summer of Bitcoin 2026 — Protocol Engineering Challenges</a>&nbsp;&nbsp;<code>All 3 Completed</code></h3></summary>
<br>

> Three progressively deeper challenges covering core Bitcoin protocol engineering — from raw transaction parsing to wallet construction to chain analysis.

**Challenge 1 · Chain Lens (Transaction Parser)**
- Protocol-first Bitcoin transaction parser with raw binary parsing of Bitcoin Core `.dat` files (XOR deobfuscation)
- SegWit weight/fee calculation (BIP-141), RBF signaling, timelocks (BIP-68), Merkle root verification
- Web visualiser explaining transactions in plain English

**Challenge 2 · Coin Smith (PSBT Builder)**
- Wallet-engineering-grade PSBT transaction builder (BIP-174)
- Branch-and-Bound + greedy coin selection, iterative fee/change resolution at the dust threshold boundary (545 vs 546 sats)
- Anti-fee-sniping locktime and RBF signaling (BIP-125)

**Challenge 3 · Sherlock (Chain Analysis)**
- 9-heuristic chain analysis engine processing 84+ real mainnet blocks per fixture
- Common Input Ownership, change detection, CoinJoin/consolidation detection, peeling chains
- Transaction classification with deterministic priority waterfall

Each challenge includes a CLI tool, interactive web UI, and automated test suite.

`TypeScript` `Node.js` `React` `Bitcoin Protocol` `BIP-141/174/125/68` `Chain Analysis` `Vitest`

</details>

<!-- PROJECT CARD: PHEM -->
<details>
<summary><h3>🎭 <a href="https://github.com/heechan02/Performance-Hall-Event-Management-System">PHEM — Performance Hall Event Management System</a>&nbsp;&nbsp;<code>Java · OOP Coursework · 91%</code></h3></summary>
<br>

> Full-featured Java desktop application for venue event management with admin and customer interfaces, shopping basket, and mock payment gateway.

- **Admin module** with inventory oversight, smart sorting by ticket price, and stock management
- **Customer module** with event browsing, shopping basket (add/view/cancel), search by Event ID, and language filtering
- **Payment gateway** supporting PayPal (email validation) and credit card (6-digit card + 3-digit CVV), with automated receipt generation
- Automatic stock deduction on successful payment · file-based persistence · robust error handling

`Java` `Swing` `MigLayout` `OOP` `SOLID Principles` `File I/O`

</details>

<!-- PROJECT CARD: Arduino Payroll -->
<details>
<summary><h3>⚙️ <a href="https://github.com/heechan02/Payroll-Management-System-Arduino">Arduino Payroll Management System</a>&nbsp;&nbsp;<code>C/C++ · Embedded · 77%</code></h3></summary>
<br>

> Embedded payroll system on Arduino with FSM architecture, LCD dashboard, and real-time employee record management within tight memory constraints.

- **5-state Finite State Machine** (SYNC → STANDBY → READ → BUTTON → DISP) managing all system transitions
- Serial command interface for CRUD operations with strict input validation (7-digit IDs, grade ranges, salary formats)
- **Adafruit RGB LCD Shield** with colour-coded status indicators (green = pension, red = no pension, purple = system info)
- Bubble sort auto-ordering by Employee ID · dynamic SRAM monitoring · custom LCD arrow graphics

`C/C++` `Arduino` `Embedded Systems` `FSM` `Adafruit LCD Shield`

</details>

<br>

## 🧰 Tech Stack

<table>
  <tr>
    <td><strong>⛓️ Protocol Layer</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white" />
      <img src="https://img.shields.io/badge/Bitcoin_Protocol-F7931A?style=flat-square&logo=bitcoin&logoColor=white" />
      <img src="https://img.shields.io/badge/Ethers.js-2535A0?style=flat-square&logo=ethereum&logoColor=white" />
      <img src="https://img.shields.io/badge/Flare_Network-E42058?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td><strong>🖥️ Application Layer</strong></td>
    <td>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
      <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
      <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><strong>🛠️ Infra & Testing</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
      <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
      <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white" />
    </td>
  </tr>
</table>

<br>

## 📊 GitHub Stats

<!-- <p align="center">
  <img src="https://github-readme-stats-psi-gray-67.vercel.app/api?username=heechan02&show_icons=true&count_private=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=F7931A&icon_color=F7931A&text_color=c9d1d9" height="165" />
</p> -->

<p align="center">
  <img src="https://github-readme-stats-psi-gray-67.vercel.app/api/top-langs/?username=heechan02&layout=compact&count_private=true&langs_count=8&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=F7931A&text_color=c9d1d9" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=heechan02&theme=github-dark-blue&hide_border=true&background=0D1117&ring=F7931A&fire=F7931A&currStreakLabel=F7931A" />
</p>

---

<p align="center">
  <em>Open to software engineering and blockchain internship opportunities.</em><br>
  <strong>Let's build something meaningful →</strong> <a href="mailto:heechanyang02@gmail.com">heechanyang02@gmail.com</a>
</p>
