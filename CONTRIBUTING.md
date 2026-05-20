# Contributing to Zellio Finance

First off, thank you for considering contributing to Zellio Finance! We welcome community input to help us build the most secure and compliant RWA tokenization platform on Base.

## How Can I Contribute?

### 1. Reporting Bugs
If you find a bug (that is NOT a security vulnerability), please open an issue in the relevant repository. 
*If it IS a security vulnerability, please refer to our [Security Policy](./SECURITY.md).*

### 2. Suggesting Enhancements
We are always looking for ways to improve. Open a GitHub Discussion or Issue to propose new features or architectures.

### 3. Submitting Pull Requests
1. Fork the repository.
2. Create a new branch (`git checkout -b feat/your-feature-name`).
3. Make your changes. Ensure you write tests for any new smart contract logic!
4. Run the test suite (e.g., `forge test`).
5. Commit your changes (`git commit -m 'feat: add awesome new feature'`).
6. Push to the branch (`git push origin feat/your-feature-name`).
7. Open a Pull Request against the `main` branch.

## Development Standards
- **Smart Contracts**: We follow the official Solidity style guide. Use `forge fmt` before committing.
- **Testing**: We strive for 100% test coverage on critical contract logic. PRs without adequate Foundry tests will not be merged.
- **Commit Messages**: We prefer Conventional Commits (e.g., `feat:`, `fix:`, `docs:`).

By contributing, you agree that your contributions will be licensed under the MIT License.
