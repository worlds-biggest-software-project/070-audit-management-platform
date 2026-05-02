# Audit Management Platform — Feature & Functionality Survey

> Candidate #70 · Researched: 2026-05-02

## Solutions Analysed

| Tool | Type | Licence / Model | URL |
|------|------|-----------------|-----|
| AuditBoard | Commercial SaaS | Proprietary / subscription | https://www.auditboard.com |
| Wolters Kluwer TeamMate+ | Commercial SaaS / on-prem | Proprietary / subscription | https://www.wolterskluwer.com/en/solutions/teammate |
| Workiva | Commercial SaaS | Proprietary / subscription | https://www.workiva.com |
| MetricStream | Commercial SaaS | Proprietary / custom enterprise | https://www.metricstream.com |
| Diligent (HighBond / Galvanize) | Commercial SaaS | Proprietary / enterprise | https://www.diligent.com |
| DataSnipper | Commercial SaaS | Proprietary / per-user | https://www.datasnipper.com |
| Sprinto | Commercial SaaS | Proprietary / subscription | https://sprinto.com |
| SAP GRC Audit Management | Commercial (SAP ecosystem) | Proprietary / SAP licence | https://www.sap.com/products/financial-management/grc.html |
| Eramba | Open Source / freemium | GPL v3 (Community) | https://www.eramba.org |
| OpenCRE | Open Source | CC BY 4.0 (content) | https://www.opencre.org |

## Feature Analysis by Solution

### AuditBoard

**Core features**
- Audit universe and risk-based audit planning with annual and rolling plan management
- Workpaper management with structured templates, sign-off workflows, and version control
- Risk and control matrix (RCM) management with SOX 302/404 support
- Finding management with severity classification, management response, and corrective action tracking
- Audit report generation and distribution
- Issues and action item follow-up tracking with owner assignment and due-date alerts
- ESG and operational audit workflows
- IT audit and cybersecurity audit workflows aligned to NIST and ISO 27001

**Differentiating features**
- AuditBoard Accelerate: enterprise-grade AI solution delivering natural-language workflows, continuous auditing and monitoring, document intelligence, and agentic AI
- Audit Agent: AI automates control testing and documentation cycles, uses risk-based sampling to select representative samples, reducing weeks of fieldwork to hours
- Document Intelligence: converts raw interview notes and walkthrough documentation into structured, audit-ready workpapers and cross-audit narratives automatically
- AI Scoping Memos: analyses audit scope and generates a detailed, structured planning memo incorporating risks, key processes, and work steps automatically
- Continuous monitoring between formal engagements — journal entry anomalies, segregation-of-duties violations, and unusual approval patterns surfaced in real time

**UX patterns**
- Modern, card-based dashboard with programme health metrics and open action items
- In-platform collaboration with comment threads, task assignments, and @mentions
- Board and audit committee reporting view with configurable risk and findings dashboards
- Mobile-responsive interface for auditee interactions and evidence submission

**Integration points**
- 300+ integrations with ERP (SAP, Oracle, NetSuite), HRIS, cloud infrastructure, and GRC platforms
- Native integration with Workday, Salesforce, and major ITSM tools
- REST API for custom data pipelines and evidence ingestion
- SSO via SAML 2.0 and OIDC

**Known gaps**
- Expensive for smaller internal audit teams (entry ~$30K/yr); pricing escalates with modules and users
- Some advanced AI features in Accelerate require additional licensing
- Less depth for external audit (public accounting firm) use cases

**Licence / IP notes**
- Fully proprietary; acquired by Hg Capital (2024) at $3B+ valuation
- No open-source components

---

### Wolters Kluwer TeamMate+

**Core features**
- Risk-based audit universe management with risk scoring and cyclical planning
- Workpaper management with electronic review, sign-off, and archiving
- Time and resource tracking for audit staff
- Finding lifecycle management with root cause classification and remediation tracking
- IIA Standards alignment with built-in methodology guidance
- External quality assessment (EQA) support module
- Automated audit report generation from structured findings data

**Differentiating features**
- Multi-Year Audit Planning (launched 2026): automates and optimises forward audit scheduling using historical data stored within TeamMate+, allowing multi-year forecasted plans with professional-judgement overrides
- Business Rules Engine (launched 2026): enforces data quality and governance rules on audit data entry, reducing errors in workpaper and finding records
- Long-standing market presence (30+ years) provides deep institutional knowledge of IIA methodology embedded in the platform design

**UX patterns**
- Document-centric workpaper view familiar to experienced auditors trained on paper-based methodologies
- Structured workflow for each audit phase: planning, fieldwork, review, reporting, follow-up
- Dashboard views for audit directors showing plan progress, open findings, and team utilisation

**Integration points**
- REST API for integration with ERP and GRC platforms
- Active Directory and SSO authentication
- CCH Tagetik integration for combined financial close and audit workflows (within Wolters Kluwer portfolio)

**Known gaps**
- UI experience noticeably less modern than AuditBoard; younger auditors often prefer AuditBoard's interface
- AI capabilities lag AuditBoard significantly; no agentic or continuous monitoring features as of 2026
- Less suited for IT audit and cybersecurity audit use cases compared to AuditBoard

