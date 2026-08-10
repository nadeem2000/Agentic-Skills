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

**Interfaces:**
- Consumes: approved design spec at `docs/superpowers/specs/2026-08-10-grant-bid-opportunity-intelligence-design.md`
- Produces: the public third flagship demonstration used by the root portfolio and flagship index.

- [ ] **Step 1: Create the positioning section** with the primary title, supporting descriptor, target users, portfolio role and shared intelligence discipline.
- [ ] **Step 2: Add the shared workflow** `Discover → Verify → Classify → Qualify → Match → Prioritise → Capture → Human decision` and explain why grant and consulting-bid qualification logic must remain separate.
- [ ] **Step 3: Build Track A — Grant Opportunity Analyst** covering opportunity discovery, official-source verification, eligibility, strategic fit, organisational capability/evidence match, partnership/consortium requirements, funding/submission pathway and prioritisation.
- [ ] **Step 4: Add a reusable Grant Opportunity Brief** containing donor/source, opportunity type, deadline, geography, thematic scope, funding, duration, eligibility, submission stage, fit, capability, gaps, partnership needs, risks, recommended next action and human decision/status.
- [ ] **Step 5: Build Track B — Consulting Bid Analyst** covering opportunity discovery, procurement-source verification, eligibility/mandatory requirements, TOR/scope decomposition, evaluation criteria, corporate experience match, expert/staffing requirements, consortium gaps, delivery/commercial risk and bid/no-bid preparation.
- [ ] **Step 6: Add a reusable Consulting Bid Intelligence Brief** containing buyer/source, procurement type, deadline, scope, deliverables, eligibility, evaluation criteria, required experience, expert requirements, consortium needs, risks, capability gaps, recommended next action and human decision/status.
- [ ] **Step 7: Add a side-by-side Grant vs Consulting Bid comparison matrix** covering opportunity format, primary qualification question, evidence needed, partnership logic, financial considerations, downstream submission type and decision owner.
- [ ] **Step 8: Add risk-and-control sections** for stale/secondary notices, fabricated eligibility, missed amendments, unsupported organisational experience, misleading fit scores, partner risk, deadline errors, procurement misclassification and AI overconfidence.
- [ ] **Step 9: Add potential benefits, pilot design, measurable pilot metrics, engagement model, related technical assets and contact CTA** without claiming unmeasured performance gains.
- [ ] **Step 10: Re-fetch the flagship file** and verify both analyst tracks, both brief templates, the comparison matrix, controls and downstream handoff are present.

### Task 2: Consolidate the opportunity-intelligence portfolio entries

**Files:**
- Modify: `FLAGSHIP-SOLUTIONS.md`

**Interfaces:**
- Consumes: `solutions/grant-bid-opportunity-intelligence-specialist/README.md`
- Produces: one mature, linked opportunity-intelligence flagship replacing the two overlapping plain entries for Development Bid Intelligence and Donor Opportunity Intelligence.

- [ ] **Step 1: Fetch current `FLAGSHIP-SOLUTIONS.md` from the feature branch.**
- [ ] **Step 2: Replace the separate Development Bid Intelligence and Donor Opportunity Intelligence entries with one `Grant & Bid Opportunity Intelligence Specialist` entry.**
- [ ] **Step 3: In that entry, explicitly show the two internal tracks: Grant Opportunity Analyst and Consulting Bid Analyst.**
- [ ] **Step 4: Add a direct link to the new full demonstration.**
- [ ] **Step 5: Preserve the AI Proposal & Bid Development Workflow as the downstream submission-development flagship and AI Evaluation Workbench as the delivery/evaluation flagship.**
- [ ] **Step 6: Re-fetch and verify terminology contains no `engine` label for the new flagship.**

### Task 3: Integrate the third commercial proof point into the root portfolio

**Files:**
- Modify: `README.md`

**Interfaces:**
- Consumes: the new opportunity-intelligence flagship and existing proposal/evaluation flagships.
- Produces: a clear three-proof-point commercial journey visible from the repository front door.

- [ ] **Step 1: Fetch current `README.md` from the feature branch.**
- [ ] **Step 2: Add the new clickable flagship to `Start here`.**
- [ ] **Step 3: Consolidate the existing opportunity-intelligence labels in the flagship section into `Grant & Bid Opportunity Intelligence Specialist`.**
- [ ] **Step 4: Explain the two tracks concisely: grants/institutional funding for NGOs/INGOs and consulting bids/tenders for firms.**
- [ ] **Step 5: Present the commercial sequence clearly as `Find & qualify opportunities → develop proposals/concept notes/bids → deliver/evaluate assignments`.**
- [ ] **Step 6: Re-fetch and verify the root README contains clickable links to the Opportunity Intelligence Specialist, AI Proposal & Bid Development Workflow and AI Evaluation Workbench.**

### Task 4: Verify scope and open review PR

**Files:**
- Verify: branch diff against `main`

**Interfaces:**
- Consumes: all feature commits.
- Produces: a reviewable pull request against `main`.

- [ ] **Step 1: Compare `main` with `grant-bid-opportunity-intelligence-spec`.**
- [ ] **Step 2: Confirm only the approved spec, plan, new flagship and intended portfolio integration files changed.**
- [ ] **Step 3: Confirm the branch is not behind `main` in a way that invalidates the implementation; if `main` moved because the Evaluation Workbench PR was merged, reconcile before final PR creation.**
- [ ] **Step 4: Verify no new flagship/public copy uses `engine` as the role label.**
- [ ] **Step 5: Open a draft pull request summarising the grant-vs-consulting distinction, professional role terminology, upstream/downstream boundaries, claims controls and verification evidence.**
