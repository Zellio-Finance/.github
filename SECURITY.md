# Security Policy & Bug Bounty

**Zellio Finance** takes security very seriously. If you discover a vulnerability in any of our smart contracts, SDKs, or infrastructure, please follow the responsible‑disclosure process below.

---

## 📬 Responsible Disclosure Procedure

1. **Do NOT publicly disclose** the vulnerability (e.g., on Twitter, Reddit, or a public issue tracker) until we have had a chance to investigate and remediate it.
2. **Contact us securely** using one of the following methods:
   - **Encrypted email**: `security@zellio.finance` (PGP‑encrypted). Our public PGP key can be downloaded from: `https://zellio.finance/pgp-key.txt`.
   - **GPG‑signed message**: If you prefer the `gpg` command line, you can encrypt the details with our key ID `0xA1B2C3D4E5F6G7H8`.
3. Provide as much detail as possible:
   - A concise summary of the issue.
   - Steps to reproduce, including transaction hashes, contract addresses, and any relevant source code snippets.
   - Your proposed fix (optional but appreciated).
4. We will acknowledge receipt of your report within **24 hours** and keep you updated on our investigation timeline.
5. Once a fix is deployed, we will credit you according to the bounty schedule (see below) and publicly thank you (unless you request anonymity).

---

## 💰 Bug Bounty Program

| Severity | Reward (USD) |
|----------|--------------|
| **Critical** – Remote code execution, loss of funds, or a break of the ERC‑3643 compliance guarantees | **$100,000** |
| **High** – Exploits that can lead to unauthorized token transfers, minting, or permission bypass | **$30,000** |
| **Medium** – Issues that compromise data privacy, cause denial‑of‑service, or affect UI integrity | **$5,000** |
| **Low** – Minor bugs, documentation errors, or non‑security related findings | **$0 – $1,000** (subject to discretion) |

### Eligibility
- The bug bounty applies to **all public repositories** under the `Zellio-Finance` GitHub organization (`contracts`, `audit`, `.github`).
- Only **original findings** that have not been previously reported or disclosed are eligible.
- Rewards are paid in **USDC** to the address you provide, after we verify the vulnerability and confirm the fix.

---

## 🛡️ Disclosure Timeline (Optional)
We support coordinated public disclosure. If you wish to disclose the vulnerability publicly, please let us know your preferred timeline. Typical timelines:
- **Immediate** (0‑30 days) – For critical bugs that are already patched.
- **Standard** (30‑90 days) – For high‑severity bugs.
- **Extended** (90‑180 days) – For lower‑severity findings.

---

## 📜 Legal Safe Harbor
We will not pursue any legal action against researchers acting in good faith, provided they:
- Follow the responsible disclosure steps above.
- Do not engage in any activity that harms users or the network (e.g., extracting funds, exploiting the bug for profit before reporting).

---

## 📄 References
- Our **PGP key**: `https://zellio.finance/pgp-key.txt`
- **Bug bounty policy** (full version): `https://github.com/Zellio-Finance/.github/blob/main/SECURITY.md`

---

*If you have any questions, feel free to reach out to `security@zellio.finance`.*
