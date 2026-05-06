# Standards & API Reference

> Project: Audit Management Platform · Generated: 2026-05-06

## Industry Standards & Specifications

### Auditing & Assurance Standards

**ISO 19011:2018 — Guidelines for Auditing Management Systems**
- URL: https://www.iso.org/standard/70017.html
- The primary international standard providing guidelines for auditing management systems including audit programme management, audit principles, and auditor competence evaluation. Applicable to all organisations conducting internal or external management system audits (ISO 9001, ISO 14001, ISO 45001, etc.). Not certifiable itself but underpins certifiable standards. The current edition (3rd) was issued in 2018; a further revision (ISO 19011:2024) is in progress.

**IIA Global Internal Audit Standards (IPPF 2024)**
- URL: https://www.theiia.org/en/standards/2024-standards/global-internal-audit-standards/
- The authoritative global standard for internal audit functions, published by the Institute of Internal Auditors. The 2024 edition superseded the 2017 IPPF effective 9 January 2025. Organised into five domains: Purpose of Internal Auditing, Ethics and Professionalism, Governing the Internal Audit Function, Managing the Internal Audit Function, and Performing Internal Audit Services. All commercial audit management platforms align their workflows to IPPF requirements.

**ISAE 3000 / ISAE 3402 — International Standards on Assurance Engagements**
- ISAE 3402: https://www.ifac.org/system/files/downloads/b014-2010-iaasb-handbook-isae-3402.pdf
- ISAE 3000 covers general assurance engagements (equivalent to SOC 2); ISAE 3402 covers service organisation controls relevant to user entity financial reporting (equivalent to SOC 1). Both drive common audit scope requirements in enterprise platforms serving global organisations. Issued by the International Auditing and Assurance Standards Board (IAASB).

**PCAOB Auditing Standards**
- URL: https://pcaobus.org/Standards/Auditing
- Public Company Accounting Oversight Board standards governing external audit of US-listed public companies. Internal audit platforms must support handoff of evidence to external auditors working under PCAOB AS 2201 (integrated audit of internal controls) and related standards.

### ISO Standards

**ISO/IEC 27001:2022 — Information Security Management Systems**
- URL: https://www.iso.org/standard/27001
- World's most widely adopted information security standard; defines requirements for an ISMS. The 2022 revision restructured Annex A to 93 controls across four themes (organisational, people, physical, technological) and added cloud security and data privacy controls. A common audit scope for internal IT audit teams; all major audit platforms include ISO 27001 control frameworks. Mandatory transition deadline was October 2025.

**ISO 9001:2015 — Quality Management Systems**
- URL: https://www.iso.org/standard/62085.html
- Requirements for quality management systems; clause 9.2 mandates internal audit programmes. The most common ISO standard audited using dedicated audit management software, particularly in manufacturing and regulated industries.

**ISO 14001:2015 — Environmental Management Systems**
- URL: https://www.iso.org/standard/60857.html
- Environmental management system requirements including mandatory internal audit (clause 9.2). EHS (Environment, Health & Safety) audit modules in platforms such as GoAudits and Donesafe are built specifically around ISO 14001 and ISO 45001 audit requirements.

**ISO 45001:2018 — Occupational Health and Safety Management Systems**
- URL: https://www.iso.org/standard/63787.html
- OHS management standard replacing OHSAS 18001; requires documented internal audit programme. Commonly combined with ISO 14001 in integrated EHS audit workflows.

### Governance & Control Frameworks

**COSO Internal Control — Integrated Framework (2013)**
- URL: https://www.coso.org/guidance-on-ic
- The dominant internal control framework for US and global organisations; defines five components and 17 principles. Internal audit platforms map findings and control assessments directly to COSO components. SOX Section 404 compliance is built around COSO.

**COBIT 2019 — Control Objectives for Information and Related Technology**
- URL: https://www.isaca.org/resources/cobit
- ISACA's IT governance and management framework; the most widely used IT audit reference. COBIT 2019 aligns with COSO and supports integration with ISO 27001, NIST, and other frameworks. Audit platforms targeting IT audit functions commonly include COBIT control libraries.

### Cybersecurity & IT Standards

