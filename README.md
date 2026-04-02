# Dojo 🥋

**Launch. Pump. Own.**  
The simplest, fairest, and cheapest meme coin & token launchpad on **Stellar**.

Dojo lets anyone create a viral meme coin in under 2 minutes — no coding required. Upload a funny meme, choose a ticker, and launch with a transparent **bonding curve** that automatically bootstraps liquidity on the Stellar DEX.

Built for speed, low fees, and community fun — perfect for creators in Nigeria and across Africa.

### Why Dojo?
- **Ultra-cheap & instant** — Launch and trade for pennies with 3-5 second finality.
- **Fair by design** — Bonding curve prevents sniping and gives everyone equal opportunity.
- **Stellar-native** — Powered by Soroban smart contracts with optional **X-Ray ZK stealth mode** for private early launches.
- **Mobile-first** — Seamless experience with Freighter wallet on phones.
- **Fully open-source** — Built by the community, governed by the community.

**Tagline:** Turn your meme into a movement on Stellar.

---

## 🚀 Quick Start (Testnet)

1. Clone the repo:
   ```bash
   git clone https://github.com/pulsefy/dojo.git
   cd dojo
Install dependencies:Bash# Frontend
cd frontend && yarn install

# Contracts
cd contracts && cargo build
Run locally:Bash# Start frontend (from frontend/ directory)
yarn dev
Connect your Freighter wallet, upload a meme, and launch your first test coin on Stellar Testnet!

Full setup guide → docs/SETUP.md

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

Phase 1: Core token minting + basic bonding curve on Testnet
Phase 2: Automatic liquidity bootstrapping + platform fee system
Phase 3: UI/UX polish, mobile optimization, and optional X-Ray ZK stealth mode
Phase 4: Security audits, mainnet deployment, and official launch
Phase 5 (Post-launch): Advanced features including yield mechanics, community governance, and ecosystem growth

See the full ROADMAP.md for detailed milestones and timelines.

How to Contribute
We welcome contributors of all levels! Whether you're experienced with Rust/Soroban, frontend development, design, documentation, or testing — your help is valuable.
Ways to Contribute:

Fix bugs or add new features
Improve UI/UX and mobile experience
Create Naija-themed meme templates
Write documentation or tutorials
Test launches and report issues
Help with marketing and community growth


Check the Issues tab for open tasks.
Look for labels: good first issue, help wanted, enhancement, or bug.
Fork the repo → Create a feature branch → Make your changes → Open a Pull Request.
Contributors may earn XLM bounties (and later $DOJO governance tokens) for significant PRs.

See CONTRIBUTING.md for detailed guidelines.

Funding & Support

Applying to the Stellar Community Fund (SCF) Build Award for development support and audits.
All code is licensed under Apache 2.0.
Transparent treasury and governance coming after mainnet.


Links
Stellar Developers: https://developers.stellar.org


Built with ❤️ for the Stellar ecosystem — especially creators in Africa.
Launch your first meme today and let's make Stellar the most fun and accessible chain!
