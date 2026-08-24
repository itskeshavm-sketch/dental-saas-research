# HIPAA Compliance Gaps in Dental Scheduling

## Regulatory Context

HIPAA compliance for dental practice management software (PMS) is not achieved by the software alone - it requires a combination of vendor capabilities and practice-managed security controls.

## Required Software Safeguards

### Technical Safeguards (vendor must support)

| Safeguard | Requirement |
|----------|------------|
| Unique User Identification | No shared logins; individual authentication |
| Role-Based Access Control (RBAC) | Granular permissions per role |
| Automatic Session Timeouts | Idle disconnection |
| Audit Logs | Track record views, edits, access |
| Encryption (data at rest) | AES-256 |
| Encryption (data in transit) | TLS 1.2+ |
| Business Associate Agreement (BAA) | Mandatory signed agreement |

### Practice-Managed Controls (the actual gap layer)

| Control | Responsibility |
|---------|---------------|
| Workstation security | Full-disk encryption, screen locks |
| Workforce training | Annual / recurring |
| Risk assessments | Annual |
| MFA on all accounts | Practice-owned |
| Secure, tested, immutable backups | Practice-owned |

## The Critical Gap: Workflow Automation Platforms

| Platform | HIPAA BAA? | Notes |
|--------|-------------|-------|
| Zapier | No | Not HIPAA-compliant; does not sign BAAs; never use for PHI |
| Make (Integromat) | No | Not HIPAA-compliant; does not sign BAAs; never use for PHI |
| Microsoft Power Automate | Yes (select plans) | HIPAA-compliant with BAA add-on |
| Self-hosted n8n | Yes (practice-owned) | Full control; practice signs own BAA |
| Keragon | Yes | Healthcare-specific; HIPAA BAA |

### Why Zapier/Make Are Disqualified

- Neither signs Business Associate Agreements (BAAs).
- PHI in workflows (patient names, medical records, insurance details) - non-compliance risk.
- Dental scheduling workflows inherently involve PHI (patient name, appointment type, treatment context).

**Primary monetization angle:** Practices that want to automate scheduling but must stay HIPAA-compliant have no good low-cost option today. Zapier and Make dominate general workflow automation but are blocked from healthcare PHI use cases.

## Gap Summary

1. Legacy dental PMS (Dentrix, Curve, DentiMax) can sign BAAs but scheduling automation is Level 1-2 (notification-only, manual reconciliation). No Level 4-5 real-time bidirectional sync.
2. General workflow automation (Zapier, Make) is cheap and powerful but cannot be used for PHI - blocks the core dental scheduling use case.
3. Healthcare workflow (Power Automate, n8n, Keragon) can sign BAAs but is expensive, complex, and not dental-domain-specific.

**Opportunity:** Build a HIPAA-compliant (BAA on file), dental-domain-specific workflow automation platform that delivers Level 4-5 scheduling integration at $99-$499/mo - bridging the gap between legacy dental PMS and non-compliant general automation.

## Sources

HIPAA technical safeguard requirements (encryption, RBAC, audit logs, BAA) and Zapier/Make BAA ineligibility - web search results.