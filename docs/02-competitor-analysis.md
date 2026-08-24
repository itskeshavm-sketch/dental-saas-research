# Competitor Analysis — WhatsApp Local Business Stack

**Status:** verified (web search, 2026-08-24)

## 1. WhatsApp Business App (the on-ramp / baseline)

- **Model:** free mobile app; 1 phone + up to 4 linked devices.
- **Cap:** 256-contact broadcast lists.
- **Strengths:** built-in product Catalog, quick replies, greeting/away messages, one-tap templates.
- **Gaps (the pain):**
  - **No shared inbox** / team collaboration → teams share devices/credentials (security risk).
  - **No conversation assignment/routing** → duplicate or missed replies.
  - **No scheduling, drip sequences, or advanced chatbot flows** → only static greeting/away.
  - **No CRM / software sync** → manual data entry.
  - **No analytics** beyond read receipts.
- **Upgrade trigger:** “I’m losing sales because my teammate and I both replied / I can’t broadcast past 256 / I need a catalog link to share.”

## 2. WATI (WhatsApp-first specialist)

- **Plans:** Starter $49/mo, Pro $99/mo, Enterprise ~$299/mo+ (contact-volume dependent).
- **Plus:** **Meta per-message fees** on top (marketing/utility/authentication; free support replies end Oct 1, 2026).
- **Strengths:** native shared inbox, team assignment, native **Shopify** integration (order updates, abandoned carts), COD-confirmation flows, WhatsApp-native.
- **Gaps:** marketer-first UI; per-message-cost unpredictability; not catalog/storefront-native.

## 3. ManyChat (cross-channel)

- **Plans:** Pro $29/mo (≤2,500 contacts), Business $69/mo (+ per-contact overages).
- **Plus:** **Meta per-message fees** on top.
- **Strengths:** IG + FB + WhatsApp unified inbox; best-in-class social → purchase funnels; native Shopify abandoned-cart recovery.
- **Gaps:** less WhatsApp-native; weaker shared-inbox/team features vs WATI; cost balloons past 2.5k contacts.

## 4. Chatfuel (Meta → AI support focus)

- **Plans:** Fuely Super $39/mo / Fuely Max $59/mo (150 active contacts each).
- **Plus:** **Meta per-message/conversation fees** on top.
- **Strengths:** GPT-4 autonomous AI agents; good for support bots.
- **Gaps:** poor native Shopify/e-commerce depth; leans on Zapier for store integrations; contact-based cap.

## 5. Twilio (developer / raw-API)

- **Model:** $0 platform fee; pay per-message + number rental.
- **Strengths:** maximum flexibility; no per-seat cap.
- **Gaps:** no UI; you build the inbox/automation yourself → needs engineering; Meta fees still apply.

## 6. Storefront / catalog overlays (no-API)

- Tools: **Shoply, WaveOrder, Lofaz, Whatsell, eCatalog**.
- **Model:** typically **$9–49/mo** platform fee to add a catalog/storefront/chat-to-cart on top of the existing WhatsApp number.
- **Strengths:** cheaper than API platforms; no per-message surcharge; built for shop owners, not devs.
- **Gaps:** mostly storefront/catalog; weak automation/shared-inbox; fragmented ecosystem (no single leader).

## Competitive matrix

| Tool | Shared inbox | Catalog/Storefront | Automation | CRM sync | Per-message Meta fee | Entry |
|---|---|---|---|---|---|---|
| WhatsApp Business App | ❌ | ✅ (basic) | ❌ (static only) | ❌ | ❌ | $0 |
| WATI | ✅ | ✅ | ✅ | ✅ | ✅ | $49 |
| ManyChat | ✅ | ✅ | ✅ | ✅ | ✅ | $29 |
| Chatfuel | ✅ | ❌ | ✅ (AI) | ❌ | ✅ | $39 |
| Twilio | (build) | (build) | (build) | (build) | ✅ | $0 |
| Storefront overlays | ❌ | ✅ | ❌ | ❌ | ❌ | $9–49 |

## Insight

Every paid API platform (WATI, ManyChat, Chatfuel, Twilio) **passes Meta’s per-message fees through to the merchant** — on top of a platform fee. There is **no** mainstream WhatsApp-native tool that gives a growing local shop a **shared inbox + catalog + light automation + CRM sync at a flat monthly price with no per-message surcharge**. That is the wedge.