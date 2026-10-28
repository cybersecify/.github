# Cybersecify

Founder led penetration testing and compliance readiness for AI first and API first SaaS startups, Seed to Series B. Bengaluru, India. Founded 2023. Delivered remotely to clients in 9 countries across 4 continents.

Website: [cybersecify.com](https://cybersecify.com) · Pricing: [cybersecify.com/pricing](https://cybersecify.com/pricing) · Contact: [cybersecify.com/contact](https://cybersecify.com/contact)

Cybersecify is the trading name of Cyber Secify Consulting (OPC) Private Limited, registered in Bengaluru, India.

## What We Do

**Penetration Testing.** Manual exploitation by a named tester, not scanner output. Automated tooling is used for surface mapping only; authentication, authorization, business logic and chained exploits are tested by hand. Surfaces we test: AI and LLM applications (agents, tool calling, RAG, MCP servers), web applications, APIs (REST, GraphQL, webhooks), Android, iOS, desktop and Electron, cloud (AWS, Azure, GCP), IoT, and internal and external networks. Grey-box by default; black-box and white-box on request. Both founders work every engagement, and we take at most 6 pentests a month.

**Audit and Compliance Readiness.** SOC 2 Type 1 and Type 2, ISO 27001 (ISMS build, Annex A controls, internal audit, Stage 1 and 2 support) and India DPDP Act readiness, with CERT-In readiness handled inside the DPDP work. We prepare and evidence; the certifying audit itself is issued by a separate accredited auditor. Scoped per engagement, with no price list.

**Platform Programmes.** We deliver the testing and evidence for the Amazon SP-API Data Protection Policy (Clause 2.7.2), Shopify Partner Governance (findings indexed against the sixteen Level 1 and Level 2 protected customer data controls) and Microsoft 365 Certification. These are not separate products and have no separate price list: you buy the pentest plans below, scoped to what the programme asks for. These are ungated requirements: no empanelment and no vendor certification is needed, only the client's written authorisation.

Common reasons buyers come to us: a SOC 2 or ISO 27001 audit, an enterprise customer security review, investor or acquirer diligence, or a platform programme listing, renewal or reinstatement.

## Engagement Model

**Essentials Plan, INR 74,999.** For when a customer, investor or acquirer is evaluating you. 1 scope, report in 6 business days, OWASP Top 10 and PTES, technical report plus a 2 page executive summary, 6 hours of founder led consulting (usable within 6 months of kickoff), 1 free retest, and a monthly external attack surface scan. Each additional scope is INR 44,999, with no cap.

**Compliance Plan, INR 1,79,999.** For when a certificate is on the line. 2 scopes, report in 12 business days, OWASP WSTG v4.2 test cases on top of the OWASP Top 10 and PTES baseline, real world attack simulation (chained exploits, privilege escalation, lateral movement, business logic abuse), SOC 2 and ISO 27001 control mapping per finding, a signed Letter of Attestation, 12 hours of founder led consulting (usable within 12 months of kickoff), 1 free retest, and a monthly external attack surface scan. Each additional scope is INR 74,999, with no cap.

**Scope.** One scope is one thing we test, not one company. A web app, the API behind it and an Android build are three scopes. We confirm the scope count before final pricing.

**Timeline.** 6 business days per scope: five days of testing and one day writing the report. The clock starts once access is verified, so waiting on access never comes out of your testing time. For larger estates we confirm the schedule when we scope the work. You get a written progress update every week, and each confirmed finding as we find it.

**Retest.** Included in both plans, not a paid add-on. It starts when your fixes are live, up to one month after the v1.0 report, takes 1 to 3 business days, re-checks every finding, and is delivered as a v2.0 report.

**How an engagement runs.**
1. Initial inquiry and a non binding estimate.
2. Mutual NDA, product walkthrough and access check.
3. Formal fixed price quote based on what we saw. It can go down as readily as up, and you approve it before anything is signed.
4. SOW locks scope, dates and deliverables. A 50% advance books the slot. Nothing changes after signing.
5. Testing and the v1.0 report. The balance is invoiced on delivery.
6. Free retest and the v2.0 report.

**Pricing terms.** Priced by effort (how many scopes, and what each takes to test), not by where the client is located. The same price applies in every country. Prices exclude taxes. The INR price binds; USD and EUR figures on the site are indicative. Indian buyers are charged GST; exports are zero rated under a Letter of Undertaking. Extra consulting hours are INR 3,500 each. Published pricing is the current figure at [cybersecify.com/pricing](https://cybersecify.com/pricing).

A real anonymized deliverable is at [cybersecify.com/sample-report](https://cybersecify.com/sample-report) and the full engagement process is at [cybersecify.com/methodology](https://cybersecify.com/methodology).

## Frameworks We Test Against

**OWASP**, matched to the application in scope: Top 10:2025, WSTG v4.2, ASVS 5.0.0, API Security Top 10 (2023), Mobile Top 10 (2024), MASTG, MASVS, Desktop App Top 10, IoT Top 10, Kubernetes Top 10, LLM Top 10 and AI Exchange.

**Engagement and technique standards:** PTES for the engagement lifecycle, NIST SP 800-115 for rules of engagement and evidence handling, MITRE ATLAS technique IDs for AI and LLM findings, and MITRE ATT&CK technique IDs for network findings.

**Scope specific baselines**, applied only where they fit: CIS Benchmarks, NIST CSF 2.0 and CSA CCM v4 for cloud; OSSTMM 3 for networks; ETSI EN 303 645 for IoT; DASVS for desktop.

Findings are scored with CVSS v3.1 and CVSS v4.0, and every finding carries a CWE identifier. Compliance work maps to SOC 2 Type 1 and Type 2, ISO 27001, the India DPDP Act, NIST CSF and the RBI Cybersecurity Framework.

We do not hold CERT-In empanelment and do not claim it. If a regulator or a specific customer requires an empanelled auditor, we are not the right vendor and we will say so.

## Team

12 people. Founders: Ashok Kamat (Co-founder and CEO), who leads scoping, compliance readiness and client delivery, and Rathnakara GN (Co-founder and Chief Hacking Officer, M.Sc Cyber Security, OSCP credential OS-101-34173), who leads every penetration testing engagement. Both founders are hands on in every engagement; no junior analysts and no handoffs. Team certifications: CISSP, OSCP, CEH, CREST, ISO 27001 Lead Auditor, CompTIA PenTest+.

## Open Source: OpenEASD

OpenEASD is our free, MIT licensed external attack surface discovery tool. It finds internet facing assets, scores what is wrong with them, and on a rescan tells you what is new and what is gone since the last run.

It wraps the standard OSS recon tools (subfinder, amass, alterx, dnsx, subzy, naabu, httpx, gau, katana, nuclei, nmap, gitleaks and cloud_enum) behind a single web UI with scheduling, alerts and findings tracking. No telemetry. Results stay on your machine.

Self host the Docker image and run unlimited scans on your own infrastructure, or use the free hosted snapshot at [cybersecify.com/openeasd](https://cybersecify.com/openeasd). There is no paid tier and no upsell on the tool itself. Sample output: [cybersecify.com/sample-openeasd-report](https://cybersecify.com/sample-openeasd-report).

## Community

Community Partner for Security BSides Bangalore 2026.

## Get in Touch

Bring us your architecture rather than picking a plan blind. [cybersecify.com/contact](https://cybersecify.com/contact) or book a 30 minute call with a founder.
