# ONCO-GUARD

> **Scope and limitations:** This is an exploratory, self-directed computational biology learning project. It has not been experimentally validated and should not be interpreted as evidence of drug efficacy, binding affinity, safety, or clinical utility.

ONCO-GUARD is an exploratory, self-directed computational biology project developed during my early undergraduate training. Using KRAS G12C as a case study, it focuses on learning a structural-biology workflow involving protein and ligand preparation, docking, and preliminary molecular-dynamics setup. This project is intended for learning and methodological exploration rather than as a validated biological or clinical claim. The repository documents my workflow and limitations transparently.
- Archived version: [10.5281/zenodo.22843776](https://doi.org/10.5281/zenodo.22843776)
- Concept DOI: [10.5281/zenodo.22711779](https://doi.org/10.5281/zenodo.22711779)

## Current Scope

PDB structure 4LUC was used as the structural starting point for an exploratory workflow related to KRAS G12C. This project helped me develop reproducible computational workflow documentation and critical interpretation of outputs.

- **Exploratory docking:** AutoDock Vina; center = [4.645, -14.532, 46.621] Å. Details in notebook.
- **Molecular dynamics:** An initial system was prepared and exploratory analyses were performed. Metrics are setup-specific and not sufficient to establish biological stability.
- **Prediction-based analyses:** SwissADME and pKCSM estimates as in silico ADMET predictions only.
- **Tools:** AutoDock Vina, GROMACS, SwissADME, pKCSM | **Languages:** Python, Bash, Jupyter

## Learning phases 01-23

- **Learning phases 01-18:** Target preparation, preliminary docking comparisons, initial dynamics setup, exploratory free-energy methods, and in silico ADMET predictions.
- **Project phases 19-23:** Interactive 3D visualizations
    - [Phase 19 - Target](https://karanveersingh-labs.github.io/ONCO-GUARD/phase19.html) | [Phase 20 - Docking](https://karanveersingh-labs.github.io/ONCO-GUARD/phase20.html) | [Phase 21 - Dynamics](https://karanveersingh-labs.github.io/ONCO-GUARD/phase21.html) | [Phase 22 - Interaction](https://karanveersingh-labs.github.io/ONCO-GUARD/phase22.html) | [Phase 23 - Complex](https://karanveersingh-labs.github.io/ONCO-GUARD/phase23.html)

## Current limitations

- No experimental validation | No binding data | Docking is hypothesis-generating only
- MD analyses are preliminary and setup-dependent | Free-energy incomplete | ADMET is predicted

## Research Interests

I am especially interested in learning from mentors and domain experts and welcome guidance. I am seeking opportunities to learn from experienced researchers and improve my computational biology skills in a mentoring environment.

**License:** CC BY 4.0 | **Author:** Karanveer Singh, early undergraduate training, SGGSWU Punjab

**Purpose:** educational, exploratory, mentorship-oriented, method development
