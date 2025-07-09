# Allocator Bookkeeping Repository for Chimsen

## Allocator JSON Link
[Chimsen Allocator JSON](https://github.com/filecoin-project/Allocator-Registry/blob/main/Allocators/chimsen.json)

## Client Diligence
Chimsen verifies clients to ensure trust and prevent sybil attacks, focusing on robust KYC/KYB processes and data ownership validation.

- **KYC Verification**: Clients submit government-issued photo ID (e.g., passport) and facial photo via Gitcoin Passport (minimum score: 20).
- **KYB Verification**: Businesses provide registration certificates, business licenses, and proof of authorized signers (e.g., board approval).
- **New User Check**: New GitHub IDs (<2 months) or first-time applicants are limited to 50 TiB initial DataCap.
- **Data Ownership**: Clients submit contracts, IP certificates, or attestations to prove dataset ownership.
- **Third-Party KYC/KYB**: Use Toggle for automated KYC/KYB; manual verification via virtual meeting if preferred.
- **Audit Trail**: All diligence records are stored on GitHub for Governance Team audits.

## Description of Data Diligence
Chimsen ensures datasets meet Fil+ program scope and legal requirements through rigorous data verification and sampling.

- **Legal Compliance**: Consult local legal experts to verify datasets comply with regional data protection laws.
- **Data Ownership**: Verify ownership via contracts, digital signatures, or public URLs for open datasets.
- **Data Sampling**: Randomly sample sectors using Booster-Bitswap and ipfs-car to confirm data integrity.
- **Tool Usage**: Use CID Checker Bot and `datacapstats.io` to verify deal data matches client claims.
- **Public Datasets**: Require retrievability (RSR >75%) via SPARK protocol for open datasets.
- **Audit Evidence**: Maintain detailed logs of sampling and verification on GitHub for Governance audits.

## Short Description of Pathway for Clients
Chimsen offers a transparent, efficient pathway for small-scale developers, enterprises, and learners to onboard high-quality data to Filecoin. With robust KYC/KYB, flexible SP selection, and clear compliance processes, we ensure trust and scalability, making us ideal for diverse, impactful datasets.

## Contact Info
- **WebSite**: [chimsen](https://www.chimsen.com/en)
- **Enterprise Email**: lium@chimsen.com
- **Slack**: lmmm (Filecoin Slack)
- **GitHub**: [LM-1207](https://github.com/LM-1207)
- **Support**: Open issues on [LM-1207/filplus-chimsen](https://github.com/LM-1207/filplus-chimsen)

## Detailed Allocator Policies, Procedures, and Requirements
Chimsen adheres to Fil+ governance to ensure fair, transparent DataCap allocation and compliance.

- **Application Process**: Clients submit detailed applications via GitHub issues, including project details and KYC/KYB.
- **Review Timeline**: Applications are reviewed within 3 business days; clarifications requested via GitHub comments.
- **Allocation Tranches**: Standardized tranches (5%, 10%, 20%, 40%) up to 10 PiB per client.
- **DataCap Expiry**: Unused DataCap expires after 3 months; non-responsive clients are flagged.
- **SP Distribution**: Require 5+ replicas across 3+ geopolitical regions, with no SP exceeding 25% allocation.
- **Compliance Monitoring**: Weekly checks via AC Bot and `datacapstats.io` ensure deal-making compliance.

## Risk Mitigation Strategies
Chimsen employs strict measures to protect its pathway, reputation, and the Fil+ program from abuse.

- **OpSec Standards**: Secure multisig wallet (`f2g6nfx52jb2o743mikkrtkboio5t4h5qxah6glca`) using Ledger hardware wallet.
- **Client Vetting**: Enforce KYC/KYB and monitor new GitHub IDs to prevent sybil attacks.
- **Throttling Mechanism**: Limit initial DataCap to 50 TiB for new users; escalate based on compliance.
- **Non-Compliance Action**: Suspend DataCap for violations, with 3 weeks to rectify or face blacklisting.
- **Transparency**: Publish all allocation decisions and diligence records on GitHub for public review.
- **Monitoring Tools**: Use `check bot` and SPARK to monitor client activity and retrievability in real-time.

## Dispute Resolutions
Chimsen resolves disputes transparently and promptly, ensuring fairness and accountability.

- **Internal Disputes**: Client disputes are logged via email (lium@chimsen.com) and resolved within 1-2 days.
- **External Disputes**: Third-party disputes are addressed via Filecoin Foundation’s tracker within 21 days.
- **Evidence Submission**: Both parties submit evidence (e.g., deal records, KYC/KYB) for review.
- **Accountability**: Non-compliant clients face DataCap suspension or blacklisting; decisions are documented.
- **Private Resolution**: Internal disputes respect client privacy; external disputes follow public transparency.
- **Mediation**: Engage neutral third parties for complex disputes to ensure fair outcomes.

## Compliance Audit Check
Chimsen ensures clients and SPs meet program-wide and pathway-specific requirements through rigorous auditing.

- **Weekly Monitoring**: Use AC Bot and `datacapstats.io` to track deal-making and retrievability (RSR >75%).
- **SP Verification**: Confirm SP KYB (e.g., business license, datacenter proof) for non-vetted providers.
- **DataCap Usage**: Audit clients for >75% DataCap utilization before approving subsequent tranches.
- **Random Sampling**: Conduct random sector checks via SPARK and Booster-Bitswap for data compliance.
- **Bookkeeping**: Maintain transparent records on GitHub, including allocation and audit logs.
- **Governance Reporting**: Submit detailed compliance reports to the Governance Team during audits.
