# Telomere technology landscape dataset (BIDS wrapper)

## Summary
This OpenNeuro dataset is a **BIDS-compatible wrapper** created to host **non-imaging, secondary-research source documents**
(e.g., curated spreadsheets, codebooks, and evidence grading tables) under `sourcedata/`.

Because OpenNeuro expects BIDS structure, the dataset includes a **minimal placeholder subject folder** (`sub-01/beh/`)
containing a tiny behavioral record. This placeholder exists only to satisfy BIDS validation rules and **does not contain
human participant measurements or identifiable information**.

## Contents
- `dataset_description.json`: Dataset-level metadata required by BIDS.
- `README.md`: This description.
- `participants.tsv`: Minimal participant listing (placeholder subject `sub-01`).
- `sub-01/beh/`: Placeholder behavioral file pair (`*_beh.tsv` and `*_beh.json`).
- `sourcedata/`: Source spreadsheets used to build the telomere technology landscape.

## Intended use
- Technology scouting / landscape analysis in telomere biology and longevity biotechnology
- Evidence grading and structured curation from publicly available sources

## Notes
If you later add real participant-level data, replace the placeholder `sub-01/` content with actual BIDS-compliant data
and update `participants.tsv` accordingly.
