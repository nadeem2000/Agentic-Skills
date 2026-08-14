# Quick Start

This guide is for people who want to try, adapt or reuse one or more Agentic-Skills without first reading the entire repository.

## 1. What should I use first?

If you already know the workflow or sector you need, start with that asset directly.

Examples:

- education, health, climate, governance or other sector analysis: [Development Sector Experts](development-sector-experts/README.md);
- grant or consulting opportunity qualification: [Grant & Bid Opportunity Intelligence Specialist](solutions/grant-bid-opportunity-intelligence-specialist/README.md);
- proposal or bid development: [AI Proposal & Bid Development Workflow](solutions/ai-proposal-bid-development/README.md);
- evaluation work: [AI Evaluation Workbench](solutions/ai-evaluation-workbench/README.md);
- organisational AI use cases, risk and governance: [Responsible AI for Development Expert](development-sector-experts/digital-development/responsible-ai-for-development-expert/SKILL.md).

If you are unsure which development-sector expert applies, start with the [Development Sector Expert Router](development-sector-experts/core/development-sector-expert-router/SKILL.md).

## 2. Use one skill

Each expert skill is primarily a Markdown instruction package centred on `SKILL.md`.

A simple first test is:

1. open the relevant skill folder;
2. copy or download its `SKILL.md`;
3. place it in the skill/instruction location supported by your agent environment, if one exists;
4. otherwise use the `SKILL.md` content as structured project/system guidance in an environment that permits such instructions;
5. give the expert a real task with the country, audience, decision and source documents where relevant.

Example:

```text
Use the Education Systems Expert to review this education programme concept for Pakistan. Identify evidence gaps, institutional assumptions, implementation risks, inclusion issues and improvements needed before donor submission.
```

The repository does not assume that every AI platform supports automatic skill discovery, file tools, current web research or multi-skill orchestration. Those capabilities depend on the environment where you use the instructions.

## 3. Use a sector bundle or the full suite

For recurring work in one thematic area, copy the relevant family from `development-sector-experts/` together with useful core experts.

For multidisciplinary work, clone the repository:

```bash
git clone https://github.com/nadeem2000/Agentic-Skills.git
```

Then use the relevant folders from:

```text
development-sector-experts/
```

For more detail, see [Development Sector Experts installation](development-sector-experts/INSTALLATION.md), [routing guidance](development-sector-experts/ROUTING-GUIDE.md) and [usage examples](development-sector-experts/EXAMPLES.md).

## 4. Customise for your organisation or country

Treat the repository as a starting architecture, not a fixed black box.

A useful adaptation sequence is:

```text
Select the relevant skill
        ↓
Identify the real workflow and decision points
        ↓
Add country / subnational context
        ↓
Add approved organisational terminology and process rules
        ↓
Define evidence and source requirements
        ↓
Define privacy / confidentiality boundaries
        ↓
Define human approval points
        ↓
Test on realistic non-sensitive tasks
        ↓
Refine based on observed failure modes
```

When adapting a skill:

- do not embed confidential proposals, personal data or restricted organisational information in a public fork;
- distinguish organisational practice from general sector guidance;
- require verification for current policies, institutions, statistics and other changeable facts;
- retain human review for consequential recommendations or decisions;
- preserve non-fabrication, safeguarding, privacy, inclusion and evidence controls that are material to the workflow;
- document important local terminology, administrative structures and assumptions rather than silently importing them from another country.

## 5. Fork and maintain your adaptation

A practical organisation-level workflow is:

1. fork the repository;
2. select only the assets you actually need;
3. create organisation- or country-specific additions in clearly named files or folders;
4. test changes against representative tasks;
5. record why the adaptation was made;
6. periodically compare upstream improvements;
7. contribute generally useful fixes or examples back to the public repository where appropriate.

Avoid publishing proprietary or sensitive organisational material merely to demonstrate an adaptation.

## 6. Report a problem or contribute

Use the repository issue forms to:

- report a reproducible problem;
- request an improvement;
- request a new sector expert;
- request a country adaptation;
- share a non-sensitive use case.

For code, documentation, examples and skill improvements, read the root [CONTRIBUTING.md](CONTRIBUTING.md). Contributors working specifically on Development Sector Experts should also follow the [suite-specific contribution rules](development-sector-experts/CONTRIBUTING.md).

## Good input produces better professional output

Where relevant, give the skill:

- country and subnational area;
- intended audience;
- decision or output required;
- source documents or data;
- donor/institutional requirements;
- time period;
- constraints such as budget, team size, word count or implementation horizon.

Do not provide sensitive information unless the AI environment and your organisation's rules permit it.
