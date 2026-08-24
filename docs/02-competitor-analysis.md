# Competitor Analysis — Dental Practice Scheduling

## Market Landscape

The dental PMS market is dominated by established players with legacy server-based deployments and recent cloud migrations. All use custom quoting (opaque pricing).

## Competitor Profiles

### 1. Dentrix (Henry Schein One)

| Attribute | Detail |
|-----------|--------|
| Ownership | Henry Schein One |
| Deployment | Server-based + cloud (Ascend) |
| Strengths | Industry standard, deep clinical charting, extensive 3rd-party integrations, robust insurance billing |
| Pricing | $300-$1,000/mo + $10k-$30k upfront (on-prem); $500-$1,500/mo/location (Ascend cloud) |
| Integration depth | Middleware/Gateway for cloud; database-level scraping historically for legacy |

### 2. Curve Dental

| Attribute | Detail |
|-----------|--------|
| Deployment | Cloud-native |
| Strengths | Minimal IT maintenance, 24/7 support, all-in-one, no separate clearinghouse/engagement fees |
| Pricing | $500-$1,500/mo/location |
| Integration depth | Cloud-native API; modern but closed ecosystem, limited 3rd-party workflow automation |

### 3. DentiMax

| Attribute | Detail |
|-----------|--------|
| Deployment | Cloud + on-prem hybrid |
| Strengths | Budget-friendly entry point |
| Pricing | $169-$669/mo |
| Integration depth | Limited workflow automation; basic 3rd-party sync |

## Scheduling Automation Gap Analysis

Per research, dental scheduling automation vendors commonly offer Level 1-2 connectivity = notifications only (email/SMS to staff), which shifts workload rather than eliminating it.

Effective automation requires Level 4-5 integration: bidirectional, real-time synchronization where AI reads live schedule availability and writes appointments directly into the PMS without manual reconciliation.

### Verification Criteria (for evaluating any scheduling automation vendor)

| # | Criterion | Why |
|---|----------|-----|
| 1 | Supported real-time API (open API / Middleware Gateway), not DB scraper | Reliability, compliance, no data corruption |
| 2 | Live demo on prospects exact system/version in <5 min | Proves real integration, not canned demo |
| 3 | Respects practice logic (provider rules, operatory constraints, appt durations) | Avoids double-booking/conflicts |

**Finding:** No major dental PMS vendor today offers a transparent, HIPAA-compliant scheduling automation tier at the $99-$499/mo price band with Level 4-5 criteria. Legacy vendors bundle scheduling as a PMS feature, not a workflow automation product.

## Competitive Positioning Opportunity

| Vendor | HIPAA BAA | Transparent Pricing | Workflow Automation | Price Band |
|--------|-----------|---------------------|---------------------|------------|
| Dentrix | Yes (BAA available) | No ($300-$1,500+) | No (Level 1-2) | $$ |
| Curve Dental | Yes | No ($500-$1,500/location) | No (Level 1-2) | $$ |
| DentiMax | Partial | Partial ($169-$669) | No (Level 1-2) | $ |
| New entrant | Yes (built-in) | Yes ($99-$499) | Yes (Level 4-5) | $-$$ |