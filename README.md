# kahyaas-smart-contracts
Official Smart Contracts for Kahyaas (كهيعص) Digital Islamic Currency
# kahyaas-smart-contracts

![TRIZEL Logo](ضع هنا رابط شعار النجمة الثمانية لـ TRIZEL)

## Official Smart Contracts for Kahyaas (كهيعص) Digital Islamic Currency

---

## رمز العملة (Symbol)
**كهيعص (KAHYAAS)**

---

## Project Overview

**Kahyaas** is a Shariah-compliant digital currency featuring built-in mechanisms for:
- **Zakat (الزكاة)**: 2.5% annual distribution mechanism.
- **Khums (الخمس)**: 20% distribution mechanism.

---

## Deployment Networks
- **Binance Smart Chain (BSC) Testnet**
- **TRON Nile Testnet**

---

## Repository Structure
- `contracts/`: Contains the Solidity Smart Contracts.
- `scripts/`: Deployment scripts using Hardhat.
- `.github/workflows/`: Automated deployment workflows via GitHub Actions.

---

## Quick Start
```bash
npm install
npx hardhat compile
npx hardhat run scripts/deploy.js --network bscTestnet
npx hardhat run scripts/deploy.js --network tronNile
