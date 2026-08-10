# Grant & Bid Opportunity Intelligence Specialist Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Add a third mature commercial proof point that helps development organisations and consulting firms discover, verify, qualify, prioritise and prepare for grant and consulting opportunities through two clearly separated professional analyst tracks.

**Architecture:** Implement one self-contained flagship under `solutions/grant-bid-opportunity-intelligence-specialist/README.md`. The flagship uses a shared intelligence sequence—Discover → Verify → Classify → Qualify → Match → Prioritise → Capture → Human decision—then branches into a Grant Opportunity Analyst pathway and a Consulting Bid Analyst pathway with different qualification logic, outputs and controls. Integrate the new flagship into the root portfolio and flagship index while preserving the downstream AI Proposal & Bid Development Workflow as a separate submission-development proof point.

**Tech Stack:** Markdown documentation in GitHub; existing Agentic-Skills repository structure; no runtime dependencies.

## Global Constraints

- Primary title: **Grant & Bid Opportunity Intelligence Specialist**.
- Internal tracks: **Grant Opportunity Analyst** and **Consulting Bid Analyst**.
- Avoid machine-centric labels such as **engine**; prefer **specialist**, **analyst**, **expert**, **adviser** and **reviewer** where appropriate.
- Keep grant/institutional-funding opportunities distinct from consulting/professional-service procurements.
- Use the source document's own opportunity terminology rather than forcing all grant opportunities into an RFP label.
- Treat opportunity intelligence as upstream of proposal/concept-note/bid development.
- Require official-source verification for material opportunity details before action.
- Do not claim autonomous pursue/no-pursue decisions; final decisions remain human.
- Do not invent eligibility, donor rules, procurement requirements, funding values, deadlines, organisational capability, experience, experts or partner credentials.
- Preserve the existing AI Proposal & Bid Development Workflow and AI Evaluation Workbench.
- Do not build automated scraping, autonomous submission, procurement portals, CRM software, databases or dashboards in this version.

---

### Task 1: Build the flagship specialist

**Files:**
- Create: `solutions/grant-bid-opportunity-intelligence-specialist/README.md`

- [ ] Create positioning, target users, portfolio role and shared intelligence discipline.
- [ ] Add the shared workflow and explain separate grant vs consulting-bid qualification logic.
- [ ] Build Track A — Grant Opportunity Analyst with eight stages.
- [ ] Add a reusable Grant Opportunity Brief.
- [ ] Build Track B — Consulting Bid Analyst with eight stages.
- [ ] Add a reusable Consulting Bid Intelligence Brief.
- [ ] Add a Grant vs Consulting Bid comparison matrix.
- [ ] Add AI/human responsibility, risk/control and transparent scoring guidance.
- [ ] Add potential benefits, pilot design, measurable metrics, engagement model, related assets and CTA.
- [ ] Re-fetch and verify the flagship against the approved design.

### Task 2: Consolidate opportunity-intelligence portfolio entries

**Files:**
- Modify: `FLAGSHIP-SOLUTIONS.md`

- [ ] Replace separate Development Bid Intelligence and Donor Opportunity Intelligence entries with one **Grant & Bid Opportunity Intelligence Specialist** entry.
- [ ] Explicitly show the **Grant Opportunity Analyst** and **Consulting Bid Analyst** tracks.
- [ ] Add a direct link to the full demonstration.
- [ ] Preserve the AI Proposal & Bid Development Workflow and AI Evaluation Workbench.
- [ ] Re-fetch and verify professional role terminology; no machine-centric `engine` label for the new flagship.

### Task 3: Integrate the third commercial proof point into the root portfolio

**Files:**
- Modify: `README.md`

- [ ] Add the new clickable flagship to `Start here`.
- [ ] Consolidate existing opportunity-intelligence labels into **Grant & Bid Opportunity Intelligence Specialist**.
- [ ] Explain the two tracks concisely.
- [ ] Present the commercial sequence: `Find & qualify opportunities → develop proposals/concept notes/bids → deliver/evaluate assignments`.
- [ ] Re-fetch and verify clickable links to all three mature proof points.

### Task 4: Verify scope and open review PR

- [ ] Compare the feature branch with its Evaluation Workbench base branch and with `main` for lineage awareness.
- [ ] Confirm only approved spec, plan, new flagship and intended portfolio integration files are added beyond the Evaluation Workbench dependency.
- [ ] Verify no new flagship/public copy uses `engine` as the role label.
- [ ] Open a draft stacked pull request against `ai-evaluation-workbench-spec`, summarising the grant-vs-consulting distinction, terminology, boundaries and claims controls.
