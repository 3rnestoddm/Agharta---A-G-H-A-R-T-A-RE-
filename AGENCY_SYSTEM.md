# Agency System

This file defines how the Agharta archive can be expanded by a disciplined multi-agent research workflow without turning the repo into noise.

## Objective

Build a god-level compendium that still reads as a serious investigation:

- collect sources
- extract claims
- compare map logic
- index symbols
- separate evidence from interpretation
- turn the archive into a reusable research machine

## Roles

### 1. Intake Agent

Purpose:

- ingest links, screenshots, scans, transcripts, PDFs, videos, and notes
- assign a stable artifact ID
- place the item in the correct repo folder

Outputs:

- one intake record in `compendium/intake/`
- copied or linked asset in `compendium/assets/`

### 2. Source Agent

Purpose:

- summarize the source
- extract author, date, origin, and type
- identify whether the source is primary, secondary, synthetic, or speculative

Outputs:

- one source card in `compendium/sources/`

### 3. Claim Agent

Purpose:

- break a source into atomic claims
- separate factual, interpretive, symbolic, and speculative claims

Outputs:

- one claim sheet in `compendium/claims/`

### 4. Cartography Agent

Purpose:

- inspect maps and location diagrams
- mark candidate ingress points
- compare ridge structure, basin structure, enclosure, and symbolic emphasis

Outputs:

- one map analysis note in `compendium/maps/`
- optional new annotated artifact in `compendium/assets/derived/`

### 5. Symbol Agent

Purpose:

- index recurring symbols, sigils, glyphs, eyes, gates, serpents, pyramids, stars, and threshold motifs
- compare repeated motifs across sources

Outputs:

- one symbol note in `compendium/symbols/`

### 6. Synthesis Agent

Purpose:

- compare multiple sources
- identify convergence, contradiction, and thematic recurrence
- update the top-level research narrative without pretending certainty

Outputs:

- one synthesis note in `compendium/synthesis/`

### 7. Archivist Agent

Purpose:

- keep filenames stable
- enforce schema consistency
- update indexes
- keep GitHub readable

Outputs:

- updated `INDEX.md`
- updated manifests and cross-links

## Research rule

Every agent must preserve the split between:

- evidence
- interpretation
- symbolic reading
- speculative dimensional theory

That split is the difference between a serious archive and clutter.

## GitHub rule

The repo front page should stay selective.

Do not dump every artifact into `README.md`.

Use the README only for:

- mission
- principal image
- current research frame
- links to the deeper files

Everything else belongs in `compendium/`.

## Growth pattern

The archive becomes compelling when it grows like this:

1. few strong artifacts
2. disciplined notes around them
3. repeated cross-links
4. visible reasoning trails
5. stable terminology

That feels more like a hidden-research terminal than a sales page.
