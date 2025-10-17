# Choose Your Wallet

An open, community-maintained advisor that helps newcomers and power users pick the right crypto wallet without risking phishing, scams, or mismatched features.

## Original Idea
- Provide friends with tailored wallet recommendations across Bitcoin, Ethereum, Solana, and other chains, factoring in networks, custody model, hardware availability, device OS, and budget.
- Share official wallet links only, with verification steps that protect against spoofed domains.
- Inspired by the bitcoin.org “Choose Your Wallet” wizard, but extend the concept to multi-chain ecosystems, modern UX, and community contributions.
- Host the project for free on Vercel and keep the codebase open-source on GitHub for transparency and contributions.

## Project Snapshot
- **Brand**: Choose Your Wallet
- **Domain**: `choosewallet.org` (available, budget-friendly on Cloudflare Registrar at ~US$7.50 first year / ~US$10 renewal)
- **Planned Hosting**: Vercel (static or hybrid Next.js deployment)
- **Repository**: To be published under `github.com/dongzhenye` (recommended name pending confirmation below)
- **License & Openness**: Public, open-source, encourage third-party wallet teams and security researchers to submit updates.

## Why This Matters
- Search results for “choose a wallet” are dominated by single-chain official docs or affiliate-heavy listicles; there is no neutral, extensible hub that aggregates verified links, security context, and multi-chain coverage.
- Wallet users frequently ask for curated suggestions that match their device, budget, custody preferences, and security posture; a simple advisor flow can reduce onboarding friction.
- Publishing the data and logic in an open repo builds trust and allows the community to keep phishing-safe endpoints up-to-date.

## Core Objectives (MVP)
1. Catalogue vetted wallets with metadata (supported chains, custody, hardware/software, open-source status, fee controls, geographical availability).
2. Build a decision wizard that filters wallets based on user input and outputs a short list with official URLs and safety notes.
3. Include transparent verification steps (DNS lookups, social cross-checks) and change logs for every wallet entry.
4. Ship structured data (Schema.org, JSON-LD) to improve search visibility for wallet-related queries.
5. Establish contribution guidelines (pull request templates, security review checklists).

## Initial Task Backlog
- [ ] Finalize data model for wallet metadata and verification records.
- [ ] Draft information architecture (landing page, wizard, docs, community section).
- [ ] Define link verification workflow (manual review, automated checks, community attestations).
- [ ] Prepare content style guide for wallet descriptions and safety warnings.
- [ ] Set up CI to run link checks and lint JSON data.

## Research & References
- Competitor analysis and source links collected in `docs/competitor-landscape.md`.
- Additional brainstorming notes will be added as features are scoped.

## Next Steps
1. Ensure the GitHub repository name stays aligned with the directory (`choosewallet`).
2. Initialize project scaffolding (framework selection, linting, CI placeholders).
3. Publish the repository to `github.com/dongzhenye` and configure Vercel integration.
4. Begin populating wallet dataset and design the recommendation flow.
