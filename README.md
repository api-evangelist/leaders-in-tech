# Leaders In Tech

Leaders In Tech (LIT) is a leadership accelerator for startup founders and technology executives,
founded in 2015 and part of the Y Combinator Summer 2015 batch. Based in San Francisco, it runs
cohort-based fellowship programs grounded in experiential, feedback-rich learning — the Founder
Fellows Program (10 months, Series A to pre-IPO), the Grove Fellows Program (6 months, pre-seed and
seed), and the Executive Fellows Program (6 months, senior leaders) — plus corporate workshops and
retreats. Its primary teaching methodology is T-groups, brought from the Stanford Graduate School of
Business by co-founder Dr. Carole Robin. LIT reports more than 350 alumni founders running companies
valued at over $75B.

- Website: https://www.leadersintech.org/
- Y Combinator: https://www.ycombinator.com/companies/leaders-in-tech (S15, San Francisco, active)
- Contact: hello@leadersintech.org

Backed by: y-combinator

## API surface: none

Leaders In Tech is a leadership-development organization, not a software or API provider. Probed
2026-07-19:

- No `api`, `docs`, `developer`, `developers`, `app` or `status` subdomain resolves (all NXDOMAIN).
- `/.well-known/security.txt`, `/.well-known/openid-configuration`,
  `/.well-known/oauth-authorization-server`, `/.well-known/api-catalog`,
  `/.well-known/ai-plugin.json`, `/llms.txt` and `/openapi.json` all return 404.
- No developer portal, documentation, API reference, SDK, CLI, changelog, status page or public
  Postman surface exists.

No API-oriented artifacts (OpenAPI, packages, MCP, skills, scopes, conventions, errors, lifecycle)
were produced, because there is nothing real to ground them in.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| Domain security | `security/leaders-in-tech-domain-security.yml` | probed |
| Well-known (negative result) | `well-known/leaders-in-tech-well-known.yml` | searched |
| llms.txt | `llms/leaders-in-tech-llms.txt` | generated |
