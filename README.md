# ONCO-GUARD

I am Karanveer Singh, a first-year B.Tech. Biotechnology student at Sri Guru Granth Sahib World University (SGGSWU), Punjab. I developed ONCO-GUARD as an independent learning project to explore reproducible computational workflows related to KRAS G12C ligand analysis using limited computational resources.

This is an exploratory learning project, not a validated drug-discovery study. It should not be used to support clinical or therapeutic conclusions.

- [Archived Zenodo release](https://doi.org/10.5281/zenodo.22843776)
- [Concept DOI](https://doi.org/10.5281/zenodo.22711779)
- [Project portfolio](https://karanveersingh-labs.github.io/ONCO-GUARD/)

### 1. What I Learned
This project is a series of exploratory workflow attempts covering preliminary docking, initial GROMACS setup and trajectory analysis, conceptual free-energy analysis, prediction-based ADMET screening, and a machine-learning exercise using a public dataset.

### 2. Current Scope
PDB ID 4LUC is used as the structural starting point for an exploratory KRAS G12C-related workflow; the target identity, construct, ligand state, and preparation decisions are documented in the structure-preparation notebook.

- **Docking:** Exploratory AutoDock Vina workflow, center = [4.645, -14.532, 46.621] Å. Box size, exhaustiveness, protein/ligand preparation, and scoring limitations are documented in the relevant notebook.
- **Dynamics:** Initial GROMACS setup and trajectory analysis.
- **Analysis:** A setup-specific exploratory RMSD estimate of approximately 1.85 Å was obtained; the atom selection, reference frame, trajectory window, and reproducibility limitations are documented in the analysis notebook.
- **In silico estimation:** Prediction-based ADMET screening (SwissADME, pKCSM).

The repository contains 46 notebooks documenting iterative attempts, including unsuccessful or incomplete stages. V1/V2 labels indicate learning iterations rather than independent validated experiments.

### 3. Limitations
No experimental validation. Limited computational resources, incomplete force-field and equilibration assessment, lack of independent replicates, uncertainty in docking scores and in silico estimates, and incomplete statistical characterization.

Results are best viewed as a record of independent learning and as a starting point for expert feedback on rigor, reproducibility, and validation.

### 4. Project Organization

**Phases 01-18: Iterative attempts (V1/V2)**
- PHASE 01: Target identification and structure preparation
- PHASE 02: Preliminary docking comparison
- PHASE 03: Initial GROMACS setup and trajectory analysis
- PHASE 04: Conceptual free-energy analysis
- PHASE 05: Prediction-based ADMET screening
- PHASE 06: Comparative analysis of reference compounds
- PHASE 07: Exploratory off-target screening
- PHASE 08: Exploratory protein-interaction analysis
- PHASE 09: Machine-learning exercise using a public dataset
- PHASE 10: Conceptual FEP analysis
- PHASE 11-18: Quality checks and documentation

**Phase 19-23: Interactive 3D Visualizations**
- [Phase 19 - Target structure](https://karanveersingh-labs.github.io/ONCO-GUARD/phase19.html)
- [Phase 20 - Docking pose](https://karanveersingh-labs.github.io/ONCO-GUARD/phase20.html)
- [Phase 21 - Dynamics trajectory](https://karanveersingh-labs.github.io/ONCO-GUARD/phase21.html) - if not generated, marked as not currently available in notebook
- [Phase 22 - Interaction visualization](https://karanveersingh-labs.github.io/ONCO-GUARD/phase22.html)
- [Phase 23 - Complex visualization](https://karanveersingh-labs.github.io/ONCO-GUARD/phase23.html)

### 5. What I Hope to Learn Next
I am hoping to learn how experienced researchers assess computational validity, choose appropriate controls, and decide when a result is strong enough to justify further investigation. I would especially value feedback on the rigor and reproducibility of this workflow.

License: CC-BY-4.0
