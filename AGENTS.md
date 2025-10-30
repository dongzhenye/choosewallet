# ChooseWallet – Agent Handbook

This file captures the essential context so any future agent (or the same developer after a break) can resume work with minimal ramp-up.

---

## Project Snapshot
- **Brand**: ChooseWallet (retain this spelling; see `docs/naming-decision.md` for rationale).
- **Mission**: Provide a trustworthy, open-source advisor that recommends crypto wallets based on network, custody, device, security, and budget needs while linking only to verified official domains.
- **Inspiration**: bitcoin.org’s “Choose Your Wallet” wizard, extended to multi-chain ecosystems and modern UX.

## Repository & Hosting
- **GitHub**: `https://github.com/dongzhenye/choosewallet`
- **Current Branch**: `main` (clean, in sync with origin).
- **Local Path**: `~/Projects/choosewallet`
- **Planned Hosting**: Vercel (not yet configured).
- **Domains**: `choosewallet.org` preferred (availability confirmed earlier but not registered yet). Optionally secure `choose-wallet.org` or `walletchoose.com` for redirects later.

## Key Documents
- `README.md`: project overview, vision, initial backlog, next steps.
- `docs/competitor-landscape.md`: summaries of existing wallet finder sites with gaps/opportunities.
- `docs/naming-decision.md`: decision log explaining why “choosewallet” remains the canonical brand (includes comparison with “walletchoose”).

## Completed Work
1. Repository initialized, documentation drafted, and pushed to GitHub.
2. Remote `origin` configured (currently using HTTPS; a proxy was previously required—ensure networking works before pushing).
3. Naming deliberations recorded and updated.

## Outstanding Priorities
1. **Register Domain**: grab `choosewallet.org` (and any desired alternates) to prevent squatting.
2. **Framework Selection**: choose the stack for the advisor site (e.g., Next.js with static export, Astro, etc.).
3. **Scaffold App**: initialize the project structure, set up linting/CI, and link to Vercel.
4. **Data Model**: design schema for wallet metadata (chains, custody, open-source status, verification proof).
5. **Verification Workflow**: define and automate how official links are vetted (DNS, social cross-checks).
6. **Content Guidelines**: draft style guide and contribution rules for external input.

## Operational Notes
- Previous push failures were due to an inactive proxy at `127.0.0.1:7890`. Ensure proxy config matches your current network setup or switch remote to SSH (`git@github.com:dongzhenye/choosewallet.git`).
- Keep repo and directory names aligned (`choosewallet`) for consistency with documentation and future deployment automation.
- When adding significant context updates or decisions, append them to `docs/` for traceability.

## Suggested Next Session Flow
1. Verify network + proxy settings → `git pull` to confirm local state.
2. Decide on framework → scaffold project files → update README with stack choice.
3. Commit and push scaffolding, then begin implementing the advisor flow/data model.
4. Integrate domain registration + Vercel once the site skeleton renders.

---

Use this file as the checkpoint before closing a session; update it whenever major decisions or blockers emerge.