**NIST SP 800-53 Rev. 5 — Security and Privacy Controls**
- URL: https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final
- Catalogue of 1,196 security and privacy controls across 20 families; mandatory for US federal systems, widely adopted commercially. Paired with NIST SP 800-53A Rev. 5 (assessment procedures). AWS Audit Manager, Azure Compliance Center, and Google Cloud Audit Manager all provide prebuilt NIST 800-53 assessment frameworks.

**ISA/IEC 62443 — Security for Industrial Automation and Control Systems**
- URL: https://www.isa.org/standards-and-publications/isa-standards/isa-iec-62443-series-of-standards
- Series of standards for OT/IACS cybersecurity; endorsed by the United Nations and recognised as a horizontal standard by IEC in 2021. Relevant to audit management platforms serving industrial, energy, or critical infrastructure sectors. Defines four security levels and a cybersecurity management system (CSMS) lifecycle.

### Regulatory Frameworks

**SOX (Sarbanes-Oxley Act) — Sections 302 and 404**
- URL: https://pcaobus.org/oversight/standards/auditing-standards/details/AS2201
- US federal law requiring CEO/CFO certification of internal controls (s.302) and external auditor attestation (s.404). The single largest driver of internal audit platform demand among US public companies. Platforms must support evidence collection, control testing documentation, and auditor collaboration aligned to PCAOB AS 2201.

**GDPR — General Data Protection Regulation**
- URL: https://gdpr-info.eu/
- EU data protection regulation; Article 30 mandates records of processing activities, Article 32 requires technical security measures, and Article 5(2) establishes the accountability principle requiring demonstrable compliance. Audit trail and evidence retention requirements directly shape audit management platform data models. Typical audit log retention is 2–7 years. Platforms must manage personal data within audit records in compliance with GDPR.

### W3C & IETF Standards

**RFC 9110 — HTTP Semantics**
- URL: https://www.rfc-editor.org/rfc/rfc9110
- Defines semantics for HTTP/1.1 and HTTP/2; foundational for all REST API implementations in audit management platforms.

**RFC 6749 — OAuth 2.0 Authorization Framework**
- URL: https://www.rfc-editor.org/rfc/rfc6749
- The authoritative standard for delegated API authorisation; used by all major audit platforms (AuditBoard, Vanta, Drata, MetricStream) to secure API access. Typically combined with OpenID Connect (OIDC) for identity.

**RFC 7643 / 7644 — SCIM 2.0 — System for Cross-domain Identity Management**
- URL: https://www.rfc-editor.org/rfc/rfc7643 · https://www.rfc-editor.org/rfc/rfc7644
- Open standard for automated exchange of user identity information between systems. TeamMate+ uses SCIM 2.0 for user provisioning via its Identity Provider API. Enterprise procurement checklists for audit platforms routinely require SCIM support for integration with Okta, Microsoft Entra ID, and similar identity providers.

**SAML 2.0 — Security Assertion Markup Language**
- URL: https://docs.oasis-open.org/security/saml/v2.0/
- XML-based SSO protocol; required by enterprise audit platforms to integrate with corporate identity providers. All major platforms (AuditBoard, Workiva, ServiceNow, HighBond) support SAML 2.0 for SSO.

### Data Model & API Specifications

**OpenAPI Specification 3.x**
- URL: https://spec.openapis.org/oas/latest.html
- The de-facto standard for describing REST APIs; used by AuditSoft (explicitly), MetricStream, and Drata to publish machine-readable API contracts. An AI-native audit platform should expose a complete OpenAPI 3.1 specification.

**XBRL — eXtensible Business Reporting Language**
- URL: https://www.xbrl.org/the-standard/what/
- International standard for digital financial and compliance reporting; used for regulatory filings (SEC, ESMA, APRA). Relevant to audit management platforms dealing with financial statement audits or regulatory submissions. IAASB has noted that ISAs do not yet require auditor attestation on XBRL-tagged data, but guidance is evolving.

**OData v4 — Open Data Protocol**
- URL: https://www.odata.org/documentation/
- OASIS standard for building and consuming queryable REST APIs; TeamMate+ exposes its Reporting API in OData-compliant format, enabling direct consumption by Power BI and Excel without coding.

---

## Similar Products — Developer Documentation & APIs

### AuditBoard

