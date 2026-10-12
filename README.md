# 🛡️ Compliance Health Check & Assurance
### Continuous Vendor Verification • Regulatory Intelligence • Evidence-Backed Risk Management

**Subtract Architect Studios** | *Intelligence by Subtraction*

> **Your vendors may have been compliant when you hired them. Are they compliant today?**
>
> **VERIFY BEFORE YOU TRUST. MONITOR AFTER YOU HIRE.**
>
> **Choose your vendors wisely. Verify indiscriminately.**

---

## The mission

A license can expire. Insurance can lapse. Regulations can change. A subcontractor can introduce risk that was never assessed during onboarding.

**Compliance Health Check & Assurance** is a vendor due-diligence and continuous-assurance program designed to help organizations **discover, verify, document, monitor, alert, remediate, and report** on relevant vendor obligations.

We aim to replace scattered spreadsheets, stale certificates, unsupported assurances, and last-minute surprises with **source-backed findings, accountable follow-up, and clear decision support**.

**Current status:** Program design / service-launch blueprint. This repository describes proposed processes and deliverables; it does **not** claim that live integrations, automated monitoring, legal certification, or a production dashboard already exist.

## What makes this different?

- **Verification, not blind trust.** Prefer authoritative records and direct issuer confirmation over self-attestation alone.
- **Continuous oversight, not a one-time checkbox.** Recheck according to risk, source availability, and renewal schedules.
- **Jurisdiction-aware.** Map obligations to the vendor's activities, locations, industries, and contracts.
- **Evidence or uncertainty.** Show the source, observation date, scope, and limitations for each finding.
- **Actionable remediation.** Track ownership, deadlines, responses, and verified closure.
- **Proportionate intelligence.** Apply **Negative Step Zero**: determine whether a check is actually necessary before adding tools, compute, or bureaucracy.
- **Human accountability.** Require qualified review for ambiguous records, material adverse findings, and legal interpretations.

## 15 core compliance domains

| # | Domain | Representative checks |
|---|---|---|
| 01 | Business registration | Secretary of State status, foreign registration, registered agent, available good-standing records |
| 02 | Professional licensing | Contractor and regulated trade/professional credentials; license status and scope |
| 03 | Insurance | General liability, workers' compensation, auto, E&O, cyber; dates, limits, endorsements where relevant |
| 04 | OSHA & workplace safety | Public inspection/enforcement records and vendor-provided safety/training evidence |
| 05 | Federal regulations | Applicable labor, environmental, transportation and sector-specific obligations |
| 06 | State regulations | State licensing, registrations, renewal requirements and enforcement records |
| 07 | Local/municipal | Permits, inspections, local licensing and applicable ordinances |
| 08 | Cybersecurity | Policies, access controls, vulnerability management, incident response and supporting evidence |
| 09 | AI governance | AI use, oversight, data handling, model/vendor risk and applicable AI obligations |
| 10 | Data privacy | Applicable privacy obligations, processing terms, safeguards and breach procedures |
| 11 | Industry certifications | ISO certificates, SOC 2 reports, accreditation status, dates and **scope** |
| 12 | Financial/legal standing | Available bankruptcy, litigation, liens and other relevant public-risk indicators |
| 13 | Environmental | EPA/state enforcement, permits, hazardous-waste and relevant environmental requirements |
| 14 | Employment/labor | Wage/hour, workers' compensation, enforcement records and relevant policy evidence |
| 15 | Government contracting/exclusions | SAM.gov, federal exclusions, debarment and applicable procurement requirements |

**Verification boundary:** Public records can often be independently checked. Insurance terms, internal security controls, personnel training and private records may require vendor cooperation, direct issuer confirmation, contractual rights or specialized audits. A missing public record is **not automatically proof of noncompliance**.

## Industry-specific assurance

| Industry | Additional focus |
|---|---|
| Property management | Trade licenses, insurance, lead-safe credentials, permits, fire safety, subcontractors |
| Construction | Bonding, OSHA history, prevailing wage, permits, subcontractor insurance |
| Healthcare | Professional licensing, OIG exclusions, credentialing, HIPAA-related safeguards |
| Transportation | DOT/FMCSA authority, safety history, commercial insurance, driver qualifications |
| Restaurants & hospitality | Health permits, food-safety credentials, fire inspections, liquor licenses |
| Technology & SaaS | SOC 2, ISO 27001, privacy, cyber controls, subprocessor and AI risk |
| Financial services | Registrations, AML controls, sanctions screening and security obligations |
| Government contracting | SAM status, exclusions, procurement clauses and contractual cyber requirements |

## The seven-stage assurance cycle

```text
DISCOVER → VERIFY → DOCUMENT → MONITOR → ALERT → REMEDIATE → REPORT
    ↑                                                       |
    └───────────── review / reassess / improve ──────────────┘
```

1. **DISCOVER** — Identify vendors, subcontractors, activities, jurisdictions and applicable requirements.
2. **VERIFY** — Consult authoritative registries, regulators, issuers and supplied documentation.
3. **DOCUMENT** — Preserve evidence references, timestamps, expiry dates, methodology and unresolved questions.
4. **MONITOR** — Schedule proportionate rechecks for changes, renewals and regulatory developments.
5. **ALERT** — Surface relevant expirations, adverse changes, gaps and evidence-staleness risks.
6. **REMEDIATE** — Assign corrective actions, request proof and independently verify closure where feasible.
7. **REPORT** — Deliver a scoped, timestamped assessment with trends, outstanding risks and an audit trail.

