# Compendium Schema

Use this schema so every future artifact lands in a consistent shape.

## Artifact ID

Format:

`AGH-YYYYMMDD-TYPE-###`

Examples:

- `AGH-20260419-MAP-001`
- `AGH-20260419-SRC-001`
- `AGH-20260419-SYM-001`

## File classes

- `SRC` = source record
- `CLM` = claim record
- `MAP` = map analysis
- `SYM` = symbol analysis
- `SYN` = synthesis note
- `AST` = asset file

## Minimum metadata

Each note should contain:

- `artifact_id`
- `title`
- `date_added`
- `source_type`
- `origin`
- `confidence_level`
- `tags`
- `summary`
- `evidence`
- `interpretation`
- `open_questions`

## Confidence levels

- `high` = direct source, clear provenance, low ambiguity
- `medium` = partial provenance or interpretive dependence
- `low` = highly speculative or weakly sourced

## Map note additions

Map notes should also contain:

- `candidate_points`
- `selection_rationale`
- `locator_heuristic`
- `symbolic_features`
- `geological_features`

## Symbol note additions

Symbol notes should also contain:

- `motif_name`
- `visual_description`
- `source_occurrences`
- `possible_meanings`
- `related_motifs`