- **Description:** Cloud-native audit, risk, and compliance platform; market leader among modern audit management SaaS tools. Supports internal audit, SOX, ESG, and operational risk workflows.
- **API Documentation:** https://developer.auditboard.com/ (requires login — ReadMe-hosted, Auth0-protected)
- **SDKs/Libraries:** No official SDK; REST API consumed directly. Community R package for data extraction available via GitHub (soxhub org).
- **Developer Guide:** https://developer.auditboard.com/docs/getting-started-1
- **Standards:** REST/JSON; API documented via ReadMe platform
- **Authentication:** OAuth 2.0 / Auth0; customer SSO via SAML 2.0

### Wolters Kluwer TeamMate+

- **Description:** Enterprise audit management with workpapers, risk-based audit planning, GRC integration, and IPPF-aligned workflows. Long-standing incumbent in large enterprise market.
- **API Documentation:** https://www.wolterskluwer.com/en/solutions/teammate/apis
- **SDKs/Libraries:** No official SDK documented publicly
- **Developer Guide:** Same URL as API documentation
- **Standards:** REST (Data Exchange API); OData v4 (Reporting API); SCIM 2.0 (Identity Provider API); JSON
- **Authentication:** Encrypted connections, role-based access; SAML 2.0 SSO
- **Key APIs:**
  - *Reporting API* — OData-compliant extraction of all reporting data; integrates with Power BI and Excel
  - *Data Exchange API* — Bidirectional REST API for issues, recommendations, risks, controls, resource management, and custom measures
  - *Event Monitoring API* — Security event log export to SIEM systems
  - *Identity Provider API* — SCIM 2.0 user provisioning

### Diligent One Platform (formerly HighBond / Galvanize)

- **Description:** Integrated governance, risk, audit, and ESG platform following Diligent's acquisition of Galvanize in 2021. Includes AuditBond (internal audit), ACL Analytics (data analytics), and board intelligence tools.
- **API Documentation:** https://docs-apis.highbond.com/ (legacy endpoint; current primary endpoint is diligentoneplatform.com)
- **SDKs/Libraries:** R package `galvanizer` — https://jonlinca.github.io/galvanizer/
- **Developer Guide:** https://docs-apis.highbond.com/
- **Standards:** REST/JSON; legacy highbond.com endpoints remain fully supported
- **Authentication:** API token; SAML 2.0 SSO
- **Regions:** US, Canada, Europe, Asia, Australia, Africa, South America, Japan

### ServiceNow GRC — Audit Management

- **Description:** Audit and risk management workflows embedded within the ServiceNow platform. Leverages native ITSM, CMDB, and workflow engine. Best suited to organisations already running ServiceNow.
- **API Documentation:** https://docs.servicenow.com/bundle/washingtondc-governance-risk-compliance/page/product/grc-audit/concept/c_GRCAudits.html
- **SDKs/Libraries:** ServiceNow SDK / Scripted REST APIs
- **Developer Guide:** https://docs.servicenow.com/ (GRC module bundle)
- **Standards:** REST/JSON; OpenAPI for table API; scripted REST for custom GRC endpoints
- **Authentication:** OAuth 2.0; SAML 2.0 SSO; mutual TLS available

### MetricStream

- **Description:** Enterprise GRC platform with full audit lifecycle management across internal audit, IT audit, operational audit, and supplier audits. Targets Fortune 500 and regulated industries.
- **API Documentation:** https://www.metricstream.com/api-developer-portal.html
- **SDKs/Libraries:** Not publicly documented
- **Developer Guide:** https://www.metricstream.com/platform/apis.htm
- **Standards:** OpenAPI-compliant REST APIs; Content Integration Service (REST-based outbound connectors)
- **Authentication:** Role-based access; SSO integration; API keys

### AuditSoft

- **Description:** Audit management platform with open API; focuses on occupational health and safety auditing with analytical data warehouse integration.
- **API Documentation:** https://auditsoft.co/news/auditsoft-open-api-available-for-integration/
- **SDKs/Libraries:** Not documented
- **Developer Guide:** Same URL
- **Standards:** JSON-based REST API; OpenAPI specification
- **Authentication:** API key
- **Notes:** Announced August 2023; enables legacy and custom-built systems to connect with AuditSoft's audit tool and analytical data warehouse.

### Drata

