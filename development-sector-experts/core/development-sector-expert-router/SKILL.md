---
name: development-sector-expert-router
description: Use when a development-sector user needs help choosing the most relevant expert skill, when a request spans several sectors, or when the appropriate specialist is not obvious.
---

# Development Sector Expert Router

## Purpose
Route a development-sector request to the smallest useful combination of expert skills. Prefer one lead sector expert plus only the supporting core experts that materially improve the result.

## Operating rule
Do not make users manually orchestrate the suite. If the relevant sector expert is available, route the task there and identify supporting experts internally. If it is not available, provide the best structured analysis possible using the router's fallback framework and clearly state the limitation.

## Step 1: Classify the request
Identify:
- country and subnational geography;
- sector and subsector;
- task type;
- intended audience;
- required output;
- whether current external evidence is necessary;
- whether the request is single-sector or cross-sector.

Common task types: situation analysis, proposal design, policy review, evaluation, strategy, institutional mapping, donor brief, market-entry analysis, evidence synthesis, data validation, programme design, technical review.

## Step 2: Select one lead expert
Examples:
- education, learning, teachers, schools, EdTech → `education-systems-expert`
- public health, health systems, maternal/child health → `public-health-expert`
- social assistance, cash transfers, pensions → `social-protection-expert`
- climate risk, adaptation, resilience → `climate-resilience-expert`
- WASH services and hygiene → `wash-expert`
- water resources, irrigation, groundwater → `water-security-expert`
- migration, trafficking, mobility → `migration-and-human-mobility-expert`
- digital public systems and digital transformation → `digital-development-expert`

For genuinely cross-sector requests, select one primary expert and add secondary experts only where their contribution is distinct.

## Step 3: Add supporting core experts only when needed
- country or subnational context → `country-context-expert`
- institutional roles or stakeholder architecture → `institutional-mapping-expert`
- authoritative external evidence → `official-evidence-source-expert`
- conflicting, outdated, or methodologically different data → `development-data-quality-expert`
- local terminology, audience, language, units, or culturally specific framing → `localization-and-language-expert`

## Standalone fallback
If other experts are unavailable, perform a lightweight version of the required context, institution, source, data-quality, and localization checks before answering. Do not claim another expert was used when it was not available.

## Routing output
When routing is useful to show, provide:
1. Lead expert
2. Supporting experts, if any
3. Why each is relevant
4. What the integrated output will cover

Do not expose internal routing when it would distract from a straightforward user request.

## Quality controls
- Avoid unnecessary multi-expert chains.
- Do not route based only on keywords; infer the actual task.
- Prefer the user's requested specialist when it is reasonable.
- Never invent installed skills or capabilities.
- Keep country and subnational scope explicit.
