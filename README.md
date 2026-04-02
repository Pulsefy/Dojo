# Dojo 🥋

<p align="center">
  <img src="https://img.shields.io/badge/Stellar-Soroban-blue.svg" alt="Stellar Soroban">
  <img src="https://img.shields.io/badge/License-Apache%202.0-orange.svg" alt="License">
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen.svg" alt="PRs Welcome">
</p>

**Launch. Pump. Own.**  
The simplest, fairest, and cheapest meme coin & token launchpad on **Stellar**.

Dojo lets anyone create a viral meme coin in under 2 minutes — no coding required. Upload a funny meme, choose a ticker, and launch with a transparent **bonding curve** that automatically bootstraps liquidity on the Stellar DEX.

Built for speed, low fees, and community fun — perfect for creators in Nigeria and across Africa.

---

## ✨ Why Dojo?

*   **⚡ Ultra-cheap & instant** — Launch and trade for pennies with 3-5 second finality.
*   **⚖️ Fair by design** — Bonding curve prevents sniping and gives everyone equal opportunity.
*   **🌌 Stellar-native** — Powered by Soroban smart contracts with optional **X-Ray ZK stealth mode** for private early launches.
*   **📱 Mobile-first** — Seamless experience with Freighter wallet on phones.
*   **🤝 Fully open-source** — Built by the community, governed by the community.

**Tagline:** *Turn your meme into a movement on Stellar.*


---

## 🚀 Quick Start (Testnet)

### 1. Clone the repository
```bash
git clone https://github.com/pulsefy/dojo.git
cd dojo
```

### 2. Install dependencies
```bash
# Frontend
cd frontend && yarn install

# Contracts
cd contracts && cargo build
```

### 3. Run locally
```bash
# Start frontend (from frontend/ directory)
yarn dev
```

Connect your **Freighter wallet**, upload a meme, and launch your first test coin on Stellar Testnet!

> [!TIP]
> Check the [Full setup guide](docs/SETUP.md) for detailed instructions.


## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Smart Contracts** | Rust + Soroban (Stellar) |
| **Frontend** | React + TypeScript + Tailwind CSS |
| **Wallet** | Freighter Wallet integration |
| **Backend** | Node.js / TypeScript (indexing & API) |
| **Blockchain** | Stellar (Testnet → Futurenet → Mainnet) |
| **Privacy** | X-Ray (Protocol 25) ZK proofs |
| **UI** | Tailwind + shadcn/ui |

> [!NOTE]
> **Base:** Extended from open-source Stellar token launchpad examples.


## 🗺️ Roadmap (Brief)

Dojo is being built in iterative phases targeting a mainnet launch in 2026.

*   **Phase 1** 🟢: Core token minting + basic bonding curve on Testnet
*   **Phase 2** 🟡: Automatic liquidity bootstrapping + platform fee system
*   **Phase 3** ⚪: UI/UX polish, mobile optimization, and optional X-Ray ZK stealth mode
*   **Phase 4** ⚪: Security audits, mainnet deployment, and official launch
*   **Phase 5** ⚪: Advanced features: yield mechanics, community governance, and growth

> [!IMPORTANT]
> See the [full ROADMAP.md](ROADMAP.md) for detailed milestones and timelines.


## 🤝 How to Contribute

We welcome contributors of all levels! Whether you're experienced with **Rust/Soroban**, **Frontend (React)**, **Design**, or **Technical Writing**.

### 💡 Ways to Contribute
1. Fix bugs or add new features
2. Improve UI/UX and mobile experience
3. Create Naija-themed meme templates
4. Write documentation or tutorials
5. Test launches and report issues

### 🔨 Getting Started
- Check the [Issues tab](https://github.com/pulsefy/dojo/issues) for open tasks.
- Look for labels: `good first issue`, `help wanted`.
- Fork the repo → Create a feature branch → Open a Pull Request.

> [!NOTE]
> Contributors may earn **XLM bounties** (and later **$DOJO** governance tokens) for significant PRs. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 💰 Funding & Support

*   **SCF Build Award:** We are applying to the Stellar Community Fund (SCF) for development support and audits.
*   **License:** All code is licensed under **Apache 2.0**.
*   **Governance:** Transparent treasury and governance coming after mainnet launch.

---

## 🔗 Links

*   **Documentation:** [Stellar Developers](https://developers.stellar.org)
*   **Repository:** [GitHub](https://github.com/pulsefy/dojo)

---

<p align="center">
  Built with ❤️ for the Stellar ecosystem — especially creators in Africa.
  <br>
  <b>Launch your first meme today and make Stellar the most fun chain!</b>
</p>

