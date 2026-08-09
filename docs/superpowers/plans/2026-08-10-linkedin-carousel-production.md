# LinkedIn Carousel Production Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Add a standalone, reusable skill that converts source material into LinkedIn document carousels and can optionally produce the design through Canva.

**Architecture:** Keep discovery and execution logic concise in `SKILL.md`, move detailed production guidance into a reusable playbook, and include one realistic example. The skill must degrade cleanly from full Canva production to a content/design-spec deliverable without overstating capabilities.

**Tech Stack:** Markdown-based Agent Skill files; optional Canva connector/tools; current LinkedIn document-post guidance.

## Global Constraints
- Skill name: `linkedin-carousel-production`.
- Default production canvas: 4:5 portrait, 1080 × 1350 px.
- Treat 1080 × 1350 as a design default, not a LinkedIn-mandated PDF dimension.
- Prefer PDF for LinkedIn document-post delivery.
- Never fabricate claims, statistics, quotations, sources, or platform requirements.
- Never claim Canva/PDF production succeeded unless an actual design/file was created.

---

### Task 1: Core skill

**Files:**
- Create: `linkedin-carousel-production/SKILL.md`

**Interfaces:**
- Consumes: user topic/source/brief, optional brand information, available design/research tools.
- Produces: carousel plan, slide copy, visual directions, packaging copy, and optional actual design/PDF.

- [ ] **Step 1: Define evaluation scenario**

Use this scenario to test the unassisted behavior before reviewing the skill instructions: “Turn a 12-page development-sector report into a LinkedIn carousel for senior NGO leaders. Preserve evidence, use a strong hook, keep slides mobile-readable, and create it in Canva if possible.” Check whether the agent explicitly handles source verification, slide narrative, visual hierarchy, PDF packaging, caption, and graceful fallback.

- [ ] **Step 2: Create minimal SKILL.md**

Write frontmatter with a discovery-only `Use when...` description, then define operating modes, workflow, output contract, and QA gates.

- [ ] **Step 3: Verify skill shape**

Check that the description contains triggers rather than workflow summary; check that full-production and fallback behavior are unambiguous; check that completion claims require an actual artifact.

- [ ] **Step 4: Commit**

Commit the core skill file.

### Task 2: Production playbook

**Files:**
- Create: `linkedin-carousel-production/references/carousel-playbook.md`

**Interfaces:**
- Consumes: the core skill’s workflow stages.
- Produces: detailed narrative, copy, design, sourcing, Canva, LinkedIn packaging, accessibility, and QA guidance.

- [ ] **Step 1: Write playbook**

Include hook patterns, slide sequence patterns, text-density guidance, design defaults, brand handling, cross-slide continuity, evidence discipline, Canva production rules, LinkedIn document-post requirements, caption structure, and preflight QA.

- [ ] **Step 2: Validate current LinkedIn rules**

Ensure time-sensitive platform details are framed as a current baseline and instruct future agents to re-check LinkedIn Help when accuracy matters.

- [ ] **Step 3: Commit**

Commit the playbook.

### Task 3: Human documentation and example

**Files:**
- Create: `linkedin-carousel-production/README.md`
- Create: `linkedin-carousel-production/examples/development-sector-carousel.md`

**Interfaces:**
- Consumes: skill contract and playbook.
- Produces: user-facing installation/use guidance and a concrete model output.

- [ ] **Step 1: Write README**

Explain purpose, inputs, modes, outputs, sample prompts, and folder structure.

- [ ] **Step 2: Write example**

Show an evidence-led development-sector carousel from objective through slides, design directions, caption, and QA.

- [ ] **Step 3: Verify example against skill**

Confirm the example follows one-idea-per-slide, source discipline, practical 4:5 design default, and packaging requirements.

- [ ] **Step 4: Commit**

Commit README and example.

### Task 4: Repository integration and final verification

**Files:**
- Modify: `README.md`

**Interfaces:**
- Consumes: finished skill folder.
- Produces: discoverable repository entry.

- [ ] **Step 1: Update root README**

Add a “Content & Communications Skills” section linking to `linkedin-carousel-production/`.

- [ ] **Step 2: Repository verification**

Fetch each new file from the branch, confirm paths and frontmatter, compare branch against `main`, and inspect the diff for accidental unrelated changes.

- [ ] **Step 3: Commit**

Commit repository catalogue update.

- [ ] **Step 4: Open draft PR**

Open a draft pull request to `main` summarizing scope, design defaults, verification, and the optional Canva path.
