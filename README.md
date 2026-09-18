# ESG Sustainability Suite for Claude

An enterprise-oriented Claude plugin for ESG analysts, sustainability/reporting teams and sustainability leadership.

## Capabilities
- IFRS S1 / IFRS S2 disclosure analysis and drafting
- GRI, SASB and ESRS/CSRD cross-framework support
- GHG Protocol Scope 1, 2 and 3 accounting, including Category 15
- Climate risk/opportunity assessment and scenario-analysis support
- ESG governance, policy, committee and management/board reporting
- Double/materiality assessment workflows
- ESG KPI/data-quality controls and evidence mapping
- Sustainable/transition finance analysis
- Assurance-readiness and disclosure-control review

## Install as a Claude marketplace
Push this repository to GitHub, then add the repository as a marketplace in Claude. The root `.claude-plugin/marketplace.json` exposes the `esg-sustainability-suite` plugin.

## Design principle
The plugin distinguishes source-backed facts, calculations, assumptions and professional judgment. It does not invent company data, emission factors, regulatory requirements, assurance conclusions or framework compliance.


## Version 2.0 — Professional Knowledge Expansion

Adds six advanced specialist skills (IFRS S1/S2 implementation, ESRS double materiality, financed emissions/project finance, emission factors, disclosure controls, and ESG claims review), two specialist agents, five executive/technical commands, and a reusable reference library for framework hierarchy, GHG decisions, KPI governance, assurance, climate scenarios, materiality and Board reporting.

### Important design principle
This plugin does not embed copyrighted standards. It operationalizes workflows and points to official standard-setter sources. Users should verify the applicable jurisdiction, standard edition and effective date before external compliance claims.

### Suggested high-value commands
- `/ifrs-readiness`
- `/financed-emissions-review`
- `/double-materiality`
- `/claims-review`
- `/board-esg-pack`
- `/esg-gap-analysis`
- `/ghg-review`
- `/cso-review`
