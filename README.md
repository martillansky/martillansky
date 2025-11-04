<!-- Header SVG (Orange & Black) -->

<p align="center">
  <img src="./assets/header.svg" alt="Martín Moguillansky — Full‑Stack Web3 Engineer" width="920" height="220" />
</p>

<div align="center">

[![Contact](https://img.shields.io/badge/📧%20Contact-Get%20in%20touch-black?style=for-the-badge&labelColor=ff6a00&logo=gmail&logoColor=white)](mailto:martin.moguillansky@gmail.com)
[![Projects](https://img.shields.io/badge/🚀%20Projects-DeFi%20%7C%20AA%20%7C%20Indexers-black?style=for-the-badge&labelColor=ff6a00)](https://github.com/martillansky)
[![GitHub](https://img.shields.io/badge/💻%20GitHub-@martillansky-black?style=for-the-badge&labelColor=ff6a00&logo=github&logoColor=white)](https://github.com/martillansky)

</div>

<br/>

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=martillansky&hide=stars,issues&theme=dark&show=prs_merged&show_icons=true&hide_border=false&count_private=true&title_color=ff6a00&icon_color=ff6a00&bg_color=0b0b0b&border_color=ff6a00&include_all_commits=true&rank_icon=github)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=martillansky&theme=dark&show_icons=true&hide_border=false&layout=compact&title_color=ff6a00&icon_color=ff6a00&bg_color=0b0b0b&border_color=ff6a00&langs_count=8)

<sub>📝 <em>Note: Language stats reflect personal repos only. Most Python/FastAPI work is in organization repositories (WakeUp Labs, DAMM Capital) or forks.</em></sub>

</div>

<br/>

---

## 👨‍💻 About Me

I engineer end-to-end **decentralized applications (dApps)** focused on DeFi infrastructure, cross-chain interoperability, and protocol reliability, combining smart-contract architecture with scalable backend systems. My work centers on EVM-based protocols, canonical PostgreSQL schemas, and asynchronous Python/FastAPI indexers optimized for real-time data ingestion across multiple chains.
I also build keeper bots and automation pipelines powered by Safe-based batched transactions, and design Account Abstraction flows that merge security, UX simplicity, and verifiable on-chain logic.

### 🔧 Technical Stack

<div align="left">

- **Frontend:** `React`, `Next.js`, `TypeScript`, `Redux-Saga`, `Tailwind CSS`, `Ethers.js`, `Viem`, `Wagmi`, `Tanstack`
- **Backend:** `NestJS`, `Node.js`, `Python` (FastAPI, Asyncio, Web3.py)
- **Smart Contracts:** `Solidity`, `Foundry`, `Hardhat`, `The Graph` (AssemblyScript), `OpenZeppelin`, TokenBase's AM-Bridge
- **Data / Infra:** `PostgreSQL`, `Supabase`, `Redis` Message broker, `Websockets`, `Docker`, `Render`, `Netlify`, `Heroku`, `Firebase`
- **DevOps / CI-CD:** `GitHub Actions`, `Docker Compose`
- **Wallets / Protocols:** `Safe` (4337), `Privy`, `Coinbase CDP`, `Thirdweb`, `Snapshot`, `SafeSnap`
- **Analytics:** `Numpy`, `Pandas`, `Matplotlib`, `Seaborn`

</div>

### 🔧 EIP/ERC Experience

<div align="left">

- **EIP-712** – Typed-data signing and off-chain signature verification
- **EIP-7702** – Pectra's emerging smart-account and batch execution standards
- **EIP-4337** – Account abstraction and Safe-based batch workflows
- **EIP-2612 / Permit2** – Off-chain ERC-20 approvals and delegated transfers
- **ERC-1155** – Multi-token permissioned access control
- **ERC-4626 / ERC-7540** – Tokenized vaults, async deposit/withdraw settlement

<br/>

<div align="center">

![Tech Stack](https://go-skill-icons.vercel.app/api/icons?i=typescript,javascript,react,reactquery,nextjs,html,css,redux,nodejs,nest,python,fastapi,redis,solidity,ethereum,foundry,hardhat,postgres,prisma,docker,git,github,vscode,cursor,npm,yarn&perline=13&titles=true&theme=dark)

</div>

<!-- ---

## 🔭 What I Build

### 🗄️ Backend & Indexing

Real-time event indexers built with **Python / FastAPI**, time-series snapshots, and canonical **Postgres schemas** with partitions and Row-Level Security (RLS).

### 🤖 Automation & Keepers

Keeper bots that monitor, settle, and rebalance via **Safe** batched transactions with robust retry mechanisms and comprehensive observability.

### 🔐 Smart Accounts / Account Abstraction

**Account Abstraction** implementations for **DAMM Capital/Lagoon** using **Safe 4337 + Privy**. For the **DAMM World mini‑app**, I leverage **Safe Smart Accounts** to deliver seamless user experiences.

### 📜 Smart Contracts & Security

Modular vault systems, **EIP‑712** signing flows, **ERC‑1155** access models, with clear on/off-chain boundary design for maximum security and auditability. -->

---

## 🚩 Open Source Projects

### 💎 DAMM Capital — Lagoon (Backend)

**Role:** Lead Developer @ **WakeUp Labs**

**Stack:** `Python` `FastAPI` `PostgreSQL` `Docker` `Render` `Solidity` `Safe SDK`

**Key Features:**

- 🗄️ Canonical **Postgres data model** for vaults: `events` → specialized request tables with partitioned **snapshots** for analytics
- ⚡ High-throughput **FastAPI indexer** that normalizes on-chain events and powers dashboards and APIs
- 🤖 **Keeper bot** automating settlement & rebalances via **Safe** batched transactions with resilient retry & logging

<div align="center">
<a href="https://github.com/DAMM-Cap/damm-world-backend">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=DAMM-Cap&repo=damm-world-backend&theme=dark&title_color=ff6a00&icon_color=ff6a00&bg_color=0b0b0b&border_color=ff6a00" alt="DAMM World Backend" />
</a>
</div>

### 💎 DAMM Capital (Frontend)

**Role:** Lead Developer @ **WakeUp Labs**

**Stack:** `Typescript` `React` `Tanstack` `Privy`

**Key Features:**

- 🔐 **Account Abstraction (EIP 4337):** Privy smart wallet integration for easy user onboarding specifically for the **Lagoon DeFi** flow interaction

<div align="center">
<a href="https://github.com/wakeuplabs-io/DAMM-capital">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=wakeuplabs-io&repo=DAMM-capital&theme=dark&title_color=ff6a00&icon_color=ff6a00&bg_color=0b0b0b&border_color=ff6a00" alt="DAMM Capital" />
</a>
</div>

---

### 🌍 DAMM World — Mini-app

**Role:** Lead Developer @ **DAMM Capital**

**Stack:** `Next.js` `TypeScript` `Safe Smart Accounts`

Smart-account driven mini-app for vault interaction and AMM strategies. Onboarding designed around **Safe Smart Accounts** for consistent UX across all wallet types.

#### DAMM Capital

<div align="center">
<a href="https://github.com/DAMM-Cap/damm-world-frontend">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=DAMM-Cap&repo=damm-world-frontend&theme=dark&title_color=ff6a00&icon_color=ff6a00&bg_color=0b0b0b&border_color=ff6a00" alt="DAMM World Frontend" />
</a>
</div>

---

### 🦋 Libélula Space

**Stack:** `NestJS` `IPFS` `EIP‑712` `Solidity (ERC‑1155)`

Decentralized **privacy vault** system featuring:

- Token‑gated encrypted vaults
- Client-side key derivation
- Schema versioning for content metadata

<div align="center">
<a href="https://github.com/martillansky/content-vault-contracts">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=martillansky&repo=content-vault-contracts&theme=dark&title_color=ff6a00&icon_color=ff6a00&bg_color=0b0b0b&border_color=ff6a00" alt="Libelula contracts" />
</a>
<a href="https://github.com/martillansky/content-vault-subgraphs">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=martillansky&repo=content-vault-subgraphs&theme=dark&title_color=ff6a00&icon_color=ff6a00&bg_color=0b0b0b&border_color=ff6a00" alt="Libelula subgraphs" />
</a>
</div>

---

### 👤 Proof of Humanity v2 (PoHv2)

**Role:** Lead Developer @ **Kleros**

Led development and migration tooling including governance automation, cross-chain considerations, and comprehensive registry management.

<div align="center">
<a href="https://github.com/Proof-Of-Humanity/proof-of-humanity-v2-web">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Proof-Of-Humanity&repo=proof-of-humanity-v2-web&theme=dark&title_color=ff6a00&icon_color=ff6a00&bg_color=0b0b0b&border_color=ff6a00" alt="PoH Frontend" />
</a>
<a href="https://github.com/Proof-Of-Humanity/proof-of-humanity-v2-contracts">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Proof-Of-Humanity&repo=proof-of-humanity-v2-contracts&theme=dark&title_color=ff6a00&icon_color=ff6a00&bg_color=0b0b0b&border_color=ff6a00" alt="PoH Contracts" />
</a>

</div>

<!-- ---

## 🛠️ Technologies

<div align="center">

### 💻 Languages

`TypeScript` `Python` `Solidity` `JavaScript`

### ⚙️ Backend

`FastAPI` `NestJS` `PostgreSQL` `Redis` `Docker` `Python`

### 🎨 Frontend

`Next.js` `React` `TailwindCSS` `viem` `wagmi` `TypeScript`

### ⛓️ Blockchain & Web3

`Safe SDK` `EIP‑712` `Permit2` `The Graph` `Foundry` `Hardhat` `Ethereum`

### 🚀 Infrastructure & DevOps

`Render` `GitHub Actions` `Pulumi` `Cloudflare` `Docker` `Git`

</div>

<br/>

<div align="center">

![Tech Stack](https://go-skill-icons.vercel.app/api/icons?i=javascript,typescript,python,fastapi,solidity,react,nextjs,html,css,redux,nodejs,nest,ethereum,foundry,hardhat,postgres,prisma,docker,git,github,vscode,cursor,npm,yarn,reactquery,redis&perline=8&titles=true&theme=dark)

</div>
 -->

---

## 🎓 Education & Background

**Ph.D. in Computer Science (AI & Law) / Software Engineer**

Research expertise in **symbolic AI** and **formal argumentation** applied to legal reasoning (Fulbright postdoc @University of Pittsburgh). I bring formal reasoning and rigorous mathematical thinking into protocol and product design, ensuring both technical excellence and logical soundness in every system I build.

**M.Sc. in Law / Legal reasoning**

Research specialization in legal argumentation with a focus in sujective reasoning, legal interpretation, discretionality and proof standardization models.

---

<br/>

</div>

<div align="center">

![GitHub Activity Graph](<https://github-readme-activity-graph.vercel.app/graph?username=martillansky&theme=redical&hide_border=false&area=true&custom_title=Recent%20Activity%20(31%20Days)&color=FF6A00&line=FF6A00&point=FF6A00&bg_color=0b0b0b&height=300&width=200>)

![Contribution Grid Snake](https://raw.githubusercontent.com/martillansky/martillansky/gh-pages/github-contribution-grid-snake-dark.svg#gh-dark-mode-only)
![Contribution Grid Snake](https://raw.githubusercontent.com/martillansky/martillansky/gh-pages/github-contribution-grid-snake.svg#gh-light-mode-only)

</div>

<br/>

---

## 📫 Contact & Connect

<div align="center">

[![Email](https://img.shields.io/badge/📧%20Email-you%40example.com-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0b0b0b)](mailto:martin.moguillansky@gmail.com)
[![LinkedIn](https://img.shields.io/badge/💼%20LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0b0b0b)](https://linkedin.example/martin)
[![Twitter](https://img.shields.io/badge/🐦%20Twitter-Follow-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white&labelColor=0b0b0b)](https://twitter.example/martin)
[![Portfolio](https://img.shields.io/badge/🌐%20Portfolio-Visit-ff6a00?style=for-the-badge&logo=google-chrome&logoColor=white&labelColor=0b0b0b)](https://example.com)

</div>

---

<div align="center">

<!-- ### ⚡ Currently working on

Building the next generation of DeFi infrastructure with Account Abstraction and smart account integrations.
 -->

### 🤝 Open to

Collaborations on DeFi protocols, Web3 infrastructure projects, and innovative blockchain solutions.

---

⭐️ **Star this repo if you find my work interesting!**

[![GitHub followers](https://img.shields.io/github/followers/martillansky?label=Follow%20%40martillansky&style=social)](https://github.com/martillansky)

</div>