### Decision statuses

| Status | Meaning |
|---|---|
| 🟢 **VERIFIED** | Defined, applicable checks passed with current supporting evidence |
| 🟡 **ACTION REQUIRED** | Missing/expiring documentation or an issue requiring follow-up |
| 🔴 **NONCOMPLIANT** | Evidence establishes a specific applicable requirement is unmet, subject to appropriate review |
| ⚪ **UNVERIFIED** | Insufficient evidence to reach a defensible determination |

Statuses apply **per requirement and assessment scope**, not as blanket certification of an entire vendor. Keep **not applicable** separate from unverified; do not treat silence as failure.

## Evidence standard: make every finding defensible

Each check should capture:

```text
Vendor / legal entity:
Jurisdiction / applicable requirement:
Check / assessment scope:
Authoritative source / evidence URL or document reference:
Source record identifier:
Observed fact:
Checked at (UTC):
Evidence valid through / next review:
Status: VERIFIED | ACTION REQUIRED | NONCOMPLIANT | UNVERIFIED | NOT APPLICABLE
Confidence / limitations:
Reviewer and review date:
Remediation owner / due date:
Reverification result:
```

**No fabricated checks. No implied live monitoring. No unsupported guarantees.** Distinguish an official-source observation from a vendor claim, an inference, and an unresolved question. Record contradictory evidence and give vendors a documented opportunity to correct inaccuracies.

## Negative Step Zero × bellaOS × Sentinel

Before executing a compliance workflow, ask:

1. **Is this requirement applicable to this vendor, activity, jurisdiction and contract?**
2. **Is the information already current and independently supported?**
3. **Can an upstream process change eliminate repeated checks or missing-document churn?**
4. **What is the lowest-cost reliable verification route?**
5. **What must be escalated to a human, regulator, issuer or qualified specialist?**

**Planned architecture:** bellaOS may orchestrate efficient routing, caching, evidence freshness and human review; Sentinel may enforce permissions, integrity checks, auditability and containment. **These are integration goals, not claims of deployed functionality.** Avoid collecting unnecessary sensitive information and never commit client evidence, credentials, or private reports to a public repository.

## Commercial offering (illustrative launch pricing)

| Service | Indicative monthly fee | Proposed coverage |
|---|---:|---|
| **Essential Vendor Verification** | **$149–$299** | Up to 10 vendors; core registrations, licensing, expiration tracking, monthly report |
| **Continuous Compliance Assurance** | **$399–$799** | Up to 25 vendors; broader checks, scheduled monitoring, alerts, remediation |
| **Enterprise Vendor Risk Management** | **Custom, starting around $1,000** | Multi-jurisdiction portfolios, specialized assurance, tailored reporting |

Pricing is **hypothetical**, not validated market pricing. Onboarding, specialized reviews, manual issuer verification and audit work may require separate fees. Monitoring frequency and service levels must be specified in each client agreement.

### Start with a Compliance Health Check

**One-time baseline assessment → prioritized findings → corrective-action plan → optional recurring monitoring.**

Initial target customers: **property management companies, general contractors, commercial landlords and facilities managers**, beginning in **Concord, Nashua, Manchester and Hollis, New Hampshire**.

A useful entry offer is a tightly scoped assessment of existing vendors—**no need to replace trusted providers just to verify their credentials**.

## Deliverables we intend to standardize

- Vendor intake and jurisdiction/requirement mapping
- Evidence register and verification checklist
- Risk-ranked compliance health-check report
- Expiration calendar and reassessment schedule
- Vendor scorecard with transparent assessment scope
- Alert and remediation tracker
- Client-ready monthly assurance summary
- Documented disputes, corrections and review history

## Implementation roadmap

- **Phase 0 — Service definition:** Finalize scopes, evidence rules, disclaimers, pricing tests and intake questions.
- **Phase 1 — Manual MVP:** Verify a small, consented pilot vendor set using authoritative records and produce reviewed reports.
- **Phase 2 — Repeatable operations:** Add templates, source catalogs, renewal schedules, QA and client feedback.
- **Phase 3 — Controlled automation:** Introduce permitted integrations, caching, change detection, secure storage and human approval gates.
- **Phase 4 — Scale:** Add industry/jurisdiction packs, dashboards, multi-client access controls and audited reliability metrics.

**Acceptance criteria before claiming a feature is live:** reproducible tests, source provenance, permission review, failure handling, defined monitoring intervals, data retention controls, and demonstrated end-to-end results.

## Important limitations

This service provides **due diligence and compliance-risk intelligence**, not legal advice, an official government determination, or a guarantee of regulatory compliance. Laws vary by jurisdiction and may change. SOC 2 is an attestation report rather than a certification; ISO certification must be checked for the relevant entity, scope and validity. OSHA and enforcement records require context. Use qualified professionals where legal, insurance, security or regulatory conclusions demand it.

**Peace of mind should come from verifiable evidence—not promises of zero risk.**

---

## Work with Subtract Architect Studios

**Continuous oversight. Documented evidence. Greater peace of mind.**

**Subtract Architect Studios** — *Intelligence by Subtraction*

- Website: https://subtractarchitect.com
- Email: michael@subtractarchitect.com

> **Don't wait until something goes wrong to discover something was wrong.**
>
> **VERIFY BEFORE YOU TRUST. MONITOR AFTER YOU HIRE.**
