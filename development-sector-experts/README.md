# Development Sector Experts

**Country-aware AI expert skills for development organizations, consulting firms, researchers, evaluators, programme teams, public institutions, and independent professionals.**

This collection turns recurring development-sector tasks into reusable AI workflows. Users can install one expert for a specific need or install the full suite and allow experts to work together.

## The operating model

Every expert supports two modes:

- **Standalone mode:** the expert can complete its core task without any other skill.
- **Integrated mode:** when related experts are available, it can use them to deepen country context, institutional analysis, evidence sourcing, data-quality assessment, localization, or adjacent sector analysis.

No expert should fail merely because another skill is not installed.

## Start in 10 seconds

If you know your sector, start with that expert. If you do not know which expert fits your task, start with `development-sector-expert-router`.

Examples:

```text
Use the Education Systems Expert to analyse foundational-learning challenges in Kenya and identify realistic programme priorities.
```

```text
Use the Public Health Expert to review this maternal-health proposal for Pakistan and identify evidence, implementation, equity, and measurement gaps.
```

```text
Use the Development Sector Expert Router to decide which experts should analyse a climate-related livelihoods assignment in Bangladesh.
```

## Which Expert Should I Use?

Use the detailed [routing guide](ROUTING-GUIDE.md), or start with this quick map:

| Your main task | Start with |
|---|---|
| Unsure which specialist you need | `development-sector-expert-router` |
| Country or subnational briefing | `country-context-expert` |
| Ministries, agencies, mandates, stakeholders | `institutional-mapping-expert` |
| Authoritative evidence and source selection | `official-evidence-source-expert` |
| Conflicting or weak statistics | `development-data-quality-expert` |
| Local terminology, language, audience fit | `localization-and-language-expert` |
| Education | `education-systems-expert` |
| Public health | `public-health-expert` |
| Social protection | `social-protection-expert` |
| Child protection | `child-protection-expert` |
| Disability inclusion | `disability-inclusion-expert` |
| Climate resilience/adaptation | `climate-resilience-expert` |
| Water resources/security | `water-security-expert` |
| WASH | `wash-expert` |
| Disaster risk reduction | `disaster-risk-reduction-expert` |
| Biodiversity | `biodiversity-expert` |
| Livelihoods/economic inclusion | `livelihoods-and-economic-inclusion-expert` |
| Employment, TVET, labour markets | `employment-and-skills-expert` |
| Agriculture/rural development | `agriculture-and-rural-development-expert` |
| Financial inclusion | `financial-inclusion-expert` |
| Governance/public-sector reform | `governance-and-public-sector-expert` |
| Local government | `local-governance-expert` |
| Migration/human mobility | `migration-and-human-mobility-expert` |
| Peacebuilding/conflict sensitivity | `peacebuilding-expert` |
| Humanitarian response | `humanitarian-response-expert` |
| Digital transformation/DPI | `digital-development-expert` |
| EdTech/digital learning | `digital-education-expert` |
| Digital health | `digital-health-expert` |
| Responsible AI/organizational AI integration | `responsible-ai-for-development-expert` |

## Expert families

### Core experts

- `development-sector-expert-router`
- `country-context-expert`
- `institutional-mapping-expert`
- `official-evidence-source-expert`
- `development-data-quality-expert`
- `localization-and-language-expert`

The core layer provides reusable context, institutions, evidence, data, and localization capabilities across the suite.

### Human Development

- `education-systems-expert`
- `public-health-expert`
- `social-protection-expert`
- `child-protection-expert`
- `disability-inclusion-expert`

### Climate & Environment

- `climate-resilience-expert`
- `water-security-expert`
- `wash-expert`
- `disaster-risk-reduction-expert`
- `biodiversity-expert`

### Economic Development

- `livelihoods-and-economic-inclusion-expert`
- `employment-and-skills-expert`
- `agriculture-and-rural-development-expert`
- `financial-inclusion-expert`

### Governance & Protection

- `governance-and-public-sector-expert`
- `local-governance-expert`
- `migration-and-human-mobility-expert`
- `peacebuilding-expert`
- `humanitarian-response-expert`

### Digital Development

- `digital-development-expert`
- `digital-education-expert`
- `digital-health-expert`
- `responsible-ai-for-development-expert`

## What users can do with the suite

The experts are designed for real professional workflows including:

- country and sector diagnostics;
- programme and project design;
- proposals and concept notes;
- evaluations and evaluation frameworks;
- policy and strategy analysis;
- institutional and stakeholder mapping;
- research and evidence synthesis;
- data-quality review;
- technical proposal development;
- risk and feasibility analysis;
- donor and development-partner briefings;
- market-entry and consulting assignments;
- digital transformation and responsible-AI integration.

## How experts work together

A user normally invokes only the lead expert.

Example: for an education-system assignment, `education-systems-expert` can work alone. When the full suite is installed, it may also use:

```text
education-systems-expert
├── country-context-expert
├── institutional-mapping-expert
├── official-evidence-source-expert
├── development-data-quality-expert
└── localization-and-language-expert
```

The same pattern applies across sectors.

## Country-aware by design

Sector experts are instructed to establish the relevant country and subnational context before transferring assumptions about institutions, policies, administrative systems, terminology, service-delivery models, or evidence from another country.

Where current external research is available, experts should prioritize authoritative country and institutional evidence and clearly distinguish evidence from inference.

## Quality and responsible-use principles

Across the suite, experts are expected to:

- avoid fabricated policies, institutions, statistics, citations, and programme experience;
- distinguish policy commitments from implementation reality;
- identify the year, geography, population, and definition behind important statistics;
- flag uncertainty and evidence gaps;
- use sensitive data cautiously;
- incorporate gender, disability, safeguarding, protection, and inclusion where relevant;
- avoid technology-first recommendations;
- retain human review for high-consequence outputs.

## Installation

See [INSTALLATION.md](INSTALLATION.md) for options ranging from downloading a single skill to cloning the whole repository.

## Examples

See [EXAMPLES.md](EXAMPLES.md) for ready-to-use prompts covering standalone, integrated, consulting, NGO, research, evaluation, and AI-integration scenarios.

## Authorship and positioning

This suite is developed and maintained by **Ahmad Nadeem** as part of a practical portfolio in **AI integration for development organizations, consulting firms, and development professionals**.

The design objective is not to publish a library of generic prompts. It is to demonstrate how domain knowledge, workflow design, evidence controls, localization, and responsible AI can be packaged into reusable expert capabilities.

See [ATTRIBUTION.md](ATTRIBUTION.md) for attribution details.

## License

The suite is released under the [MIT License](LICENSE), allowing reuse, modification, and distribution subject to the license terms.

## Status

Initial public-release candidate. The skills remain under active testing and refinement. Field feedback, examples, issue reports, and contributions are welcome.
