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
- Climate resilience → `climate-resilience-expert`
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

## Professional value

The suite is designed for real workflows including proposals, evaluations, strategy development, policy analysis, programme design, market entry, donor intelligence, research, technical reviews, briefing notes, stakeholder mapping, and organizational decision support.
