# P1 Adoption Growth Foundation Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Make the repository front door adoption-first so a new visitor can understand, try, adapt and contribute to Agentic-Skills within roughly one minute while preserving professional portfolio value.

**Architecture:** Keep the existing repository structure and technical assets intact. Improve only the visitor-facing root documentation and repository-wide contribution surfaces, with platform-neutral guidance and reviewable GitHub issue/PR forms.

**Tech Stack:** Markdown, GitHub issue-form YAML, GitHub repository documentation.

## Global Constraints

- Open-source utility comes before consulting promotion in the visitor journey.
- Preserve the niche: AI integration for international development.
- Do not present the repository as a generic prompt library.
- Do not add unverified compatibility, ROI, performance, adoption or impact claims.
- Keep human oversight, evidence verification, privacy and responsible-AI controls visible.
- Make individual assets independently understandable and shareable.
- Keep contribution paths small, explicit and low-friction.
- Avoid keyword stuffing.
- Do not change existing Development Sector Expert skill files in this batch.

---

### Task 1: Rebuild the root README around adoption

**Files:**
- Modify: `README.md`

**Produces:** An adoption-first landing page with a one-minute visitor journey.

- [ ] Reorder the opening into: title/value proposition → audience → immediate actions → Try in 60 seconds → five flagship assets.
- [ ] Add direct actions for `QUICKSTART.md`, flagship workflows, fork/customise, and contribution guidance.
- [ ] Use one Development Sector Expert as the 60-second example and avoid platform-specific compatibility claims.
- [ ] Add the reusable design model: professional problem → workflow → AI skill/assistant → evidence/human controls → adaptation → testing/refinement.
- [ ] Add a visible fork/customise journey.
- [ ] Add community/request pathways.
- [ ] Retain portfolio, services, case studies, responsible-use text and collaboration/contact material below the open-source sections.
- [ ] Verify every relative link in the revised README points to an existing repository path.

### Task 2: Add platform-neutral quick start

**Files:**
- Create: `QUICKSTART.md`

**Produces:** A concise first-use and customisation guide.

- [ ] Explain how to choose a first skill or use the router when unsure.
- [ ] Explain single-skill use using `SKILL.md`.
- [ ] Explain sector-bundle and full-suite use.
- [ ] Explain use in formal skill-capable environments and as structured project/system instructions where formal loading is unavailable.
- [ ] Add organisation and country customisation guidance that preserves evidence, privacy and human-review controls.
- [ ] Link to root contribution guidance and relevant suite installation/examples documentation.

### Task 3: Add repository-wide contribution standards

**Files:**
- Create: `CONTRIBUTING.md`
- Create: `CODE_OF_CONDUCT.md`
- Create: `.github/pull_request_template.md`

**Produces:** A repository-level participation front door.

- [ ] Create a concise root contribution guide covering documentation, examples, country use cases, new experts, interoperability and workflow demonstrations.
- [ ] Link to `development-sector-experts/CONTRIBUTING.md` for suite-specific design rules.
- [ ] Add Contributor Covenant-based code of conduct with repository-based enforcement/contact path and no invented email address.
- [ ] Add PR template sections for user value, affected assets, validation, evidence/responsible-AI implications and unsupported-claim confirmation.

### Task 4: Add issue forms for substantive participation

**Files:**
- Create: `.github/ISSUE_TEMPLATE/bug_report.yml`
- Create: `.github/ISSUE_TEMPLATE/feature_request.yml`
- Create: `.github/ISSUE_TEMPLATE/request_sector_expert.yml`
- Create: `.github/ISSUE_TEMPLATE/request_country_adaptation.yml`
- Create: `.github/ISSUE_TEMPLATE/use_case_showcase.yml`

**Produces:** Structured request and feedback pathways without requiring sensitive information.

- [ ] Add bug/problem form with reproducibility context.
- [ ] Add improvement form focused on user/workflow value.
- [ ] Add sector-expert request form requiring the professional problem, likely users and expected outputs.
- [ ] Add country-adaptation form requesting geography, workflow and localisation need while warning against sharing sensitive organisational data.
- [ ] Add use-case showcase form for real adaptations, lessons and optional links.
- [ ] Omit label metadata unless an existing repository label is verified.
- [ ] Ensure all forms contain `name`, `description`, `title`, `body` and valid field IDs.

### Task 5: Validate the adoption foundation

**Files:**
- Review all files created/modified in Tasks 1–4 plus the approved spec and this plan.

**Produces:** A clean, limited branch suitable for a draft PR.

- [ ] Fetch every README and QUICKSTART relative-link target to confirm it exists.
- [ ] Inspect each issue-form YAML for required GitHub issue-form structure and unique field IDs.
- [ ] Compare `agent/p1-adoption-growth-foundation` against `main` and confirm no Development Sector Expert `SKILL.md` files changed.
- [ ] Confirm the diff contains only the adoption-growth documentation/community surfaces plus approved design/plan docs.
- [ ] Open a draft PR targeting `main` with summary, user impact, validation and follow-on items that remain out of scope.
