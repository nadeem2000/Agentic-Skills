# Case Study: Building a 29-Skill Development Sector Expert System

## Challenge

Development-sector work frequently requires multiple kinds of professional judgment at the same time: country context, institutions, source quality, data interpretation, sector expertise, localisation, inclusion and responsible use of AI.

A generic prompt can produce useful text, but it does not reliably encode these requirements as repeatable operating rules. The challenge was to turn recurring development-sector reasoning and quality controls into a reusable AI architecture that could support multiple sectors and professional workflows.

## Existing process

Without a structured skill system, users may repeatedly instruct a general-purpose model to:

- establish country and subnational context;
- identify relevant institutions;
- prioritise authoritative evidence;
- compare conflicting statistics;
- adapt terminology to local context;
- apply sector-specific frameworks;
- avoid fabrication;
- consider privacy, safeguarding and inclusion;
- retain human oversight.

These instructions can become inconsistent across tasks, users and sessions.

## AI-enabled intervention

The repository's **Development Sector Experts** collection packages these recurring requirements into a modular set of **29 country-aware AI expert skills**.

The system combines:

- a core layer for routing, country context, institutional mapping, evidence sourcing, data quality and localisation;
- Human Development experts;
- Climate & Environment experts;
- Economic Development experts;
- Governance & Protection experts;
- Digital Development experts, including Responsible AI for Development.

Each expert is designed to work independently while being able to draw on supporting experts where available.

## Workflow architecture

```text
User task
   ↓
Lead sector / workflow expert
   ↓
Country and subnational grounding
   ↓
Institutional context
   ↓
Evidence and data-quality controls
   ↓
Sector-specific analysis
   ↓
Localisation / inclusion / risk checks
   ↓
Professional output
   ↓
Human review and decision
```

Users who are unsure which expert applies can start with the Development Sector Expert Router. Users with a clear task can invoke the relevant specialist directly.

## Controls built into the design

The public skill documentation establishes a common set of quality expectations, including:

- avoidance of fabricated policies, institutions, statistics, citations and programme experience;
- separation of policy commitments from implementation reality;
- attention to year, geography, population and definitions behind key statistics;
- identification of uncertainty and evidence gaps;
- careful handling of sensitive data;
- gender, disability, safeguarding, protection and inclusion considerations where relevant;
- avoidance of technology-first recommendations;
- human review for high-consequence outputs.

The Responsible AI for Development Expert further structures AI adoption around value, risk, data, human oversight, evidence, workflow design, governance, adoption and monitoring.

## Observed result

The repository now contains a documented public-release candidate consisting of **29 expert skills**, plus routing guidance, installation instructions, usage examples, licensing, attribution and contribution standards.

This is directly verifiable in the repository and demonstrates the ability to convert a broad professional domain into a structured, reusable AI skill architecture.

## Potential organisational benefit

When adapted to an organisation, this architecture could potentially help:

- standardise how staff approach recurring analytical tasks;
- make evidence and non-fabrication controls more explicit;
- reduce dependence on improvised prompting;
- improve reuse of sector and workflow guidance;
- create a foundation for organisation-specific AI assistants;
- support staff training around repeatable AI practices;
- make responsible-use controls part of the workflow rather than an afterthought.

These benefits have not been presented here as measured client outcomes. They would need to be tested in an organisational pilot.

## Transferability

The architecture can be adapted for:

- development consulting firms;
- NGOs and INGOs;
- evaluation and research organisations;
- donor-funded programme teams;
- thematic centres of expertise;
- university/research teams;
- independent consulting practices.

An organisation could retain the same modular approach while replacing public generic guidance with its own approved methods, terminology, templates, evidence sources, quality checks and access rules.

## Related technical evidence

- [Development Sector Experts overview](../development-sector-experts/README.md)
- [Routing guide](../development-sector-experts/ROUTING-GUIDE.md)
- [Installation](../development-sector-experts/INSTALLATION.md)
- [Usage examples](../development-sector-experts/EXAMPLES.md)
- [Responsible AI for Development Expert](../development-sector-experts/digital-development/responsible-ai-for-development-expert/SKILL.md)

## Commercial application

This case demonstrates the underlying method used in the **Custom AI Skills & Assistants** and **Responsible AI Adoption & Capacity Building** services: identify a recurring professional workflow, make the quality requirements explicit, package the workflow into a reusable capability, test it, and refine it under human oversight.

See [AI Integration Services](../SERVICES.md).

## Contact

For discussion about adapting a similar skill architecture to a development organisation or consulting practice, visit the [GitHub profile](https://github.com/nadeem2000) for current public contact links or open a repository issue beginning **AI integration enquiry:**.
