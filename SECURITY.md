# Security Policy

At Zellio Finance, the security of our smart contracts and users' funds is our absolute highest priority. We take all security reports seriously and are committed to resolving vulnerabilities quickly and responsibly.

## Supported Versions

Currently, the smart contracts deployed on the Base network (and Base Sepolia testnet) are actively supported.

| Component | Supported |
| --- | --- |
| Zellio Core Contracts (ERC-3643) | ✅ |
| Permissioned DEX | ✅ |
| Yield Distributor | ✅ |
| Frontend UI/API | ❌ (Bug bounty applies to smart contracts primarily) |

## Reporting a Vulnerability

If you believe you have found a security vulnerability in our smart contracts, **please do not open a public issue.**

Instead, please email us directly at:
👉 **security@zellio.finance**

When reporting, please include:
1. A detailed description of the vulnerability.
2. The specific smart contract(s) and line numbers involved.
3. A Proof of Concept (PoC) using Foundry or Hardhat demonstrating the exploit.
4. The potential impact (e.g., fund loss, bypass of KYC/compliance checks).

We aim to respond to all security reports within **24-48 hours**.

## Bug Bounty Program

Zellio Finance operates a bug bounty program to reward researchers who help secure our protocol. Bounties are paid out based on the severity of the vulnerability, determined using the CVSS (Common Vulnerability Scoring System) and our internal risk assessment.

* **Critical** (e.g., direct loss of funds, unauthorized minting): Up to $100,000 USD
* **High** (e.g., bypassing KYC/compliance restrictions, significant griefing): Up to $25,000 USD
* **Medium** (e.g., logic errors leading to minor disruption): Up to $5,000 USD
* **Low** (e.g., gas optimizations, UI bugs): Swag or up to $1,000 USD

*Note: Bounties are paid in USDC at the discretion of the Zellio team. Public disclosure before a fix is implemented will forfeit the bounty.*
