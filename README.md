# 🪙 ERC-20 Token Sale DApp — Ethereum

![Solidity](https://img.shields.io/badge/Solidity-ERC--20-363636?style=flat&logo=solidity)
![Truffle](https://img.shields.io/badge/Framework-Truffle-5E464D?style=flat)
![Ethereum](https://img.shields.io/badge/Network-Ethereum-3C3C3D?style=flat&logo=ethereum)
![ICO](https://img.shields.io/badge/Type-ICO%20%2F%20Crowdsale-0C447C?style=flat)

A decentralized token sale (ICO/crowdsale) DApp built on Ethereum. Investors send ETH directly to the sale contract and receive ERC-20 tokens in return at a fixed rate. The contract manages the full sale lifecycle — from token allocation and fund collection to owner withdrawal — with a transparent, trustless frontend interface.

---

## How it works

```
Deploy contracts → Investor sends ETH → Contract validates → Tokens transferred → Owner withdraws funds
```

Each step is enforced on-chain — no intermediary, no trust required.

---

## Key features

- **ERC-20 compliant token** — configurable name, symbol, supply, and token price
- **ETH → Token exchange** — fixed rate conversion enforced in contract logic
- **Atomic fund + token handling** — sale contract manages collection and distribution in one transaction
- **Owner-controlled withdrawal** — role-based access control for fund management
- **Frontend DApp** — real-time token balance display and sale progress via Web3.js
- **Contract test suite** — unit tests with Truffle

---

## Contract architecture

| Contract | Role |
|---|---|
| Token contract | ERC-20 token — supply, balances, transfers |
| Sale contract | Crowdsale logic — ETH acceptance, token distribution, fund management |

---

## Quick start

```bash
git clone https://github.com/monickark/eth_token_sale
cd eth_token_sale
npm install
truffle migrate --network sepolia
npm start
```

---

## Project structure

```
eth_token_sale/
├── contracts/       # ERC-20 token + crowdsale Solidity contracts
├── migrations/      # Truffle deployment scripts
├── test/            # Contract test suite
└── src/             # Frontend DApp (HTML/CSS/JS)
```

---

## Built by

[Monicka Akilan](https://github.com/monickark) — Blockchain Architect · Smart Contract Engineer
[![LinkedIn](https://img.shields.io/badge/LinkedIn-monickark-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/monickark/)