**Licence / IP notes**
- Fully proprietary (Wolters Kluwer N.V.)

---

### Workiva

**Core features**
- Connected financial reporting with linked data across financial statements, footnotes, and management commentary
- Audit management with task management, sign-off, and evidence linking
- XBRL and iXBRL tagging for SEC and regulatory filings
- SOX programme management with control documentation and testing evidence
- ESG and sustainability reporting workflows
- Narrative reporting with automatic data refresh from connected spreadsheets and databases

**Differentiating features**
- Data connectivity is the strongest in class: cells in reports are live-linked to source data, so when actuals change, all downstream reports and disclosures update automatically
- Best platform for external reporting and XBRL filing; dominant for public companies preparing SEC submissions
- Workspot AI (acquired 2025): narrative AI that drafts MD&A and disclosure language from structured financial data

**UX patterns**
- Document-centric interface combining spreadsheet grids and word-processing panels in a single view
- Live-link visualisation showing data lineage from source cell to final disclosure
- Collaboration and review workflows with tracked changes and reviewer sign-off

**Integration points**
- Native connections to Oracle, SAP, Workday, and major ERP systems for live data pull
- REST API for custom data integrations
- Microsoft Teams and Slack integration for notification workflows

**Known gaps**
- Broader than audit-only; internal audit management depth is secondary to financial reporting
- Expensive; less suited for companies that don't have an external reporting or XBRL filing requirement
- Limited continuous monitoring or AI-powered fieldwork assistance compared to AuditBoard

**Licence / IP notes**
- Fully proprietary (Workiva Inc., NYSE: WK, ~$4B market cap)

---

### Diligent (HighBond / Galvanize)

**Core features**
- Audit management with planning, fieldwork, and finding lifecycle
- Data analytics and continuous control monitoring (ACL Analytics heritage)
- GRC platform covering risk, policy, compliance, and audit in the Diligent One Platform
- Board governance and director management modules
- Third-party risk management

**Differentiating features**
- ACL Analytics heritage: strongest built-in data analytics capabilities for audit in the market — population analysis, Benford's Law testing, duplicate detection, and statistical sampling built natively
- Board + GRC convergence: unique integration of board governance data with audit and risk management data in a single platform (Diligent One Platform)

**UX patterns**
- Analytics-first audit workflow: auditors can run data queries directly against uploaded populations without exporting to Excel
- Script library with pre-built ACL analytics for common audit procedures (accounts payable, payroll, inventory)
- Post-Galvanize acquisition, platform integration is still consolidating as of 2026

**Integration points**
- Direct data connectors to ERP systems for population data extraction
- Integration with Diligent Boards for audit committee reporting
- REST API for custom integrations

**Known gaps**
- Post-acquisition platform consolidation created UX fragmentation
- Custom pricing with no published rates makes evaluation difficult
- Less modern UX compared to AuditBoard for standard audit lifecycle workflows

**Licence / IP notes**
- Fully proprietary; Diligent Corporation is a private company

---

### DataSnipper

**Core features**
- AI-powered audit automation within Microsoft Excel for external auditors
- Automated cross-referencing between financial statements and supporting evidence
- Document matching: maps amounts in workpapers to source documents (invoices, bank statements, contracts)
- Population extraction and sampling from structured data files
- Completeness and accuracy testing on audit populations

**Differentiating features**
- Excel-native — public accounting firms and external auditors work entirely in Excel; DataSnipper augments the existing workflow rather than replacing it
- AI document matching eliminates the most time-consuming manual reconciliation step in external audit
- Designed specifically for the Big 4 / mid-tier accounting firm audit workflow; highest adoption in that segment

**UX patterns**
- Excel ribbon add-in; auditors never leave Excel
- Side-by-side document and workpaper view with AI-suggested matches
- Team review and sign-off integrated with existing Excel review processes

**Integration points**
- Microsoft 365 integration
- Works with any file type (PDF, Excel, CSV) as evidence source

**Known gaps**
- Not designed for internal audit lifecycle management (planning, universe, CAP tracking)
- Limited to Excel-based workflows; not suitable for organisations moving away from Excel-centric audit
- No continuous monitoring or real-time risk capabilities

**Licence / IP notes**
- Fully proprietary SaaS

---

### Eramba (audit module)

**Core features**
- Internal audit planning module within the broader Eramba GRC platform
- Audit project management with task assignment and status tracking
- Finding and remediation tracking integrated with the risk register
- Control assessment workflows linked to compliance frameworks

**Differentiating features**
- Free Community Edition (GPL v3) with no user limits; viable for resource-constrained internal audit teams
- Risk register integration means audit findings automatically update risk assessments in the same platform
- Battle-tested over nearly two decades of real-world GRC use

**UX patterns**
- Functional but visually dated compared to AuditBoard or TeamMate+
- Navigation follows a GRC-first model (risk and compliance as primary context; audit as a sub-function)

**Integration points**
- REST API (Enterprise Edition)
- LDAP/Active Directory authentication

