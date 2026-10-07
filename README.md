# dcd-governance-consent

Static OAuth 2.1 consent page for the **Dealiyo Governance Auditor** connector only.

- Served by GitHub Pages at `https://info-dealiyo.github.io/dcd-governance-consent/oauth/consent`.
- Used once by the Referee to authorize the ChatGPT Business Governance Auditor connector against the isolated
  Supabase project `dcd-governance-mailbox` (OAuth Server authorization path).
- Grants access only to the Governance mailbox MCP (list pending audits, read one package, submit one ruling).
- Contains no secrets. The only key is the project's **publishable** browser key. No server, no build, no Actions.
