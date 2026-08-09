# Installation and Setup

Development Sector Experts are plain-text AI skill packages built around `SKILL.md`. How you install them depends on your agent platform.

## Option 1: Download one expert

Use this when you need only one specialist.

1. Open the folder for the expert you want.
2. Download its `SKILL.md` and any supporting files in the same folder.
3. Place the folder in the skills directory recognized by your AI agent or development environment.
4. Restart or refresh the agent if required by that platform.
5. Invoke the expert with a task that matches its description.

Example:

```text
education-systems-expert/
├── SKILL.md
└── README.md
```

The expert is designed to work independently.

## Option 2: Download one sector family

Use this when you work repeatedly in one thematic area.

For example, a climate/WASH consultant may install:

```text
climate-environment/
├── climate-resilience-expert/
├── water-security-expert/
├── wash-expert/
├── disaster-risk-reduction-expert/
└── biodiversity-expert/
```

For stronger country and evidence support, also install the `core/` folder.

## Option 3: Install the full suite

Use this for organizations, consulting firms, multidisciplinary professionals, or users who want cross-sector workflows.

Clone the repository:

```bash
git clone https://github.com/nadeem2000/Agentic-Skills.git
```

Then copy or point your agent to:

```text
development-sector-experts/
```

The full suite gives the sector experts access to the shared core layer and neighboring specialists.

## Option 4: Download from GitHub without Git

1. Open the repository on GitHub.
2. Select **Code**.
3. Choose **Download ZIP**.
4. Extract the archive.
5. Copy the required expert folders into your platform's skill directory.

## Suggested installations by user type

### Individual consultant

Install:

- your main sector expert;
- `country-context-expert`;
- `institutional-mapping-expert`;
- `official-evidence-source-expert`;
- `development-data-quality-expert`.

### NGO or consulting firm

Install the full suite if your work spans sectors. Start with the router for unfamiliar or cross-sector assignments.

### Researcher or evaluator

A useful base package is:

- `official-evidence-source-expert`;
- `development-data-quality-expert`;
- `country-context-expert`;
- relevant sector expert(s).

### AI integration or digital-transformation practitioner

Install:

- `responsible-ai-for-development-expert`;
- `digital-development-expert`;
- relevant sector expert(s);
- core evidence and data-quality experts.

## How to invoke an expert

You can explicitly name the skill:

```text
Use the Education Systems Expert to review this programme concept for Pakistan.
```

Or, on platforms with skill discovery, simply ask the task naturally and allow the agent to select the matching skill.

## Standalone and integrated use

Every sector expert contains enough internal guidance to work alone.

When supporting experts are installed, the lead expert may use them for additional depth. For example:

```text
education-systems-expert
+ country-context-expert
+ institutional-mapping-expert
+ official-evidence-source-expert
+ development-data-quality-expert
```

You generally should not invoke all supporting experts manually.

## Platform compatibility

The skills are intentionally written as portable Markdown instructions rather than tied to one proprietary runtime. However, skill discovery, automatic loading, tool access, web search, file access, and multi-skill orchestration vary by platform.

If a platform does not support automatic skills, you can still use a `SKILL.md` as a structured system/project instruction or reference prompt.

## Important limitation

Installing an expert does not automatically provide external tools. Current web research, file reading, spreadsheets, databases, or connected services depend on the capabilities of the AI platform where the skill is used.
