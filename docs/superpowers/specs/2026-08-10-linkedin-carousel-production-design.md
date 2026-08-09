# LinkedIn Carousel Production Skill — Design

## Goal
Create a reusable skill that turns a topic, source document, article, report, campaign brief, or rough idea into a LinkedIn-ready document carousel, with an optional Canva production path and a content/design-spec fallback.

## Scope
The skill will support two modes:

1. **Full production mode** — develop the carousel narrative and copy, create or adapt the visual design in Canva when suitable design tooling is available, prepare/export a LinkedIn-ready PDF, and provide the accompanying post copy and document title.
2. **Content + design-spec mode** — provide publication-ready slide copy, page-by-page visual direction, design specifications, document title, caption, accessibility guidance, and export instructions when direct design production is unavailable or not requested.

The skill is standalone and will live outside the Development Sector Experts collection.

## Inputs
The skill must work from any of the following:
- a topic or idea;
- pasted source text;
- an uploaded document/report/newsletter;
- a public article or webpage;
- a campaign, brand, or communications brief;
- an existing carousel that needs improvement or repurposing.

It should infer reasonable defaults when minor information is missing and ask only when a missing decision materially changes the output.

## Content architecture
The skill will convert source material into a swipe-oriented narrative rather than simply splitting paragraphs across pages. Default structure:

1. Cover / hook
2. Problem, tension, or promise
3. Context / why it matters
4. Core insight sequence
5. Evidence, example, framework, or application
6. Practical takeaway(s)
7. Summary / synthesis
8. CTA / closing

The exact slide count is content-driven. A typical carousel should be concise; the skill should not pad a weak idea to reach a fixed number of slides.

## Design architecture
Default page format: **4:5 portrait, 1080 × 1350 px**, used as a practical visual-production default rather than a claim that LinkedIn mandates this exact PDF page size.

Design rules:
- one dominant idea per slide;
- mobile-readable typography;
- strong cover hierarchy;
- controlled text density;
- consistent grid, margins, typography, and visual language;
- optional cross-slide continuity devices, used only when they improve flow;
- brand colors, logo, and typography when supplied or available;
- visuals should clarify the idea rather than decorate empty space;
- avoid generic AI-looking layouts, excessive icons, and text-heavy pages.

## LinkedIn packaging
The skill will treat the carousel as a LinkedIn **document post**. It will prefer PDF for final delivery and include a clear document title and accompanying post copy. Platform-specific limits and upload guidance must be verified against current LinkedIn Help when current accuracy matters.

Current official baseline at design time (10 August 2026): LinkedIn supports PDF, PPT/PPTX, DOC/DOCX document uploads, with a maximum file size of 100 MB and 300 pages; PDFs should use consistent page sizes and be flattened where necessary. LinkedIn posts allow up to 3,000 characters of post text.

## Canva production path
When Canva creation tools are available, the skill should:
- use an existing brand kit/template when the user explicitly wants brand alignment and one is available;
- otherwise generate a coherent visual design from the approved carousel brief;
- keep all pages visually consistent;
- review text fit, hierarchy, spacing, and sequence before export;
- export/prepare a PDF suitable for LinkedIn document upload where export capabilities permit.

If Canva cannot reliably create the complete multi-page carousel in the available environment, the skill must fall back to content + design-spec mode rather than claiming completion.

## Source discipline
When factual claims are based on external or time-sensitive information, the skill must verify them with credible sources appropriate to the topic. It should distinguish sourced facts from interpretation and avoid inventing statistics, quotes, platform rules, or attribution.

## Output contract
A completed run should produce as applicable:
1. Carousel objective and target audience
2. Recommended title/hook
3. Slide-by-slide copy
4. Slide-by-slide visual/layout direction
5. Design system/specification
6. LinkedIn document title
7. LinkedIn post caption
8. CTA
9. Source/citation notes when evidence is used
10. Canva design/PDF when full production succeeds
11. Final QA checklist

## Quality gates
Before completion, verify:
- the first slide earns the swipe;
- each slide advances the story;
- no slide is overloaded;
- statistics and quotations are traceable;
- page numbering and sequence are correct;
- typography is readable on mobile;
- visual continuity is intentional;
- CTA matches the communication objective;
- document title and caption are supplied;
- the PDF has consistent page dimensions and is suitable for upload;
- the skill never claims to have designed/exported a file when it only produced instructions.

## Files
- `linkedin-carousel-production/SKILL.md` — compact agent operating instructions.
- `linkedin-carousel-production/README.md` — human-facing overview and usage.
- `linkedin-carousel-production/references/carousel-playbook.md` — detailed content, design, LinkedIn, Canva, and QA guidance.
- `linkedin-carousel-production/examples/development-sector-carousel.md` — realistic end-to-end example.
- root `README.md` — add the skill to the repository catalogue.