- **Description:** Continuous compliance automation platform focused on SOC 2, ISO 27001, HIPAA, and other security frameworks. Strong evidence collection automation with 300+ integrations. Not a full internal audit lifecycle tool but highly relevant to compliance audit evidence management.
- **API Documentation:** https://developers.drata.com/api-docs/
- **SDKs/Libraries:** Not officially published; REST API consumed directly
- **Developer Guide:** https://developers.drata.com/
- **Standards:** REST/JSON; OpenAPI 3.x
- **Authentication:** Bearer token (API key); 500 requests/minute rate limit
- **Key Resources (from API):** Controls, Frameworks, Policies, Evidence Library, Risks, Risk Registers, Personnel, Assets, Devices, Vendors, Monitoring Tests, Custom Connections, Custom Data Records

### Vanta

- **Description:** Largest pure-play compliance automation platform (15,000+ customers as of 2026); automated evidence collection covering SOC 2, ISO 27001, HIPAA, GDPR, and others. Shipped AI Agent 2.0 in January 2026.
- **API Documentation:** https://developer.vanta.com/
- **SDKs/Libraries:** Not officially published
- **Developer Guide:** https://www.vanta.com/products/vanta-api
- **Standards:** REST/JSON; OAuth 2.0
- **Authentication:** OAuth 2.0 with granularly scoped read/write permissions; administrator-managed credentials
- **Key Capabilities:** Security awareness training data ingestion, background check results, MDM data, vulnerability scanner results, custom/on-premise system integration; bulk document uploads; resource owner assignments; scope management; employee offboarding automation

### AWS Audit Manager

- **Description:** AWS-native continuous audit service that automates evidence collection from CloudTrail, Security Hub, Config, and API calls. Provides prebuilt frameworks for SOC 2, NIST 800-53, ISO 27001, HIPAA, and CIS.
- **API Documentation:** https://docs.aws.amazon.com/audit-manager/latest/APIReference/
- **SDKs/Libraries:** AWS SDK (all major languages — Python/boto3, JS/TypeScript, Java, Go, Ruby, .NET)
- **Developer Guide:** https://docs.aws.amazon.com/audit-manager/latest/userguide/what-is.html
- **Standards:** REST/JSON via AWS SDK; AWS Signature Version 4 authentication; OpenAPI compatible
- **Authentication:** AWS IAM roles and policies; SigV4 request signing

### Google Cloud Audit Manager

- **Description:** Google Cloud's compliance audit service; runs audits against frameworks (CIS, NIST) to assess GCP environment state. Relatively newer service compared to AWS Audit Manager.
- **API Documentation:** https://cloud.google.com/audit-manager/docs/reference/rest
- **SDKs/Libraries:** Google Cloud client libraries (Python, Go, Java, Node.js, .NET, Ruby, PHP)
- **Developer Guide:** https://docs.cloud.google.com/audit-manager/docs/run-audit
- **Standards:** REST/JSON; gRPC; OpenAPI 3.x via Discovery API
- **Authentication:** Google OAuth 2.0; service account credentials; Workload Identity Federation

---

## Notes

### Gaps and Evolving Areas

- **No universal audit data exchange standard exists.** Unlike financial reporting (XBRL) or healthcare (HL7/FHIR), there is no industry-wide standard for exchanging audit findings, workpapers, or evidence between platforms. Each vendor implements proprietary data models. An open-source AI-native platform has an opportunity to define an open schema and advocate for interoperability.

- **Workpaper format interoperability** is entirely absent. TeamMate+ workpapers, AuditBoard documentation, and Workiva-linked content are all proprietary formats with no cross-platform portability.

- **AI/ML model governance standards for audit** are nascent. As AI-generated findings and risk scores enter audit workflows, there are no established standards for explainability, bias assessment, or auditor oversight of AI outputs. The IIA and ISACA are developing guidance but no normative standard exists as of mid-2026.

- **MCP (Model Context Protocol)** relevance: An AI-native audit platform could expose audit entities (findings, risks, controls, workpapers) as MCP resources, enabling AI agents to query and reason over audit data programmatically. No existing platform has implemented MCP server endpoints as of this research date.

- **Evidence format standards**: Most platforms accept evidence as file uploads (PDF, XLSX, images). There is no standard structured evidence schema. AWS Audit Manager's approach of structured JSON evidence records from CloudTrail represents the most machine-readable approach currently available.