**Known gaps**
- Audit module is secondary to risk/compliance; lacks workpaper management, time tracking, and IIA methodology depth
- No AI features
- Limited evidence management compared to dedicated audit platforms

**Licence / IP notes**
- GPL v3 (Community); proprietary Enterprise add-ons
- No patent concerns

---

## Cross-Cutting Feature Themes

### Table-Stakes Features
- Audit universe management with risk-scoring-based entity prioritisation and annual plan generation
- Audit engagement lifecycle: planning, opening meeting, fieldwork, review, reporting, close
- Workpaper management with structured templates, electronic review, and sign-off workflows with version control
- Risk and control matrix (RCM) documentation linked to audit scope
- Finding lifecycle management: observation, severity, root cause, management response, remediation, verification
- Corrective action plan (CAP) tracking with owner assignment and due-date escalation
- Audit report generation and distribution with configurable formats
- Time and resource tracking for audit staff
- Audit committee and board-level reporting dashboard
- User roles for CAE, audit manager, senior auditor, staff auditor, auditee, and read-only executive

### Differentiating Features
- AI-powered fieldwork automation: automated control testing, risk-based sampling, and anomaly detection in population data
- Continuous monitoring between formal engagements: journal entry analytics, SoD violation detection, unusual approval pattern flags
- Document intelligence: converting interview notes and walkthrough documentation into structured workpapers automatically
- Natural-language findings drafting: LLM-generated observation, root cause, and recommendation text for auditor review
- AI scoping memo generation: automatic audit scope documentation from risk data
- Data analytics built natively: population testing, Benford's Law, duplicate detection, statistical sampling
- External auditor collaboration portal for evidence exchange and sign-off workflow
- Board governance integration linking audit findings to director-level oversight

### Underserved Areas / Opportunities
- No production-quality open-source internal audit platform exists — the entire market is proprietary
- Mid-market companies (internal audit teams of 2–10 auditors) using SharePoint + Excel + email cannot afford AuditBoard or TeamMate+ but have genuine needs
- Continuous auditing between annual engagements is nascent; most platforms still operate on annual/semi-annual cycles
- IT audit and cybersecurity audit workflow depth (evidence from cloud systems, ITGC testing automation) is underdeveloped in open-source adjacent tools
- Integrated audit-to-risk-register feedback loop (audit findings automatically updating risk register scores) is a gap in standalone audit platforms

### AI-Augmentation Candidates
- AI-assisted audit universe prioritisation: continuously re-ranking audit entities based on financial data, operational metrics, news sentiment, and control test results
- Automated evidence collection and population testing: AI agents querying ERP, HRIS, and access logs, running completeness checks and anomaly tests
- Natural-language findings drafting: generating IIA-standard observation, root cause, and recommendation text from structured audit data
- Continuous control testing: automated running of control assertions between formal engagements, surfacing failures before annual audit
- Document intelligence: converting unstructured walkthrough notes into structured workpaper narratives
- AI scoping and planning: generating audit scopes, programme objectives, and testing steps from prior year workpapers and current risk profile

---

## Legal & IP Summary

All dedicated audit management platforms are fully proprietary. AuditBoard's AI features (Audit Agent, Document Intelligence, Accelerate) are proprietary implementations built on general LLM and ML techniques; none of the underlying approaches (evidence sampling, anomaly detection, NLP-based text generation) are believed to be patent-encumbered at the technique level. DataSnipper's document matching approach uses standard OCR and fuzzy-matching algorithms with no known patent protection. The IIA Standards (IPPF) are public and freely referenceable; building a platform aligned to IIA methodology carries no IP risk. COSO and PCAOB frameworks are also public. Eramba's GPL v3 licence requires that derivative works also be GPL — it is not a suitable base for a permissively licensed OSS audit platform. An OSS audit management platform built from scratch on Apache 2.0 or MIT would have no identified IP constraints.

---

## Recommended Feature Scope

**Must-have (MVP)**:
- Audit universe with risk-score-based entity list and annual plan builder
- Full audit engagement lifecycle: planning, fieldwork, review, reporting, follow-up
- Workpaper management with templates, electronic sign-off, and version control
- Finding lifecycle management with severity, root cause, management response, and CAP tracking
- Role-based access: CAE, audit manager, auditor, auditee, and executive read-only
- Audit committee reporting dashboard with open findings and plan status
- REST API and SSO (SAML/OIDC)

**Should-have (v1.1)**:
- AI-powered findings drafting (LLM-generated observation, root cause, and recommendation text)
- Automated population testing and statistical sampling from uploaded data files
- Continuous monitoring module for journal entry anomalies and SoD violations
- Time and resource tracking integrated with audit plan and engagement records
- External auditor collaboration portal for evidence request and delivery

**Nice-to-have (backlog)**:
- AI-assisted audit universe prioritisation with external data ingestion (news, financial filings)
- Document intelligence: automatic workpaper narrative generation from interview notes
- Built-in data analytics library (Benford's Law, duplicate detection, gap testing) for audit populations
- Integration with ITSM and cloud platforms for automated IT audit evidence collection
- ESG and sustainability audit workflow templates aligned to CSRD and GRI
