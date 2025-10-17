# Naming Decision – `choosewallet`

**Context**  
You evaluated keeping the project name consistent across the domain, GitHub repository, and local directory. Options considered:

- `choosewallet`
- `choose-wallet`
- `choose_wallet` (discarded early because it conflicts with JavaScript/URL norms)

At the time of the decision the domain had not yet been registered, so both `choosewallet.org` and `choose-wallet.org` remained available.

**Considerations**

1. **Consistency with Branding**
   - The planned brand name is “Choose Your Wallet”.
   - Using `choosewallet` directly mirrors the domain and avoids introducing a hyphen that doesn’t exist in the brand.

2. **Developer Experience**
   - Repository and directory names without punctuation are simpler for shell commands, CI configuration, and package scripts (no quoting or special handling).
   - Hyphenated repo names are common—over 50% of the top 30 starred GitHub repos use them (e.g., `public-apis`, `system-design-primer`). However, adopting a hyphen would make the repo diverge from the domain.

3. **SEO & URL Alignment**
   - Domains and URLs consistently written as `choosewallet` reinforce a single canonical identifier.
   - If necessary, the hyphenated domain can be registered later and redirected, but all primary assets benefit from one spelling.

4. **Future Proofing**
   - Additional repos can extend the namespace (e.g., `choosewallet-data`, `choosewallet-design`) without ambiguity.

**Conclusion**

> Keep the repository, directory, and primary domain name aligned as `choosewallet`.  
> Optionally register `choose-wallet.org` later to redirect to `choosewallet.org`, but build the project and tooling around the non-hyphenated name.

**Next Steps**

1. Register `choosewallet.org` (and consider `choose-wallet.org` for redirection).
2. Create the GitHub repository `github.com/dongzhenye/choosewallet`.
3. Maintain documentation and deployment scripts using the `choosewallet` naming convention.
