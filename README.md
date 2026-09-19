# ONCO-GUARD

> **Scope and limitations:** ONCO-GUARD is a self-directed computational biology learning project developed by Karanveer Singh during his early undergraduate training. It has not been experimentally validated and should not be interpreted as evidence of drug efficacy, binding affinity, safety, or clinical utility.

ONCO-GUARD uses KRAS G12C as a case study to explore a structural-biology workflow, including protein and ligand preparation, docking, and preliminary molecular-dynamics setup. This repository documents the workflow, exploratory analyses, and limitations of the work; it does not claim validated binding, therapeutic activity, or experimental evidence.

- Archived version: 10.5281/zenodo.22843776
- Concept DOI: 10.5281/zenodo.22711779

## Current Scope

PDB structure 4LUC was used as the structural starting point for an exploratory workflow related to KRAS G12C. Through this project, I practiced documenting computational workflows and critical interpretation of outputs.

- **Exploratory docking:** AutoDock Vina; center = [4.645, -14.532, 46.621] Å. Box size and preparation documented in notebook.
- **Molecular dynamics:** An initial system was prepared and exploratory trajectory analyses were performed. Metrics are setup-specific and not sufficient to establish biological stability.
- **Prediction-based analyses:** SwissADME and pKCSM estimates as in silico ADMET predictions only.
- **Tools:** AutoDock Vina, GROMACS, SwissADME, pKCSM | **Languages:** Python, Bash, Jupyter

## Phases 01-23

- **Phases 01-18:** Development and learning stages involving target preparation, preliminary docking comparisons, initial dynamics setup, exploratory free-energy methods, and in silico ADMET predictions.
- **Phases 19-23:** Interactive 3D visualizations
    - [Phase 19 - Target](https://karanveersingh-labs.github.io/ONCO-GUARD/phase19.html) | [Phase 20 - Docking](https://karanveersingh-labs.github.io/ONCO-GUARD/phase20.html) | [Phase 21 - Dynamics](https://karanveersingh-labs.github.io/ONCO-GUARD/phase21.html) | [Phase 22 - Interaction](https://karanveersingh-labs.github.io/ONCO-GUARD/phase22.html) | [Phase 23 - Complex](https://karanveersingh-labs.github.io/ONCO-GUARD/phase23.html)

## Current limitations

- No experimental validation | No experimentally measured binding data
- Docking results are hypothesis-generating only
- Molecular-dynamics analyses are preliminary and setup-dependent
- Free-energy calculations are incomplete | ADMET values are computational predictions

## Research Interests

I am interested in computational biology, molecular simulation, and the validation of computational predictions. I am especially interested in learning from mentors and domain experts and welcome feedback from researchers working in these areas.

**License:** CC BY 4.0 | **Author:** Karanveer Singh, B.Tech Biotechnology, SGGSWU Punjab
