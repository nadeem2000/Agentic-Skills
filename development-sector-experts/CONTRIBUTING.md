# Contributing

Contributions that improve the practical usefulness, accuracy, portability, or responsible use of Development Sector Experts are welcome.

## Good contributions

Examples include:

- field-tested prompt examples;
- country-specific edge cases that reveal overly generic assumptions;
- improved evidence and data-quality safeguards;
- clearer skill-discovery descriptions;
- stronger sector frameworks;
- additional quality-control checks;
- accessibility, safeguarding, privacy, or inclusion improvements;
- corrections to terminology;
- interoperability improvements that do not create hard dependencies.

## Design rules

Contributions should preserve these principles:

1. **Standalone operation** — a sector expert must remain useful when installed alone.
2. **Optional interoperability** — supporting experts may deepen a task but should not be required for basic operation.
3. **Country awareness** — avoid importing institutional or policy assumptions from another country without evidence.
4. **Evidence discipline** — prioritize authoritative and fit-for-purpose sources.
5. **Non-fabrication** — never instruct an agent to invent missing statistics, policies, institutions, citations, or experience.
6. **Professional value** — skills should solve real workflows, not merely emulate a persona.
7. **Responsible use** — include privacy, safeguarding, inclusion, human oversight, or other controls where the domain requires them.
8. **Portable Markdown** — avoid unnecessary dependency on one proprietary runtime.

## Skill structure

At minimum:

```text
expert-name/
├── SKILL.md
└── README.md   # recommended for sector experts
```

`SKILL.md` should include valid YAML frontmatter with:

```yaml
---
name: expert-name
description: Use when ...
---
```

Keep names descriptive and kebab-case. Descriptions should explain **when the skill should be used**, rather than summarizing its entire workflow.

## Quality checklist

Before proposing a change, check:

- Does the folder name match the `name` field?
- Does the description begin with a clear usage trigger?
- Can the expert work independently?
- Are optional supporting experts actually optional?
- Are country and subnational differences handled?
- Are current or high-stakes facts expected to be verified when tools are available?
- Are major failure modes explicitly addressed?
- Is there a clear professional output or decision use?
- Are sensitive-data, safeguarding, or inclusion issues handled where relevant?
- Are examples free of fabricated facts?

## Pull requests

Keep changes focused. Explain:

- what changed;
- why it creates user value;
- which workflows it affects;
- how the change was validated.
