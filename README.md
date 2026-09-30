# Awesome-Construction-Project-Management

# Top Construction Project Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Project Scheduling, Cost Control, Field Coordination & Document Management*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Construction Project Management**. These tools help general contractors, specialty contractors, and owners plan, execute, and close out construction projects—managing schedules, budgets, documents, RFIs, submittals, and field coordination.

**Examples** include Procore, Buildertrend, CoConstruct, Fieldwire, Autodesk Construction Cloud, RedTeam, Buildxact, ProjectSight, Contractor Foreman, Jonas Construction Software, Oracle Primavera Cloud, and CMiC (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom project workflows, and transparent construction data—ideal for contractors that need full control over their project management infrastructure without per-user fees or vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Procore](https://www.procore.com/)**
  The dominant construction management platform, used by over 3 million individual users. **Unlimited users, unlimited data, and unlimited 24/7 support** across all plans. Pricing is based on **Annual Construction Volume (ACV)**—the aggregate dollar value of construction work across projects. Bundled packages (Project Execution, Cost Management, Resource Management, Project Lifecycle Management) launched in February 2026. Products include Project Financials, Procore Pay (payment processing with lien waiver automation), and agentic AI capabilities for workflow automation .

- **[Buildertrend](https://www.buildertrend.com/)**
  Residential construction management platform with **unlimited users and projects** across all tiers. Three plans: **Essential ($399–$499/mo)** for basic project management and client communication, **Advanced ($699–$799/mo)** for detailed estimating and budget tracking, and **Complete ($999–$1,099/mo)** for client selections, warranty tracking, and RFIs. Mid-market contractors typically spend $8k–$10k annually. No free plan; 30-day trial available .

- **[Fieldwire](https://www.fieldwire.com/)**
  Field management platform optimized for construction teams. **Free tier** for small teams (≤3 projects, ≤100 sheets, ≤5 users). Premium tiers: **Pro ($468/user/year)**, **Business ($768/user/year)**, **Business Plus ($948–$1,068/user/year)**. Only the **Project Owner pays**—users with their own premium accounts don't incur additional charges. Pricing is prorated for revolving users .

- **[Autodesk Construction Cloud](https://construction.autodesk.com/)**
  Comprehensive construction platform combining BIM, project management, and field collaboration. **Standard, Premium ($100K+ annual), and Enterprise ($500K+ annual)** tiers with 10–35% discount structures. **Flex tokens** available for occasional users. Major licensing pitfall: seats are charged whether or not users log in—enterprises report 15–30% dormant seats. **Bridge** cross-account sharing requires licensing on both sides .

- **[ProjectSight](https://www.trimble.com/en/products/projectsight)**
  Trimble's construction project management platform. **Free tier** for small teams with core document and field management. **Go tier ($29 USD/user/month)** for growing teams with volume purchasing. **Enterprise** (custom pricing) for 30+ users with advanced visualization and BIM workflows. Integrates with Trimble Construction One and Viewpoint .

- **[RedTeam](https://www.redteam.com/)**
  Construction project management and accounting platform. Starting price approximately **$10,000/year**. Popular among general contractors and subcontractors for construction management and accounting integration .

- **[Buildxact](https://www.buildxact.com/)**
  Estimating and project management for residential builders. **Unlimited users across all plans**. Features AI Calculator, native timesheets with QuickBooks integration, digital signatures, and Blu AI tools (Estimate Generator, Takeoff Assistant, Estimate Reviewer). **Pro plan $399/mo** (excl. GST). Foundation Plan available as more affordable option .

- **[Contractor Foreman](https://www.contractorforeman.com/)**
  Affordable construction management platform starting at **$49/month**. Provides project management, scheduling, and field coordination for small to mid-sized contractors .

- **[Jonas Construction Software](https://www.jonasconstruction.com/)**
  Construction ERP for mechanical, HVAC, plumbing, electrical, and specialty contractors. **Modular pricing**—mandatory core (GL, AP, AR, payroll) plus operational modules (job costing, equipment, inventory, T&M billing) and optional add-ons (GPS Routing, Open API, Field Mobile). **30+ years** in business with **14,000+ users**. Hosted on Microsoft Azure .

- **[Oracle Primavera Cloud](https://www.oracle.com/)**
  Enterprise project portfolio management for large capital projects. Starting price approximately **$100/year**. Industry standard for complex scheduling and resource management in engineering and construction.

- **[CMiC](https://www.cmicglobal.com/)**
  Construction ERP and project management platform. Pricing available upon request (typically enterprise-level, **$10,000+/year**). Integrates financials, project management, and field operations .

## Open-Source GitHub Projects

- **[OpenConstructionERP](https://github.com/datadrivenconstruction/OpenConstructionERP)**
  **The most complete open-source construction ERP and project management platform.** **AGPL-3.0 licensed**, Python 3.12+ with FastAPI backend and React 18/TypeScript frontend. **Zero-config install**: `pip install openconstructionerp` starts an embedded PostgreSQL database automatically—no Docker, no Redis, no separate database setup . **Comprehensive feature set**: BOQ editor with hierarchical bill of quantities, multi-currency support, **120K+ priced cost items across 9 cost bases** ; AI-powered cost estimation from text, photos, PDFs, and spreadsheets; **CAD/BIM takeoff** from DWG/DXF, IFC, and RVT files without IfcOpenShell ; 4D/5D scheduling with earned value (SPI/CPI) and cash-flow forecasting; **submittals module** with multi-stage review workflows (Contractor → Engineer → Architect), revision tracking, and specification linking ; **validation rule packs** for DIN 276, GAEB, NRM, and MasterFormat; 45 locale files with full RTL support (Arabic, Urdu, Persian, Hebrew) . **Demo accounts** include 70 pre-loaded projects across 30+ countries. **Available on PyPI** as `openconstructionerp` .

- **[OpenConstructionERP Submittals](https://github.com/datadrivenconstruction/OpenConstructionERP/blob/main/docs/docs.html)**
  Dedicated submittals management module within OpenConstructionERP. Features **multi-stage review workflows** with sequential or parallel reviewers, review outcomes (Approved, Approved as Noted, Revise and Resubmit, Rejected) with stamped comments, automatic revision numbering (Rev A, Rev B), a **submittal register** showing all submittals with current status and days outstanding, and **specification linking** to BOQ positions for traceability .

### Additional Strong Open-Source Options

- **Construction ERP/PM**: **OpenConstructionERP** (most complete, AGPL-3.0, zero-config install) .
- **BOQ & Cost Estimation**: Built into OpenConstructionERP with 120K+ cost items, multi-currency, and regional catalogues .
- **CAD/BIM Takeoff**: OpenConstructionERP's DDC converters handle RVT, IFC, DWG, and DGN without IfcOpenShell dependencies .
- **Submittals & RFIs**: OpenConstructionERP provides production-ready submittal workflow with multi-stage review .

**Frameworks for building custom systems**: **OpenConstructionERP** serves as a comprehensive foundation, combining BOQ editing, cost databases, CAD/BIM takeoff, 4D/5D scheduling, and submittal management in a single self-hosted platform . Add **PostgreSQL** (embedded or external) for persistence and optional **LLM integration** (Anthropic, OpenAI, Gemini, Mistral, Groq, DeepSeek) for AI-powered estimation .

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Construction project management platforms handle sensitive project, financial, and contract data; ensure proper access controls and compliance with contractual requirements.
- **Open-source reality**: **OpenConstructionERP** is a **genuinely comprehensive open-source alternative**—the first of its kind to cover cost estimation, CAD/BIM takeoff, 4D/5D scheduling, and submittals in a single self-hosted platform . It eliminates per-user pricing entirely. However, **commercial platforms** (Procore, Autodesk Construction Cloud) provide deeper ecosystem integrations (Procore Pay, accounting connectors, mobile apps at scale) and enterprise-grade support that open-source projects cannot yet match. **OpenConstructionERP** is most viable for contractors with engineering capacity who want full data ownership and zero per-seat costs.

---

**Made for general contractors, project managers, estimators, and construction technologists.**
Let's make construction project management more open, transparent, and cost-effective.
