# Which Expert Should I Use?

This guide helps users choose the smallest useful combination of Development Sector Experts.

## Rule of thumb

**If you know your sector, start with the sector expert.**

You normally do not need to invoke the core experts manually. Sector experts can use them when installed and relevant.

**If you do not know which specialist fits your task, start with `development-sector-expert-router`.**

## Three user paths

### 1. Beginner or cross-sector request

Start with:

`development-sector-expert-router`

Use this when the request crosses sectors or you are unsure where to begin.

Example:

> Use the Development Sector Expert Router to determine the best experts for analysing how floods are affecting education, livelihoods, and social protection in Bangladesh.

### 2. Professional who knows the sector

Start directly with the lead expert.

Examples:

- education → `education-systems-expert`
- public health → `public-health-expert`
- climate adaptation → `climate-resilience-expert`
- social protection → `social-protection-expert`
- governance → `governance-and-public-sector-expert`

The lead expert can use supporting experts internally when they are available.

### 3. Specialist task

Invoke a core expert directly when the task is narrow:

- country context → `country-context-expert`
- ministries, mandates, stakeholders → `institutional-mapping-expert`
- authoritative evidence → `official-evidence-source-expert`
- data reliability/comparability → `development-data-quality-expert`
- localization/language → `localization-and-language-expert`

## Sector routing table

| If your main question is about… | Lead expert |
|---|---|
| Education systems, schools, teachers, learning, education financing | `education-systems-expert` |
| Health systems, primary care, maternal/child health, health financing | `public-health-expert` |
| Cash transfers, pensions, registries, targeting, social assistance | `social-protection-expert` |
| Child protection, safeguarding, child labour, trafficking, case management | `child-protection-expert` |
| Disability rights, accessibility, inclusive services | `disability-inclusion-expert` |
| Climate adaptation, resilience, NAP/NDC, climate risk | `climate-resilience-expert` |
| Water resources, basins, groundwater, irrigation | `water-security-expert` |
| Drinking water, sanitation, hygiene, WASH services | `wash-expert` |
| Disaster risk, preparedness, early warning, anticipatory action | `disaster-risk-reduction-expert` |
| Biodiversity, ecosystems, conservation, restoration | `biodiversity-expert` |
| Livelihoods, graduation, economic inclusion, market systems | `livelihoods-and-economic-inclusion-expert` |
| Employment, TVET, apprenticeships, labour markets, skills | `employment-and-skills-expert` |
| Agriculture, smallholders, value chains, rural development | `agriculture-and-rural-development-expert` |
| Financial access, digital finance, savings, credit, insurance | `financial-inclusion-expert` |
| Governance, public administration, public-sector reform | `governance-and-public-sector-expert` |
| Municipalities, decentralization, local planning and finance | `local-governance-expert` |
| Migration, labour mobility, trafficking, return, remittances | `migration-and-human-mobility-expert` |
| Conflict, social cohesion, mediation, conflict sensitivity | `peacebuilding-expert` |
| Emergency response, displacement, humanitarian assistance | `humanitarian-response-expert` |
| Digital government, DPI, digital transformation | `digital-development-expert` |
| EdTech, digital learning, education platforms | `digital-education-expert` |
| Digital health, HMIS, telehealth, health interoperability | `digital-health-expert` |
| AI integration, AI governance, responsible AI, generative AI adoption | `responsible-ai-for-development-expert` |

## Common multi-expert patterns

### Education programme design

Lead:
- `education-systems-expert`

Possible support:
- `country-context-expert`
- `institutional-mapping-expert`
- `official-evidence-source-expert`
- `development-data-quality-expert`
- `localization-and-language-expert`

### Climate-resilient WASH

Lead:
- `wash-expert`

Possible support:
- `climate-resilience-expert`
- `water-security-expert`
- `country-context-expert`
- `institutional-mapping-expert`

### Youth employment programme

Lead:
- `employment-and-skills-expert`

Possible support:
- `livelihoods-and-economic-inclusion-expert`
- `financial-inclusion-expert`
- `country-context-expert`
- `official-evidence-source-expert`

### AI integration in an NGO

Lead:
- `responsible-ai-for-development-expert`

Possible support:
- `digital-development-expert`
- relevant sector expert for the workflow being transformed
- `official-evidence-source-expert` where evidence verification matters
- `development-data-quality-expert` where data is used

### Humanitarian displacement response

Lead:
- `humanitarian-response-expert`

Possible support:
- `migration-and-human-mobility-expert`
- `child-protection-expert`
- `public-health-expert`
- `wash-expert`
- `social-protection-expert`

## Avoid over-orchestration

More experts do not automatically produce a better answer. Add a supporting expert only when it contributes a distinct analytical function.

A good default is:

**one lead expert + zero to three supporting experts.**

The router should prefer the smallest combination that can complete the task well.
