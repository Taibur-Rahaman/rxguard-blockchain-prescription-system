# RxGuard — Blockchain Prescription System

A blockchain-based prescription verification and anti-counterfeit medicine tracking system for Bangladesh healthcare.

## Overview

RxGuard aims to secure the prescription lifecycle on-chain — from doctor issuance through pharmacy dispensing — so patients, pharmacists, and regulators can verify authenticity and detect fraudulent or recalled medicines.

> **Note:** This repository is the project home for RxGuard. For the full working implementation (smart contracts, React frontend, Hardhat tooling, and documentation), see **[BlockMed V1.2](https://github.com/Taibur-Rahaman/blockmed-v1.2)**.

## Goals

- Tamper-proof digital prescriptions on a public or permissioned blockchain
- QR-based verification at pharmacies
- Role-based access (doctor, pharmacist, manufacturer, patient, regulator)
- Medicine batch tracking and recall support
- Bangla and English UI for local adoption

## Related Project

| Repository | Description |
|------------|-------------|
| [blockmed-v1.2](https://github.com/Taibur-Rahaman/blockmed-v1.2) | Full BlockMed V2 implementation with Hardhat, React/Vite, RBAC smart contract, Dev Mode, and deployment guides |

## Tech Stack (BlockMed implementation)

- **Smart contracts:** Solidity, Hardhat
- **Frontend:** React, Vite, Tailwind CSS, ethers.js
- **Features:** Dev Mode, MetaMask, QR verification, multi-language (EN/BN)

## Quick Start

Clone and run the full system from the BlockMed repository:

```bash
git clone https://github.com/Taibur-Rahaman/blockmed-v1.2.git
cd blockmed-v1.2
npm install
npm run start
```

Open `http://localhost:3000` and use **Dev Mode** for local testing without a wallet.

See the [BlockMed README](https://github.com/Taibur-Rahaman/blockmed-v1.2#-quick-setup-latest-github-version) for complete setup, scripts, and deployment instructions.

## Author

**Md Taibur Rahaman** — [GitHub](https://github.com/Taibur-Rahaman)

## License

See [LICENSE](./LICENSE) in this repository.
