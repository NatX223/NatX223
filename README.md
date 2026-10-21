# Hi, I'm Sinachi 👋

Backend & smart contract engineer based in Lagos, Nigeria. I build payment rails, DeFi protocols, and the off-chain services that keep them honest: indexers, reconcilers, price reporters, and worker networks.

**Open to:** Backend · Smart Contract · Web3 Backend roles (remote or Nigeria)

---

## 🔨 Featured work

### [Laxu](https://github.com/NatX223/Laxu) · borrow against open perp trades
Tokenizes each open leveraged position on Arcus (Robinhood Chain) into its own ERC-20/ERC-7540 with an isolated lending pool, so traders can borrow USDG against a live trade and others can buy in.
- Resumable open-position state machine with automatic refunds, indexer + reconciler, and an on-chain price reporter
- Tiered LTV by leverage, stale-price guard that blocks borrowing but never liquidation
- **114 contract tests + 90 backend tests**
- *Solidity · Hardhat · OpenZeppelin · Node/Express · TypeScript · Prisma · Postgres · Next.js · Privy*
- [Live app](https://laxu.vercel.app) · [Demo](https://www.loom.com/share/9debdffa70c042d0a8f9f573f3c89843) · Built for Arbitrum Open House Singapore 2026

### [Arkivate](https://github.com/NatX223/Arkivate) · decentralized triggers for Arkiv data
An open network of workers that react to Arkiv data changes and expiry ("when X happens, do Y") and burn a permanent public receipt for every action, so a skipped job can be proven.
- Multi-worker dedupe and failover across two GCP regions, coordinated only through on-chain receipts
- Sealed triggers: commit-reveal privacy with a `verify` tool that proves censorship from public reads
- Cut the deployment's RPC read cost **~50×** through query batching and caching
- *TypeScript · Node/Express · Arkiv SDK · viem · zod · Next.js 15 · GCP · Caddy · systemd*
- [Live app](https://arkivate.vercel.app) · Built for Arkiv Global Tour Stop 2026

### [Xap](https://github.com/NatX223/XanPay) · x402 micropayments
Millicent payments over x402 on Circle, with a payment card and an SDK for merchants.
- *TypeScript · Node · Firebase · SDK package*

### [XanPay](https://github.com/NatX223/XanPay-Prodfest) · crypto payments for businesses
Business wallet with inventory management, crypto payment acceptance, and fast off-ramp to fiat.
- *TypeScript · Node · React Native*

### [Reactivate](https://github.com/NatX223/Reactivate) · self-sustaining reactive contracts
Automatically monitors, tops up, and reactivates Reactive Network contracts before they run out of gas, plus a mini bridge from Base to fund dev accounts.
- Factory-deployed funder, monitor, and debt-payer contracts on Reactive mainnet
- *Solidity · Foundry · Node/Express · Next.js · Wagmi · Firestore*
- [Live app](https://reactivat.app) · [Demo](https://www.loom.com/share/7d530114a9b24a59bbbbd48a1251e602) · Built for BUIDL with REACT x DoraHacks 2025

### [Dinamiko](https://github.com/DinamikoApp/Dinamiko) · automated on-chain investing (team project)
Time-, price-, and volume-triggered buy/sell and liquidity strategies powered by Chainlink data feeds and automation.
- *Solidity · Scaffold-ETH 2 · Chainlink · Next.js*

---

## 🧰 Stack
**Backend:** TypeScript · Node.js · Express · PostgreSQL · Prisma · Firebase/Firestore
**Smart contracts:** Solidity · Hardhat · Foundry · OpenZeppelin · ERC-4626 / ERC-7540
**Web3 infra:** viem · Wagmi · Privy · Chainlink · EVM L2s (Arbitrum Orbit, Base)
**Frontend & mobile:** Next.js · React · React Native/Expo
**Ops:** GCP · Vercel · systemd · Caddy

## 📫 Reach me
[Email](mailto:ajuziesinachi@gmail.com) · [LinkedIn](https://www.linkedin.com/in/sinachi-ajuzie/) · [X]([YOUR_X](https://x.com/NatX_eth))
