[security_policy (1).md](https://github.com/user-attachments/files/33010241/security_policy.1.md)
# Security Policy

Security is the foundational layer of the Supernova Protocol. We take all potential vulnerabilities within our SVM architecture, smart contracts, and infrastructure routing extremely seriously.

Our core philosophy is absolute transparency with our community and strict adherence to responsible disclosure practices.

## Supported Versions

Please ensure you are testing or reviewing the correct branches of our protocol.

| Version | Environment | Supported | Status | 
| ----- | ----- | ----- | ----- | 
| **V2.0.x** | Mainnet-Beta | ❌ | *Pending Launch (Oct 2026)* | 
| **V2.0-rc** | Devnet | ✅ | *Active Testing* | 

## Reporting a Vulnerability

If you have discovered a potential security vulnerability in the Supernova smart contracts, our Jito routing implementation, or the terminal UI, **do not open a public issue.** Public disclosure of a vulnerability prior to a patch compromises the protocol and will disqualify you from any future bug bounties.

Please report all security findings directly to our security team via email: 👉 **SupernovaLaunchpadDev@gmail.com**

### Required Information for Reports:

To help us triage and resolve the issue quickly, please include the following in your report:

* A detailed description of the vulnerability and its potential impact.

* Steps to reproduce the issue (including any scripts, transaction hashes on Devnet, or payload examples).

* The specific file, contract, or endpoint affected.

### Response Time

Our engineering team operates globally. You can expect an initial acknowledgment of your report within **12 hours**, and a detailed technical assessment within **48 hours**.

## Audit Status & Smart Contracts

The Supernova V2 core smart contracts (Anchor/Rust) are currently undergoing rigorous zero-knowledge testing.

* **Pre-Launch:** A comprehensive smart contract audit is currently scheduled with a Tier-1 auditing firm (OtterSec).

* **Transparency:** The full, unredacted audit report will be published in this repository and linked in our Litepaper exactly 24 hours prior to the Mainnet-Beta migration. The source code will remain in a private repository until this audit is complete to prevent malicious cloning prior to launch.

## Bug Bounty Program

A formal Bug Bounty program (managed via platforms like Immunefi) will be announced concurrently with our Mainnet-Beta deployment. Early disclosures during our Devnet phase that lead to critical architectural patches may be eligible for retroactive compensation at the discretion of the core team.

*By submitting a vulnerability, you agree to our responsible disclosure guidelines and will grant the Supernova team adequate time to patch the exploit before making any information public.*
