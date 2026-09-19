# ONCO-GUARD

> **Scope and limitations:** ONCO-GUARD is an independent exploratory computational biology project. The analyses are not experimentally validated and are not intended for clinical, therapeutic, or drug-development decisions.

ONCO-GUARD is an independent project by Karanveer Singh, a first-year B.Tech. Biotechnology student at Sri Guru Granth Sahib World University (SGGSWU), Punjab.

The project explores an in silico workflow related to KRAS G12C, including structure preparation, docking, initial molecular dynamics setup, and exploratory free-energy analysis attempts.

The repository documents the workflow, intermediate analyses, limitations, and incomplete stages.

- Archived version: 10.5281/zenodo.22843776
- Concept DOI: 10.5281/zenodo.22711779

## Current Scope

PDB structure 4LUC was used as the structural starting point for an exploratory workflow related to KRAS G12C. Through this project, I practiced reproducible workflow design, structural preparation, molecular dynamics analysis, and critical interpretation of computational outputs.

- **Exploratory docking:** AutoDock Vina; center = [4.645, -14.532, 46.621] Å. Box size, exhaustiveness, and preparation documented in notebook.
- **Molecular dynamics:** Initial system setup and exploratory trajectory analysis. In one setup-specific analysis, the selected atoms showed an average RMSD of approximately 1.85 Å over the analyzed trajectory window. This is a descriptive, setup-specific value, not evidence of biological stability. Atom selection, alignment, and analysis interval are documented in the linked notebook.
- **Prediction-based analyses:** SwissADME and pKCSM estimates are included as computational predictions only.
- **Tools:** AutoDock Vina, GROMACS, SwissADME, and pKCSM.
- **Languages:** Python, Bash, and Jupyter.

The repository contains 46 notebooks covering 23 exploratory workflow stages. Some stages contain multiple notebooks or V1/V2 iterations reflecting exploratory analyses, initial implementations, and incomplete or nonvalidated stages.

## Phases 01-23

- **Phases 01-18:** Iterative learning work involving target preparation, preliminary docking comparison, initial dynamics setup, exploratory free-energy attempts, and prediction-based ADMET screening.
- **Phases 19-23:** Interactive 3D visualizations.
    - [Phase 19 - Target](https://karanveersingh-labs.github.io/ONCO-GUARD/phase19.html)
    - [Phase 20 - Docking](https://karanveersingh-labs.github.io/ONCO-GUARD/phase20.html)
    - [Phase 21 - Dynamics trajectory](https://karanveersingh-labs.github.io/ONCO-GUARD/phase21.html)
    - [Phase 22 - Interaction](https://karanveersingh-labs.github.io/ONCO-GUARD/phase22.html)
    - [Phase 23 - Complex](https://karanveersingh-labs.github.io/ONCO-GUARD/phase23.html)

## Research Interests

I am interested in computational biology, molecular simulation, and the validation of computational predictions. I welcome feedback from researchers working in these areas.

**License:** CC BY 4.0
