# Naming Decision – `choosewallet`

**Context**  
Naming should stay consistent across domain, GitHub repository, and local directory. Options explored:

- `choosewallet`
- `choose-wallet`
- `choose_wallet` (discarded early because it conflicts with JavaScript/URL norms)
- Later revisit: `walletchoose` (ultimately rejected)

When the decision was made, both `choosewallet.org` and `choose-wallet.org` were available.

**Why `choosewallet` Remains Preferred**

1. **Brand Clarity & SEO**
   - “Choose Your Wallet” is the user-facing promise; `choosewallet` matches that phrasing and aligns with search intent (“choose a wallet”).

2. **Consistency Across Assets**
   - Same string for domain, repo (`github.com/dongzhenye/choosewallet`), directory, and future Vercel deployments keeps URLs, badges, and tooling predictable.
   - Avoids hyphen-related quoting issues in shell scripts, CI configs, and environment variables.

3. **Developer Experience**
   - Hyphenated names are common (≈53% of top-starred GitHub projects), but using the plain form gives frictionless CLI usage while still allowing derivative repos (`choosewallet-data`, `choosewallet-design`).

4. **Flexibility**
   - Alternate domains (e.g., `choose-wallet.org`, `walletchoose.com`) can be registered later for redirects without rebranding the primary project.

**Comparison: `choosewallet` vs `walletchoose`**

| Brand          | Score | Why                                                                                                     |
|----------------|:-----:|----------------------------------------------------------------------------------------------------------|
| choosewallet   | 8/10  | Natural phrasing, keyword aligned, mirrors domain & repo, instills immediate clarity.                   |
| walletchoose   | 7/10  | Distinct and brandable, but sounds less natural; requires more messaging to reinforce the core concept. |

**Conclusion**

> Keep “ChooseWallet” as the master brand and naming convention. Register or redirect alternates as needed, but the project identity—and code artifacts—should remain `choosewallet`.

**Next Steps**

1. Register `choosewallet.org` (optional: secure `choose-wallet.org` or `walletchoose.com` for redirects).
2. Continue using `choosewallet` across documentation, code, and deployments.
3. Revisit naming only if future trademark or market conflicts appear.
