# AI Integration Portfolio Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Transform the repository front door from a skills-library presentation into a client-facing AI Integration Specialist portfolio while preserving the existing Development Sector Experts suite.

**Architecture:** Use a dual-layer structure. The root repository becomes the professional portfolio and conversion layer; `development-sector-experts/` remains the technical evidence base. New solution, service, case-study, and resource pages link down to the existing skills rather than duplicating them.

**Tech Stack:** GitHub Markdown, existing repository content, GitHub links.

## Global Constraints

- Preserve the existing Development Sector Experts suite and its technical documentation.
- Do not exaggerate technical qualifications or claim unverified client outcomes.
- Present Ahmad Nadeem as an AI Integration Specialist for international development, not as a generic prompt engineer.
- Prioritize real organisational workflows: proposals, business development, research, evaluation, donor intelligence, knowledge management, communications, productivity, and responsible AI.
- Use clear calls to action without inventing private contact information.
- Distinguish observed results from potential benefits.

---

### Task 1: Rebuild the repository front door

**Files:**
- Modify: `README.md`

**Interfaces:**
- Consumes: existing Development Sector Experts links and repository structure.
- Produces: the 30-second market-facing landing page that routes visitors to portfolio, services, flagship solutions, case studies, resources, and technical skills.

- [ ] Replace the generic skills-library opening with the AI Integration Specialist positioning statement.
- [ ] Add clear audience, problem, capability, proof, and contact sections.
- [ ] Preserve direct access to the Development Sector Experts suite.
- [ ] Verify all relative links resolve to files created in this branch.

### Task 2: Add professional portfolio and services pages

**Files:**
- Create: `PORTFOLIO.md`
- Create: `SERVICES.md`

**Interfaces:**
- Consumes: root positioning and existing skill suite.
- Produces: client-facing explanation of professional value and engagement options.

- [ ] Document the development-sector/AI intersection and practical capability areas.
- [ ] Define six service lines with client problem, deliverables, engagement format, and intended outcome.
- [ ] Add responsible claims language and contact route.

### Task 3: Package flagship solutions

**Files:**
- Create: `FLAGSHIP-SOLUTIONS.md`
- Create: `solutions/ai-proposal-bid-development/README.md`

**Interfaces:**
- Consumes: relevant existing skills and workflow examples.
- Produces: eight solution concepts plus one fully documented flagship demonstration.

- [ ] Define eight professionally named solutions with target audience, problem, workflow, benefit, evidence/control model, and next action.
- [ ] Fully document the AI Proposal & Bid Development Workflow as the first showcase solution.
- [ ] Avoid unsupported savings or performance percentages.

### Task 4: Add case-study proof layer

**Files:**
- Create: `case-studies/README.md`
- Create: `case-studies/development-sector-expert-system.md`

**Interfaces:**
- Consumes: public repository evidence only.
- Produces: a reusable case-study format and one substantiated portfolio case.

- [ ] Create case-study standards separating observed facts from potential benefits.
- [ ] Document the Development Sector Experts suite as a portfolio case using verifiable repository facts.

### Task 5: Add first lead magnet

**Files:**
- Create: `resources/25-ai-workflows-for-development-organisations.md`

**Interfaces:**
- Consumes: service architecture and existing responsible-AI skill scope.
- Produces: a practical shareable resource that links back to services and technical evidence.

- [ ] Provide 25 concrete workflow opportunities grouped by organisational function.
- [ ] Add risk/human-review reminders.
- [ ] End with a professional engagement CTA.

### Task 6: Verify and prepare review

**Files:**
- Verify all files above.

**Interfaces:**
- Consumes: completed branch.
- Produces: reviewable pull request with no broken portfolio links.

- [ ] Fetch each created/modified file from the branch.
- [ ] Compare branch with `main` and verify only intended portfolio/documentation changes are present.
- [ ] Open a draft pull request for review.
