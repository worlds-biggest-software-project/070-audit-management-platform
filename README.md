# Audit Management Platform

> Part of the [worlds-biggest-software-project](https://github.com/worlds-biggest-software-project) initiative.
>
> An open-source, AI-native platform for internal audit planning, evidence collection, and findings management aligned to IIA Standards.

The Audit Management Platform gives internal audit teams a full engagement lifecycle workspace — audit universe, planning, fieldwork, workpapers, findings, and follow-up — built around continuous, AI-assisted assurance. It is designed for Chief Audit Executives, internal audit managers, and IT audit leads at mid-market and enterprise companies who currently rely on SharePoint, Excel, and email, or who cannot justify the $30K–$150K+ annual cost of incumbents like AuditBoard, TeamMate+, or Workiva.

---

## Why Audit Management Platform?

- **No production-quality OSS option exists.** The entire dedicated audit management market is proprietary; adjacent OSS tools like Eramba (GPL v3) treat audit as a sub-function of GRC and lack workpaper depth, time tracking, and IIA methodology alignment.
- **Incumbents price out the mid-market.** AuditBoard starts at ~$30K/year, TeamMate+ at ~$19K/year, and MetricStream and Workiva commonly exceed $50K–$300K/year — out of reach for internal audit teams of 2–10 auditors who still have genuine SOX, ISO 27001, and IIA obligations.
- **Most platforms still operate on annual cycles.** Continuous control monitoring between formal engagements is nascent outside AuditBoard Accelerate; mid-market teams have no affordable path to continuous assurance.
- **AI capabilities lag in legacy tools.** TeamMate+, Eramba, and most enterprise GRC suites have no agentic or document-intelligence features as of 2026, leaving auditors to draft findings, build scoping memos, and reconcile evidence by hand.
- **IIA, COSO, and PCAOB frameworks are public.** Audit workflow logic is well-understood and unencumbered, making a permissively licensed Apache/MIT alternative feasible without IP risk.

---

## Key Features

### Audit Universe & Planning

- Risk-scored audit universe with entity prioritisation and cyclical coverage tracking
- Annual and rolling audit plan builder with capacity and resource allocation
- AI-assisted scoping memos generated from prior workpapers and current risk profile
- Multi-year forecasted plan support with professional-judgement overrides
- Audit committee and board-level reporting dashboards with plan status and open findings

### Engagement Lifecycle & Workpapers

- Structured audit lifecycle: planning, opening meeting, fieldwork, review, reporting, close, follow-up
- Workpaper management with templates, electronic review, sign-off, and version control
- Risk and control matrix (RCM) documentation linked to audit scope
- Time and resource tracking integrated with engagement and plan records
- Role-based access for CAE, audit manager, senior auditor, staff auditor, auditee, and executive read-only

### Findings, CAPs & Reporting

- Finding lifecycle management: observation, severity, root cause, management response, remediation, verification
- Corrective action plan (CAP) tracking with owner assignment and due-date escalation
- Configurable audit report generation and distribution from structured findings data
- IIA Standards (IPPF), COSO, ISO 19011, and SOX 302/404 alignment built into workflow defaults
- External auditor collaboration portal for evidence request, exchange, and sign-off

### AI-Powered Fieldwork

- Natural-language findings drafting: LLM-generated observation, root cause, and recommendation text for auditor review
- Automated population testing and statistical sampling from uploaded data files
- Document intelligence converting walkthrough notes and interview transcripts into structured workpaper narratives
- Continuous monitoring module for journal entry anomalies, segregation-of-duties violations, and unusual approval patterns

### Integrations & Standards Mapping

- REST API and SSO via SAML 2.0 and OIDC
- Connectors for ERP (SAP, Oracle, NetSuite), HRIS, and cloud infrastructure for evidence collection
- Framework mapping for NIST SP 800-53, ISO 27001, COSO, and SOX
- Optional analytics library for population testing, Benford's Law, duplicate detection, and gap testing

---

## AI-Native Advantage

AI shifts internal audit from a periodic, labour-heavy exercise to continuous, evidence-driven assurance. The platform uses AI agents to ingest financial, operational, and access-log data from connected systems, run statistical sampling and anomaly detection, and surface emerging risks in the audit universe before they become material findings. LLM assistance drafts IIA-standard observations, root cause analyses, and recommendations from structured engagement data — research suggests this can reduce fieldwork time by 40–60% relative to manual workflows. Between formal engagements, continuous control tests run automatically against journal entries, SoD configurations, and approval patterns, giving CAEs real-time signals rather than annual snapshots.

---

## Tech Stack & Deployment

The platform is intended to support self-hosted and cloud deployment, with a permissive Apache 2.0 or MIT licence model so it can serve both regulated enterprises and mid-market teams. Integration is REST-API-first, with SSO via SAML 2.0 and OIDC, LDAP/Active Directory authentication, and connectors for major ERP, HRIS, ITSM, and cloud platforms. Methodology defaults align to the IIA International Professional Practices Framework (IPPF), COSO, ISO 19011, NIST SP 800-53, and ISO 27001, all of which are public standards.

---

## Market Context

The global audit management software market was valued at $1.92B in 2025 and is projected to reach $3.39B by 2029 at a 15.3% CAGR (Persistence Market Research), with the broader audit software market forecast to hit $9.78B by 2032 (Market Research Future). Incumbent pricing ranges from ~$19K/year (TeamMate+) and ~$30K/year (AuditBoard entry) up to $100K–$300K+/year for MetricStream, Workiva, and SAP GRC. Primary buyers are Chief Audit Executives at public companies, internal audit managers at mid-market firms, IT audit leads, and Big 4 / consulting audit teams.

---

## Project Status

> This project is in the **research and specification phase**.  
> Contributions, feedback, and domain expertise are welcome.

---

## Contributing

We welcome contributions from developers, domain experts, and potential users.
See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

**Important:** All contributions must be your own original work or clearly attributed
open-source material with a compatible licence. Copyright infringement and licence
violations will not be tolerated and will result in immediate removal of the offending
contribution. If you are unsure whether a piece of code, text, or other material is
safe to contribute, open an issue and ask before submitting.

---

## Licence

Licence to be determined. See [discussion](#) for context.
