# FalXDex Smart Contract Audit by Line1.io

This repository contains the security audit report for the FalXDex project, a blazing fast decentralized exchange (DEX) on the Solana blockchain. This audit was conducted by **Line1.io** to ensure the security and integrity of the FalXDex smart contracts and codebase.

## Project Overview

### Project Name: FalXDex

- **Website:** [FalXDex](https://falxdex.com/)

### About the Project

FalXDex is a next-generation decentralized exchange (DEX) built on the Solana blockchain, leveraging the speed and efficiency of the Solana ecosystem to provide fast and secure trading experiences.

- **Chain:** Solana
- **Language:** Rust

## Audit Summary

### Version History

- **V1.0:** Initial Report - 3rd October 2024

### Scope of Work

The audit focused on a thorough security assessment of the Rust-based Smart Contracts provided by FalXDex. This included identifying vulnerabilities, ensuring code integrity, and verifying adherence to security best practices. The auditing process followed a structured and methodical approach:

1. **Pre-Audit Review:** Review of specifications, source code, and supplementary documentation.
2. **Manual Code Review:** Detailed inspection of the source code to identify logic flaws, access control issues, and susceptibility to known exploits.
3. **Specification Comparison:** Verification of code alignment with specifications and functional requirements.
4. **Test Coverage Analysis:** Analysis of test coverage to identify untested paths.
5. **Symbolic Execution and Automated Tools:** Simulation of inputs and execution paths using symbolic execution and automated tools.
6. **Best Practices Review:** Evaluation of the smart contract’s architecture for efficiency, maintainability, and security.
7. **Actionable Recommendations:** Specific itemized recommendations provided upon audit completion.

### Imported Packages

The audit reviewed the following dependencies:

- `anchor-lang 0.29.0`
- `anchor-spl 0.29.0`
- `spl-token 4`
- `spl-transfer-hook-interface 0.5.1`
- `solana-program 1.17`
- `thiserror 1.0`
- `uint 0.9.1`
- `borsh 0.9.1`
- `solana-security-txt 1.1.1`
- `proptest 1.0`
- `serde 1.0.117`
- `serde_json 1.0.59`

## Contact

For more information or to get in touch with the FalXDex team:
- **Email:** [info@falxdex.com](mailto:info@falxdex.com)
- **Telegram:** [Direct Contact](https://falx.pro/FalXDexTelegram)
