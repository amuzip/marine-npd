# CLAUDE.md - Marine Natural Product Discovery

## Project Context
AI-driven drug discovery pipeline for bioactive compounds from marine algae.
Target species: Ulva (Sea Lettuce), Sargassum (Brown Algae), Gelidium (Red Algae).
Therapeutic focus: Sarcopenia treatment, Metabolic disease management.

## Key Targets
- AKT1, PPARG, FASN, mTOR, AMPK

## Analysis Tools
- PASS Online: Biological activity prediction
- PharmaExpert: Drug-likeness and ADMET prediction
- RDKit: Chemical structure processing

## Repository Structure
- data/ : Raw and processed compound data
- analysis/ : Analysis scripts and dashboards
- reports/ : Generated reports
- scripts/ : Utility scripts
- templates/ : Document templates
- docs/ : Methodology and workflow documentation

## Conventions
- All analysis scripts must include docstrings
- Commit messages follow conventional commits format
- Data files use JSON caching for performance (2-stage architecture)