# Development Sector Experts

A modular suite of reusable AI skills for development organizations, consulting firms, researchers, evaluators, programme teams, and independent professionals.

## Design principle

Every expert works in two modes:

- **Standalone mode:** it can complete its core task without requiring any other skill.
- **Integrated mode:** when related experts are installed, it can use them to deepen context, evidence, institutional analysis, data validation, and localization.

No skill should fail simply because a supporting skill is unavailable.

## Start here

If you know your sector, start with the relevant sector expert. If you do not know which expert to use, start with `development-sector-expert-router`.

Examples:

- Education system analysis or programme design → `education-systems-expert`
- Health-sector analysis → `public-health-expert`
- Social protection systems or cash transfers → `social-protection-expert`
- Child protection and safeguarding → `child-protection-expert`
- Disability inclusion and accessibility → `disability-inclusion-expert`
- Climate resilience and adaptation → `climate-resilience-expert`
- Water resources or water security → `water-security-expert`
- Water, sanitation and hygiene → `wash-expert`
- Disaster risk reduction and preparedness → `disaster-risk-reduction-expert`
- Biodiversity and ecosystem conservation → `biodiversity-expert`
- Livelihoods or economic inclusion → `livelihoods-and-economic-inclusion-expert`
- Employment, labour markets, TVET or skills → `employment-and-skills-expert`
- Agriculture or rural development → `agriculture-and-rural-development-expert`
- Financial inclusion or digital finance → `financial-inclusion-expert`
- Governance or public-sector reform → `governance-and-public-sector-expert`
- Local government or municipal systems → `local-governance-expert`
- Migration, trafficking or human mobility → `migration-and-human-mobility-expert`
- Peacebuilding, conflict sensitivity or social cohesion → `peacebuilding-expert`
- Humanitarian response or emergency programming → `humanitarian-response-expert`
- Digital transformation or digital public infrastructure → `digital-development-expert`
- EdTech or digital learning → `digital-education-expert`
- Digital health or health information systems → `digital-health-expert`
- Responsible AI or organizational AI integration → `responsible-ai-for-development-expert`
- Institutional landscape → `institutional-mapping-expert`
- Authoritative evidence → `official-evidence-source-expert`
- Data reliability → `development-data-quality-expert`
- Country briefing → `country-context-expert`
- Local terminology/language → `localization-and-language-expert`

## Core experts

The core layer provides reusable capabilities that support every sector expert:

1. `development-sector-expert-router`
2. `country-context-expert`
3. `institutional-mapping-expert`
4. `official-evidence-source-expert`
5. `development-data-quality-expert`
6. `localization-and-language-expert`

Sector experts should call these only when useful. They must retain a built-in minimum fallback for context, evidence, quality control, and localization.

## Available human-development experts

- `education-systems-expert`
- `public-health-expert`
- `social-protection-expert`
- `child-protection-expert`
- `disability-inclusion-expert`

## Available climate & environment experts

- `climate-resilience-expert`
- `water-security-expert`
- `wash-expert`
- `disaster-risk-reduction-expert`
- `biodiversity-expert`

## Available economic-development experts

- `livelihoods-and-economic-inclusion-expert`
- `employment-and-skills-expert`
- `agriculture-and-rural-development-expert`
- `financial-inclusion-expert`

## Available governance & protection experts

- `governance-and-public-sector-expert`
- `local-governance-expert`
- `migration-and-human-mobility-expert`
- `peacebuilding-expert`
- `humanitarian-response-expert`

## Available digital-development experts

- `digital-development-expert`
- `digital-education-expert`
- `digital-health-expert`
- `responsible-ai-for-development-expert`

## Professional value

The suite is designed for real workflows including proposals, evaluations, strategy development, policy analysis, programme design, market entry, donor intelligence, research, technical reviews, briefing notes, stakeholder mapping, organizational decision support, digital transformation, and responsible AI integration.
