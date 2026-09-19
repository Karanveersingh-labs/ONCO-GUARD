# ONCO-GUARD

> **Scope and limitations:** ONCO-GUARD is an independent, student-led computational biology learning project. It has not been experimentally validated and should not be interpreted as evidence of drug efficacy, binding affinity, safety, or clinical utility.

ONCO-GUARD is an independent project by Karanveer Singh, a first-year B.Tech. Biotechnology student at Sri Guru Granth Sahib World University (SGGSWU), Punjab.

The project uses KRAS G12C as a case study for learning an in silico structural-biology workflow, including protein and ligand preparation, exploratory docking, initial molecular-dynamics setup, and an incomplete exploration of free-energy methods.

The repository documents the workflow, intermediate analyses, limitations, and incomplete stages. This project does not demonstrate that a compound binds KRAS G12C, inhibits cancer, or has therapeutic potential.

- Archived version: 10.5281/zenodo.22843776
- Concept DOI: 10.5281/zenodo.22711779

## Current Scope

PDB structure 4LUC was used as the structural starting point for an exploratory workflow related to KRAS G12C. Through this project, I practiced documenting computational workflows, structural preparation, and critical interpretation of outputs.

- **Exploratory docking:** AutoDock Vina; center = [4.645, -14.532, 46.621] Å. Box size, exhaustiveness, and preparation documented in the linked notebook.
- **Molecular dynamics:** An initial system was prepared and exploratory trajectory analyses were performed. The reported metrics are setup-specific and are not sufficient to establish biological stability or binding.
- **Prediction-based analyses:** SwissADME and pKCSM estimates are included as computational predictions only (in silico ADMET property predictions).
- **Tools:** AutoDock Vina, GROMACS, SwissADME, and pKCSM.
- **Languages:** Python, Bash, and Jupyter.

## Phases 01-23

- **Phases 01-18:** Development and learning stages involving target preparation, preliminary docking comparisons, initial dynamics setup, exploratory free-energy methods, and in silico ADMET predictions.
- **Phases 19-23:** Interactive 3D visualizations.
    - [Phase 19 - Target](https://karanveersingh-labs.github.io/ONCO-GUARD/phase19.html)
    - [Phase 20 - Docking](https://karanveersingh-labs.github.io/ONCO-GUARD/phase20.html)
    - [Phase 21 - Dynamics trajectory](https://karanveersingh-labs.github.io/ONCO-GUARD/phase21.html)
    - [Phase 22 - Interaction](https://karanveersingh-labs.github.io/ONCO-GUARD/phase22.html)
    - [Phase 23 - Complex](https://karanveersingh-labs.github.io/ONCO-GUARD/phase23.html)

## What I learned

- Preparing protein and ligand structures for computational analysis
- Using AutoDock Vina and GROMACS in an exploratory workflow
- Writing Python and Bash scripts for analysis and visualization
- Interpreting computational results cautiously
- Documenting limitations and incomplete analyses

## Current limitations

- No experimental validation
- No experimentally measured binding data
- Docking results are hypothesis-generating only
- Molecular-dynamics analyses are preliminary and setup-dependent
- Free-energy calculations are incomplete
- ADMET values are computational predictions, not measurements

## Research Interests

I am interested in computational biology, molecular simulation, and the validation of computational predictions. I welcome feedback from researchers working in these areas.

**License:** CC BY 4.0
