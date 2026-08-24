# Pricing Validation — WhatsApp Local Business

**Status:** verified (web search, 2026-08-24) + framework applied

## The problem with today's stack
- Free app = $0 but hard-capped and automation-less.
- First paid rung = WATI $49 or ManyChat $29 — PLUS Meta per-message fees (marketing/utility/authentication, country-tiered). Free customer-support replies end Oct 1, 2026.
- A 2,000-message month (common for a busy local shop doing COD confirmations + order updates) adds $40–$120 in Meta fees on top of the platform fee — i.e. the platform fee is often the smaller half of the bill.

## Proposed tier framing (vs incumbents)
| Tier | Target | Monthly price (proposed) | Covers | vs incumbent |
|---|---|---|---|---|
| Starter | Solo shop outgrowing free app | $9 | Catalog + basic auto-reply + 500-msg billing cap | Beats storefront overlays ($9–49); no free-app broadcast cap |
| Growth | Growing local shop (2–10 staff) | $29 | Shared inbox, team assignment, catalog, order board, light CRM sync, no per-message Meta surcharge (within cap) | Undercuts WATI ($49+Meta) / ManyChat ($29+Meta) on predictability |
| Pro | Multi-location (10+ locations) | $49 | Multi-number dashboard, RBAC, analytics, export, higher caps | Cheaper than per-location WATI/ManyChat stacking |

## Key pricing moat
- No Meta per-message pass-through is the value proposition, not a lower platform fee. A shop paying WATI $49 + $80 Meta fees pays us $29 + $0 -> same or lower headline, far more predictable.
- Cap monthly messages (e.g. 5k / 10k / 25k) and absorb Meta fee risk into our margin so the merchant gets a flat bill.

## Validation questions for interviews
1. What was your single highest WhatsApp-platform bill in the last 3 months? How much was Meta fees vs platform?
2. At what message volume would a flat $29/mo (no per-message fees) beat your current WATI/ManyChat spend?
3. Would you pay $9/mo for a mobile-friendly catalog + 500-message cap to leave the free app?

## Open item — tier-band conflict
The project's original $99–$499/mo tier band is sized for the dental/DSO market. For WhatsApp local business the competitive ceiling is ~$29–$99 (WATI Pro $99, ManyChat Business $69, Chatfuel $59). A strict $99 entry is non-competitive vs the $29–49 API platforms — and a $499 multi-location tier is hard to justify vs WATI Enterprise at ~$299.

**Recommendation (flagged to Finch):** align the WhatsApp SKU to $9/$29/$49 tiers, and treat the $99–$499 band as the multi-account/anchor model (per-location seat under a head-enterprise account) — not a per-shop entry ceiling.
