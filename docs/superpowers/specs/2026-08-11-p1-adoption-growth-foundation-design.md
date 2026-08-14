# P1 Adoption Growth Foundation Design

## Objective

Convert `Agentic-Skills` from a repository that primarily demonstrates Ahmad Nadeem's AI-integration capability into a stronger open-source adoption funnel while preserving its consulting and portfolio value.

The first implementation batch must improve the path:

**Discovery → Understand → Try → Use → Star → Fork → Contribute → Professional Enquiry**

## Scope

This batch covers four connected repository surfaces:

1. Root `README.md` adoption-first redesign.
2. Root `QUICKSTART.md` for first-use and customisation.
3. Repository-wide contribution/community infrastructure.
4. Reviewable GitHub issue and pull-request pathways for user feedback and contributions.

It does not include external promotion, automated outreach, GitHub Discussions settings, repository topics/settings changes, formal releases, or analytics automation. Those follow after the repository front door is ready.

## Design principles

- Open-source utility comes before consulting promotion in the visitor journey.
- Preserve the existing niche: AI integration for international development.
- Do not present the repository as a generic prompt library.
- Do not make unverified compatibility, ROI, performance, adoption, or impact claims.
- Keep human oversight, evidence verification, privacy and responsible-AI controls visible.
- Make individual assets independently understandable and shareable.
- Make contribution paths small, explicit and low-friction.
- Avoid keyword stuffing.

## 1. Root README architecture

The root README should be reorganised into this order:

### A. Above the fold

- Repository title: **Agentic Skills for International Development**.
- One-sentence value proposition explaining that the repository contains reusable, country-aware and evidence-conscious AI skills/workflows for international development.
- Compact audience line covering development organisations, consulting firms, NGOs/INGOs, evaluators, researchers and development professionals.
- Immediate links to **Try a skill**, **Explore flagship workflows**, **Fork and customise**, and **Contribute**.

### B. Try in 60 seconds

Use one Development Sector Expert as the default demonstration because it is a mature, reusable technical asset.

The section should show:

1. choose an expert;
2. open/copy its `SKILL.md`;
3. place it in a compatible agent/project instruction context;
4. invoke it with one realistic prompt;
5. link to `QUICKSTART.md` for platform-neutral installation/customisation.

No proprietary-platform compatibility claim should be made unless already verified.

### C. Start with these flagship assets

Expose five primary entry points:

1. Development Sector Experts.
2. Grant & Bid Opportunity Intelligence Specialist.
3. AI Proposal & Bid Development Workflow.
4. AI Evaluation Workbench.
5. Responsible AI for Development Expert.

For each: audience, problem solved, one-line hook and direct repository link.

### D. How the repository is designed

Explain the reusable design model:

**professional problem → workflow → AI skill/assistant → evidence and human-review controls → adaptation → testing/refinement**.

### E. Fork and customise

Present the adaptation journey:

**Fork → select relevant skills → add organisational/country context → test with real tasks → improve → optionally contribute upstream**.

Link to `QUICKSTART.md` and contribution guidance.

### F. Contribution/community entry points

Expose links for:

- report a problem;
- request an improvement;
- propose a sector expert;
- request a country adaptation;
- share a use case;
- contribute documentation/examples.

### G. Professional portfolio and services

Retain the existing portfolio, services, case studies, responsible-use position and collaboration options, but place them after open-source usage and contribution sections.

## 2. QUICKSTART.md

`QUICKSTART.md` should be platform-neutral and answer five questions:

1. What should I install/use first?
2. How do I use one skill?
3. How do I use a sector bundle or the full suite?
4. How do I customise a skill for my organisation or country?
5. How do I report an issue or contribute an improvement?

The guide should support both users with formal skill-capable agent environments and users who can only paste/use `SKILL.md` as structured project/system instructions.

## 3. Repository-wide contribution infrastructure

Create root-level `CONTRIBUTING.md` that acts as the repository front door and links to `development-sector-experts/CONTRIBUTING.md` for suite-specific rules.

Create `CODE_OF_CONDUCT.md` using the Contributor Covenant, with standard enforcement language and a repository-owner contact path that does not invent an email address.

Create `.github/pull_request_template.md` covering:

- what changed;
- why it creates user value;
- affected workflows/assets;
- validation performed;
- evidence/responsible-AI implications;
- confirmation that no unsupported performance or organisational-experience claims were added.

## 4. Issue forms

Create repository issue forms for:

- bug/problem report;
- feature/improvement request;
- request a sector expert;
- request a country adaptation;
- share a use case.

Forms should request enough context for maintainers to act, but should not require sensitive organisational information.

Use labels in the form metadata only when the label is known to exist; otherwise omit labels to avoid broken submission behaviour.

## 5. Calls to action

Calls to action should be natural and utility-led. Preferred language:

- **Try a skill**
- **Explore flagship workflows**
- **Fork and customise**
- **Contribute an example**
- **Request an expert**
- **Report a problem**
- **Share a use case**

Avoid aggressive star solicitation. A soft line explaining that starring helps users find the project again is acceptable, but utility must remain the primary reason to star.

## 6. Validation

Before opening the PR:

- verify all new README internal links resolve;
- verify all issue-form YAML is syntactically valid;
- verify existing flagship paths still resolve;
- confirm existing portfolio/service/case-study links remain available;
- confirm no existing Development Sector Expert files are unintentionally changed;
- compare branch against `main` and ensure the diff is limited to this adoption-growth foundation and its design/plan documentation.

## Success criteria

A first-time visitor should be able to determine within roughly one minute:

- what the repository provides;
- which asset is relevant to them;
- how to try one asset;
- how to fork/customise it;
- how to contribute or request an improvement;
- where to learn about Ahmad Nadeem's professional AI-integration capability.

The repository should remain credible as both an open-source resource and a professional demonstration environment without reading like a sales brochure.
