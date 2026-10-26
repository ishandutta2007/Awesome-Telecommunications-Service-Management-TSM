# Awesome-Telecommunications-Service-Management-TSM

# Top Telecommunications Service Management (TSM) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Telecom BSS/OSS, Service Orchestration & Customer Operations*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Telecommunications Service Management (TSM)**. These tools enable Communication Service Providers (CSPs) to manage the full service lifecycle—from product catalog and order management to provisioning, assurance, billing, and customer care—across B2C, B2B, and wholesale business models.

**Examples** include ServiceNow Telecommunications Service Management, Amdocs, Netcracker, Ericsson Digital BSS, CSG, Oracle Communications, Comarch, Cerillion, Hansen Technologies, and Subex (the category leaders).

**Open-source emphasis**: This section is heavily expanded with active projects for self-hosted telecom billing, OSS provisioning, charging engines, and ISP management—ideal for MVNOs, regional ISPs, and developers building sovereign telecom service management infrastructure without per-subscriber licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Telecommunications Service Management (TSM)](https://www.servicenow.com/)**  
  Telecom-specific orchestration layer on the Now Platform that automates incident, change, and problem management with full visibility into customer impact; uses AI Agents to automate issue resolution and onboarding across customer service and network operations .

- **[Amdocs](https://www.amdocs.com/)**  
  Comprehensive BSS/OSS suite with the newly launched **aOS** operating system that operates on top of any existing BSS/OSS stack, embedding telco-specific intelligence for cognitive, governed operations; targets GenAI-driven transformation across billing, charging, and customer experience .

- **[Netcracker](https://www.netcracker.com/)**  
  End-to-end Digital Platform covering service fulfillment, assurance, customer management, and monetization; cloud-native and AI-native with embedded AI agents across network automation, digital commerce, and omnichannel engagement layers; TMF, ETSI, MEF, ONAP, and O-RAN compliant .

- **[Ericsson Digital BSS](https://www.ericsson.com/)**  
  BSS suite including the Digital Monetization Platform (charging, billing, mediation, order management, catalog); supports real-time monetization and TM Forum Open APIs; deployed at scale for CSPs undergoing BSS transformation .

- **[CSG](https://www.csgi.com/)**  
  Business support systems for telecom scale, covering monetization, billing, and digital commerce for B2C and B2B; supports 600M+ subscribers and claims 99.70% migration success rate across large-scale BSS transitions; now part of Netcracker following acquisition .

- **[Oracle Communications](https://www.oracle.com/communications/)**  
  Oracle Digital BSS Express (DBX) packaged solution covering customer lifecycle, ordering, provisioning, rating, charging, and billing; delivered on Oracle Cloud Infrastructure in nine months or less with pre-built TM Forum eTOM processes .

- **[Comarch](https://www.comarch.com/)**  
  Telecom BSS/OSS portfolio with real-time OSS, SDN/NFV orchestration, zero-touch network provisioning, and IoT monetization; focused on automation and reducing operational costs for CSPs .

- **[Cerillion](https://www.cerillion.com/)**  
  Modular BSS/OSS suite with convergent charging, billing, revenue management, service manager with GenAI workflow creation, and network inventory; serves ~80 customer installations across ~45 countries with cloud or on-premise deployment .

- **[Hansen Technologies](https://www.hansencx.com/)**  
  Hansen CCB (Customer Care and Billing) solution for CSPs, pay-TV, and media providers; supports broadband, mobile, and value-added services with integrated customer care and billing for multi-country operations .

- **[Subex](https://www.subex.com/)**  
  Business assurance platform for revenue assurance and fraud management, processing 150B+ transactions daily; uses AI-driven risk discovery, adaptive controls, and guided investigation to protect margins and reduce revenue leakage .

## Open-Source GitHub Projects

- **[NMS Prime (Community Edition)](https://github.com/cablelabs/os-provisioning)**  
  Modular OSS provisioning platform for telcos and ISPs, covering DOCSIS, FTTH, FTTx, DSL, and WiFi activation; built on Laravel/PHP with integration for Icinga2, Prometheus, Grafana, and Cacti; enterprise modules add CRM, BSS, and billing; developed under CableLabs .

- **[CGRateS](https://github.com/cgrates/cgrates)**  
  Real-time Online/Offline Charging System (OCS) for Telecom and ISP environments; features account balance management, session/event charging with reservation, rating engine, CDR logging, fraud detection with automatic mitigation, and Least Cost Routing; cloud-ready microservices architecture with RPC APIs .

- **[BillRun CRM](https://bill.run/)**  
  Open-source CRM built on SuiteCRM and customized specifically for telecom operators and DSPs; adds OSS interface, subscriber management, and telecom inventory modules; integrates with BillRun billing and self-care portal to form a complete BSS stack .

- **[BillRun Revenue Assurance](https://bill.run/)**  
  GPL-licensed call generator and revenue assurance tool that automates test calls/SMS/MMS across 2G/3G/4G networks, compares billing reports, and detects revenue leakage; compatible with third-party modems and built on YAF PHP Framework with MongoDB .

- **[NOC Project](https://github.com/nocproject/noc)**  
  Open-source OSS for telecom companies and NOCs (BSD-3-Clause); covers service activation/provisioning, IPAM, multi-vendor configuration management, fault management, performance management, DNS provisioning, and peering management; actively developed since 2008 with recent commits .

- **[mediation (Rust crate)](https://github.com/hupe1980/mediation)**  
  Telecom usage mediation domain library in Rust; handles CDR parsing, deduplication, gap detection, sequence tracking across wraps, and 3GPP charging record formats; designed for reproducible, auditable mediation pipelines .

- **[Ubilling](https://github.com/nightflyza/Ubilling)**  
  Open-source billing system designed for Internet service providers; provides subscriber management, payment handling, detailed reporting, and network equipment monitoring/control; extensible with custom functionality .

### Additional Strong Open-Source Options

- **iTop** — Open-source ITSM platform with ITIL best practices and ISO 20000 certification; can be adapted for telecom service desk workflows, often paired with Nagios for network monitoring integration .
- **OTRS** — Open-source service management platform used in telecommunications for ticketing, workflow automation, and ITIL-oriented operations .
- **OpenTelemetry** — Open standard for instrumenting MVNO traffic routing and billing mediation pipelines, enabling revenue assurance reconciliation and SLA compliance monitoring .

**Frameworks for building custom systems**: Combine **NMS Prime** for OSS provisioning and network management, **CGRateS** for real-time charging and rating, **BillRun CRM** for subscriber and customer lifecycle management, and **mediation** for CDR processing in a fully self-hosted telecom BSS/OSS stack suitable for MVNOs and regional ISPs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Telecom service management platforms handling subscriber data must comply with applicable regulations (GDPR, local telecom licensing, lawful intercept requirements, etc.).
- Self-hosted open-source solutions for telecom are most viable for MVNOs, ISPs, and regional operators; Tier 1 CSP deployments typically require commercial BSS/OSS suites with vendor support and carrier-grade SLAs.
- Verify license terms for commercial use; NMS Prime uses a community/enterprise split, CGRateS and BillRun have open-source cores with commercial support options, and NOC Project uses BSD-3-Clause.

---

**Made for CSP operations teams, MVNO operators, ISP engineers, and telecom platform developers.**  
Let's make telecommunications service management more open, programmable, and operator-controlled.
