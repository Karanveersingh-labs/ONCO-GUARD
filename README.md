# ONCO-GUARD

**Status: Exploratory learning project. The analyses are not experimentally validated and are not intended for clinical, therapeutic, or drug-development decisions.**

ONCO-GUARD is an independent computational biology learning project by Karanveer Singh, a first-year B.Tech. Biotechnology student at Sri Guru Granth Sahib World University (SGGSWU), Punjab.

The project explores an exploratory in silico workflow related to KRAS G12C, including structure preparation, docking, initial molecular dynamics setup, and exploratory free-energy analysis attempts.

This repository should not be interpreted as a validated drug-discovery study. The results should not be used to support clinical or therapeutic conclusions.

- Archived release: 10.5281/zenodo.22843776
- Concept DOI: 10.5281/zenodo.22711779

## Current Scope

PDB ID 4LUC was used as the structural starting point for an exploratory workflow related to KRAS G12C. Documentation of ligand identity and preparation is provided in the structure-preparation notebook.

- **Exploratory docking:** AutoDock Vina; center = [4.645, -14.532, 46.621] Å. Box size, exhaustiveness, and preparation details are documented in the notebook.
- **Molecular dynamics:** Initial system setup and trajectory analysis. In one setup-specific analysis, the selected atoms showed an average RMSD of approximately 1.85 Å over the analyzed trajectory window (atom selection, reference frame, and analysis interval are documented in the notebook). This value is not presented as a general stability conclusion.
- **Prediction-based analyses:** SwissADME and pKCSM estimates are included as computational predictions only.
- **Tools:** AutoDock Vina, GROMACS, SwissADME, and pKCSM.
- **Languages:** Python, Bash, and Jupyter.

The repository contains 46 notebooks covering 23 documented phases. Some phases contain multiple notebooks or V1/V2 iterations reflecting exploratory analyses, initial implementations, and incomplete or nonvalidated stages.

## Phases 01-23

- **Phases 01-18:** Iterative learning work involving target preparation, preliminary docking comparison, initial dynamics setup, exploratory free-energy attempts, and prediction-based ADMET screening.
- **Phases 19-23:** Interactive 3D visualizations.
    - [Phase 19 - Target](https://karanveersingh-labs.github.io/ONCO-GUARD/phase19.html)
    - [Phase 20 - Docking](https://karanveersingh-labs.github.io/ONCO-GUARD/phase20.html)
    - [Phase 21 - Dynamics trajectory](https://karanveersingh-labs.github.io/ONCO-GUARD/phase21.html) - exploratory; notebook records current status if not generated
    - [Phase 22 - Interaction](https://karanveersingh-labs.github.io/ONCO-GUARD/phase22.html)
    - [Phase 23 - Complex](https://karanveersingh-labs.github.io/ONCO-GUARD/phase23.html)

## Research Interests

I am interested in computational biology, molecular simulation, and how computational predictions are validated and in receiving feedback from researchers working in computational biology.

**License:** CC BY 4.0
