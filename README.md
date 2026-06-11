# CaseStack — offer page

Single static page. No framework, no build step, no JS.

## Deploy (2 minutes)

Drag this whole folder onto https://app.netlify.com/drop — done.
Point your domain (casestack.tools / casestack.io — verify availability at checkout) at it afterward in Netlify's domain settings.

## Before you ship — find/replace these

| Placeholder | Where | Replace with |
|---|---|---|
| ~~Calendly link~~ | done | https://calendly.com/rhowardstone/30min |
| ~~Photo~~ | done | assets/rye.jpeg |
| ~~Stripe link~~ | done | https://buy.stripe.com/28EdRb1xa411cLw5XPdIA00 (prod_UgWex6Og4jtumN) |
| `$400` / `from $1,500` | pricing tiers | confirm after running the price-sanity prompt |

## Notes

- The Exhibit A terminal block is static. The weekend upgrade: wire it to the
  live epstein-data.com Datasette JSON endpoint so visitors can run a real
  query. Host-agnostic client-side fetch — Netlify is fine.
- The 78,000-removed-documents numbers in Exhibit A are from your real finding;
  tighten the wording to match exactly what you published before shipping.
