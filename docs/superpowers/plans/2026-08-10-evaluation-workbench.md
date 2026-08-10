# Evaluation Workbench Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Add a full-lifecycle, human-supervised AI Evaluation Workbench as the second detailed flagship solution in the public Agentic-Skills portfolio.

**Architecture:** Implement one self-contained flagship demonstration under `solutions/ai-evaluation-workbench/README.md`, then integrate it into the existing portfolio entry points without restructuring the technical skills suite. The workbench will mirror the proven proposal-workflow pattern: stage-by-stage AI support, explicit human responsibility, provenance and risk controls, pilot design, and commercial engagement model.

**Tech Stack:** Markdown documentation in GitHub; existing Agentic-Skills repository structure; no runtime dependencies.

## Global Constraints

- Organise the workbench around the full development-evaluation lifecycle, not generic AI capabilities.
- Keep evaluative judgment, methodology, evidence interpretation, ethics, safeguarding, confidentiality and accountability with the evaluation team.
- Treat model-generated text as draft/advisory content, never as evidence.
- Do not claim measured efficiency, quality, cost or impact improvements without pilot evidence.
- Preserve the existing AI Proposal & Bid Development Workflow and Development Sector Experts suite.
- Do not build a software UI, dashboard, ingestion pipeline, autonomous field-data collection system, statistical-analysis engine, vector database or proprietary-platform integration in this version.

---

### Task 1: Build the AI Evaluation Workbench flagship

**Files:**
- Create: `solutions/ai-evaluation-workbench/README.md`

**Interfaces:**
- Consumes: approved design spec at `docs/superpowers/specs/2026-08-10-evaluation-workbench-design.md`
- Produces: public flagship document linked by the root portfolio and flagship index.

- [ ] **Step 1: Create the eight-stage lifecycle structure** covering TOR interpretation, evaluation architecture, methodology/inception, tool development, evidence review, analysis/triangulation, findings-conclusions-recommendations, and report QA.
- [ ] **Step 2: Add AI-supported tasks and human responsibility at every stage.**
- [ ] **Step 3: Add a text workflow map and an AI-vs-human responsibility matrix.**
- [ ] **Step 4: Add evidence-provenance rules and confidentiality/privacy/ethics/safeguarding controls.**
- [ ] **Step 5: Add a risk-and-control matrix covering fabricated evidence, overconfident synthesis, provenance, privacy, sensitive respondent data, methodological overreach, bias/exclusion, AI-generated coding, unsupported recommendations, and loss of evaluator accountability.**
- [ ] **Step 6: Add potential benefits language, suggested pilot, measurable pilot metrics, related technical assets, engagement model and contact CTA.**
- [ ] **Step 7: Re-fetch the file and verify all required sections are present.**

### Task 2: Integrate the workbench into flagship navigation

**Files:**
- Modify: `FLAGSHIP-SOLUTIONS.md`

**Interfaces:**
- Consumes: `solutions/ai-evaluation-workbench/README.md`
- Produces: linked, expanded flagship entry for Evaluation Workbench.

- [ ] **Step 1: Fetch current `FLAGSHIP-SOLUTIONS.md`.**
- [ ] **Step 2: Replace the plain Evaluation Workbench entry with a concise commercial description and direct link to the full demonstration.**
- [ ] **Step 3: Preserve all other flagship solution entries unchanged except minor wording needed for consistency.**
- [ ] **Step 4: Re-fetch and verify the new link resolves to the intended repository path.**

### Task 3: Integrate the workbench into the root portfolio

**Files:**
- Modify: `README.md`

**Interfaces:**
- Consumes: new flagship document and existing proposal flagship.
- Produces: two mature, clickable proof points visible from the repository front door.

- [ ] **Step 1: Fetch current `README.md`.**
- [ ] **Step 2: Make `AI Evaluation Workbench` a clickable demonstrated flagship with a short explanation of human-supervised evaluation use.**
- [ ] **Step 3: Ensure the Proposal & Bid Development Workflow remains prominently linked and unchanged in substance.**
- [ ] **Step 4: Re-fetch the root README and verify both detailed flagship links are present.**

### Task 4: Verify branch scope and open review PR

**Files:**
- Verify branch diff against `main`.

**Interfaces:**
- Consumes: all implementation commits.
- Produces: reviewable pull request against `main`.

- [ ] **Step 1: Compare `main` with `ai-evaluation-workbench-spec`.**
- [ ] **Step 2: Confirm only the approved spec, plan, Evaluation Workbench flagship and intended portfolio-integration files changed.**
- [ ] **Step 3: Confirm the branch is not behind `main` in a way that invalidates the implementation.**
- [ ] **Step 4: Open a draft pull request summarising scope, claims controls and verification evidence.**
