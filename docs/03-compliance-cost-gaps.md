# Compliance, Cost & Feature Gaps — WhatsApp Local Business

*(Originally the HIPAA-compliance doc; HIPAA is irrelevant here. Reframed to the gaps that matter for local shop owners.)*

**Status:** verified (web search, 2026-08-24)

## Gap 1 — Per-message cost explosion (the big one)

- As of **July 1, 2025**, WhatsApp moved from conversation-based to **per-message billing** (marketing / utility / authentication tiers, priced by country).
- As of **Oct 1, 2026**, **free customer-support replies end globally** — every delivered message becomes a paid Meta fee.
- API platforms (WATI, ManyChat, Chatfuel, Twilio) **pass these fees through**. A shop growing from 500 → 5,000 monthly customer messages sees Meta fees grow ~10× while the platform fee stays flat.
- **Result:** total cost is **unpredictable** and dominated by message volume the shop cannot control (COD confirmations, order updates, support).

## Gap 2 — Data lock-in + portability

- WhatsApp is the merchant’s only customer channel, yet no API platform offers easy export of customer message/commerce history back to the merchant’s own CRM.
- Switching platforms = losing conversation history and the customer relationship thread → high switching cost, but also a gap an open-data model can own.

## Gap 3 — GDPR / payment (PCI) exposure for local commerce

- Many local shops collect payments/personal data *inside* WhatsApp chat (COD, bank transfer, delivery address).
- The free app and most API overlays provide **no PCI path** and **no GDPR export/delete workflow** — the shop owner is personally on the hook.
- A tool that bakes in **data-retention, export, and a PCI-light (payment-link, not card data in chat) flow** would address a real regulatory pain.

## Gap 4 — Free-app automation hard ceiling

- The WhatsApp Business App supports only **static** greeting + away messages.
- No scheduling, no drip sequences, no “cart-abandoned” reminder, no order-status flow, no catalog auto-sync to a web listing.
- Shops wanting even basic automation must jump straight to a $49–99/mo API platform + per-message fees — a steep, non-linear jump from $0.

## Opportunity framing

| Gap | Who suffers | What wins |
|---|---|---|
| Per-message fees | Growing shops | Flat monthly price, no Meta pass-through |
| No shared inbox | 2–10 staff | Native shared inbox + team assignment |
| No CRM sync | Repeat-customer shops | Light CRM sync (Google Sheets / simple CRM) |
| Free-app plateau | Everyone outgrowing solo | Bridge tier between $0 and $49/mo |
| Data lock-in | All API-platform users | Exportable customer/chat history |

**Bottom line:** the defensible wedge is a **WhatsApp-native, predictable-monthly, no-per-message-surcharge** tool that adds the shared inbox + catalog + light automation a shop needs when it outgrows the free app — without the bill shock of the API platforms.