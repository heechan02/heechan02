<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=1000&color=F7931A&center=true&vCenter=true&width=620&lines=Bitcoin+Protocol+Engineer;Full-Stack+Blockchain+Builder;Solidity+%2B+TypeScript+%2B+React" alt="Typing SVG" />
</h1>

<p align="center">
  <strong>Heechan Yang</strong> · BSc Computer Science & AI · Loughborough University
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
<summary><h3>🛡️ SatShield — Parametric Insurance dApp&nbsp;&nbsp;<code>ETH Oxford 2026 · Top 6</code></h3></summary>
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

<!-- PROJECT CARD: Chain Lens -->
<details>
<summary><h3>🔍 Chain Lens — Bitcoin Transaction Parser&nbsp;&nbsp;<code>Summer of Bitcoin · Challenge 1</code></h3></summary>
<br>

> Protocol-first transaction parser that reads raw Bitcoin binary and explains it in plain English.

- Raw binary parsing of Bitcoin Core `.dat` files with XOR deobfuscation
- SegWit weight/fee calculation (BIP-141), RBF signaling, timelocks (BIP-68)
- Merkle root verification from scratch
- Web visualiser that breaks down transactions for non-technical users

`TypeScript` `Node.js` `React` `Bitcoin Protocol` `BIP-141` `BIP-68`

</details>

<!-- PROJECT CARD: Coin Smith -->
<details>
<summary><h3>🪙 Coin Smith — PSBT Transaction Builder&nbsp;&nbsp;<code>Summer of Bitcoin · Challenge 2</code></h3></summary>
<br>

> Wallet-engineering-grade transaction builder handling the edge cases real wallets face.

- BIP-174 PSBT construction with Branch-and-Bound + greedy coin selection
- Iterative fee/change resolution at the dust threshold boundary (545 vs 546 sats)
- Anti-fee-sniping locktime and RBF signaling (BIP-125)
- CLI tool + interactive web UI + automated test suite

`TypeScript` `Node.js` `React` `BIP-174` `BIP-125` `Vitest`

</details>

<!-- PROJECT CARD: Sherlock -->
<details>
<summary><h3>🕵️ Sherlock — Bitcoin Chain Analysis Engine&nbsp;&nbsp;<code>Summer of Bitcoin · Challenge 3</code></h3></summary>
<br>

> 9-heuristic chain analysis engine processing 84+ real mainnet blocks per fixture.

- Common Input Ownership, change detection via multi-signal scoring
- CoinJoin & consolidation detection, address reuse tracking, peeling chain identification
- Transaction classification with deterministic priority waterfall
- Built on real Bitcoin mainnet data — not testnet simulations

`TypeScript` `Node.js` `React` `Chain Analysis Heuristics` `Vitest`

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
      <img src="https://img.shields.io/badge/Effect_TS-111827?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td><strong>🛠️ Infra & Testing</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
      <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
    </td>
  </tr>
</table>

<br>

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=heechan02&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=F7931A&icon_color=F7931A&text_color=c9d1d9" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=heechan02&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=F7931A&text_color=c9d1d9" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=heechan02&theme=github-dark-blue&hide_border=true&background=0D1117&ring=F7931A&fire=F7931A&currStreakLabel=F7931A" />
</p>

---

<p align="center">
  <em>Currently looking for blockchain / full-stack internship opportunities for Summer 2026.</em><br>
  <strong>Let's build something meaningful →</strong> <a href="mailto:heechanyang02@gmail.com">heechanyang02@gmail.com</a>
</p>
