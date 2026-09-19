# ONCO-GUARD

I am Karanveer Singh, a first-year B.Tech. Biotechnology student at Sri Guru Granth Sahib World University (SGGSWU), Punjab. I am developing this project as an independent learning exercise in computational oncology, molecular modeling, and structure-based drug design workflows.

This repository documents an independent learning and workflow-development effort for KRAS G12C-related ligand analysis with limited computational resources. This is not a complete computational oncology study and does not claim therapeutic or clinical relevance. The work is intended as a record of learning and a starting point for feedback on computational rigor, reproducibility, and validation.

Archived release: 10.5281/zenodo.22843776
Concept DOI: 10.5281/zenodo.22711779

### 1. Current Learning Focus
Learning reproducible workflows for structure preparation, exploratory docking, and in silico estimation, with attention to uncertainty and limitations.

### 2. Current Scope
The repository contains completed workflow components as well as conceptual and exploratory phases. The phase labels do not imply that every method is production-ready or scientifically validated.

- **Target:** PDB ID 4LUC; target identity and structure details are documented in the structure-preparation notebook. 4LUC is used as a KRAS G12C structure for learning purposes.
- **Docking:** Exploratory AutoDock Vina workflow. Center = [4.645, -14.532, 46.621] Å. Box dimensions, exhaustiveness, ligand-preparation settings, and scoring limitations are documented in the relevant notebook.
- **Molecular Dynamics:** Initial GROMACS workflow exploration.
- **Analysis:** Exploratory trajectory analysis, setup-specific.
- **In silico ADMET estimation:** SwissADME, pKCSM (prediction only, high uncertainty).
- **Structure:** 46 notebooks organized as iterative attempts (V1/V2) across Phases 01-23. V1/V2 indicates learning iterations.

### 3. Exploratory Observations
All values are computational and hypothesis-generating only.

- Docking estimates obtained in a defined Vina box
- Mean RMSD ~1.85 Å (setup-specific, exploratory)
- Conceptual free-energy analysis only
- Cys12 pose is illustrative, not experimentally confirmed covalent binding
- Exploratory machine-learning analysis on a public dataset, not a diagnostic model

### 4. Limitations
This project has no experimental validation and should not be used to support clinical or therapeutic conclusions. Important limitations include limited computational resources, incomplete force-field and equilibration assessment, lack of independent replicate simulations, uncertainty in docking scores and in silico ADMET estimates, and incomplete statistical characterization.

The results are best viewed as a record of independent learning and as a starting point for receiving expert feedback on computational rigor, reproducibility, and validation.

### 5. Project Organization and Visualizations

**Phases 01-18: Core and Exploratory Work (V1/V2 as iterative attempts)**
- PHASE 01: Target identification and structure preparation - V1, V2
- PHASE 02: Exploratory docking - V1, V2
- PHASE 03: Initial dynamics workflow - V1, V2
- PHASE 04: Conceptual free-energy analysis - V1, V2
- PHASE 05: In silico ADMET estimation - V1, V2
- PHASE 06: Comparative analysis of reference compounds - V1, V2
- PHASE 07: Exploratory off-target screening - V1, V2
- PHASE 08: Exploratory protein-interaction analysis - V1, V2
- PHASE 09: Exploratory machine-learning analysis - V1, V2
- PHASE 10: Conceptual FEP analysis - V1, V2
- PHASE 11: Exploratory optimization - V1, V2
- PHASE 12: Interaction analysis - V1, V2
- PHASE 13-18: Quality checks and documentation - V1, V2

**Phase 19-23: Interactive 3D Visualizations**
- Phase 19 - Target structure: https://karanveersingh-labs.github.io/ONCO-GUARD/phase19.html
- Phase 20 - Docking pose: https://karanveersingh-labs.github.io/ONCO-GUARD/phase20.html
- Phase 21 - Dynamics trajectory (if generated): https://karanveersingh-labs.github.io/ONCO-GUARD/phase21.html
- Phase 22 - Interaction visualization: https://karanveersingh-labs.github.io/ONCO-GUARD/phase22.html
- Phase 23 - Complex visualization: https://karanveersingh-labs.github.io/ONCO-GUARD/phase23.html

Portfolio: https://karanveersingh-labs.github.io/ONCO-GUARD/

### 6. What I Hope to Learn Next
Seeking mentorship on improving methodological rigor, documentation standards, and appropriate validation strategies, and how this learning connects to ongoing KRAS research.

License: CC-BY-4.0
