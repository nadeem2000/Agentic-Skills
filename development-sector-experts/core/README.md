# Core Experts

The core experts provide reusable capabilities across the Development Sector Experts suite. Every skill works independently and can also support sector experts.

## Recommended user paths

### Beginner
Start with `development-sector-expert-router`.

### Professional who knows the sector
Start directly with the sector expert, for example `education-systems-expert`. The sector expert may use relevant core experts when available.

### Specialist task
Use a core expert directly, such as `institutional-mapping-expert` or `development-data-quality-expert`.

## Core skills

- `development-sector-expert-router` — selects the best lead and supporting experts.
- `country-context-expert` — builds decision-relevant country/subnational context.
- `institutional-mapping-expert` — maps mandates, actors, authority and relationships.
- `official-evidence-source-expert` — identifies authoritative evidence matched to claims.
- `development-data-quality-expert` — assesses reliability, comparability and fitness for purpose.
- `localization-and-language-expert` — localizes terminology, language and communication.

## Interoperability rule

Dependencies are optional. A skill may call another expert when available and materially useful, but must retain enough internal logic to complete its own core task when used alone.
