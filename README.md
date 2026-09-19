# ONCO-GUARD

**Status: Exploratory learning project; not experimentally validated and not intended for clinical, therapeutic, or drug-development decisions.**

ONCO-GUARD is an independent computational biology learning project by Karanveer Singh, a first-year B.Tech. Biotechnology student at Sri Guru Ganth Sahib World University (SGGSWU), Punjab.

The project explores an end-to-end, in silico workflow related to KRAS G12C, including exploratory free-energy analysis attempts, an introductory FEP workflow attempt, initial molecular-dynamics setup and trajectory analysis, and in silico ADMET predictions. This is an exploratory learning project, not a validated drug-discovery study.

- Archived release: [10.5281/zenodo.22843776](https://doi.org/10.5281/zenodo.22843776)
- Concept DOI: [10.5281/zenodo.22711779](https://doi.org/10.5281/zenodo.22711779)
- Portfolio: [https://karanveersingh-labs.github.io/ONCO-GUARD/](https://karanveersingh-labs.github.io/ONCO-GUARD/)

### What was learned
A series of exploratory workflow attempts documenting structure preparation, preliminary docking comparison, and prediction-based screening. The repository explicitly documents unsuccessful and incomplete attempts as learning records.

### Current Scope
PDB ID 4LUC was used as the structural starting point for an exploratory workflow related to KRAS G12C. The repository documents the structure's identity, construct, ligand state, and preparation decisions. This avoids implying that every analysis necessarily represents biologically relevant KRAS G12C behavior.

- **Docking:** Exploratory AutoDock Vina workflow attempt, center = [4.645, -14.532, 46.621] Å. Box size, exhaustiveness, preparation, and scoring limitations are documented in the notebook.
- **Dynamics:** Initial molecular-dynamics setup and trajectory analysis.
- **RMSD:** In one setup-specific trajectory analysis, the selected atoms showed an average RMSD of approximately 1.85 Å over the analyzed trajectory window. This value is not presented as evidence of biological stability and depends on the atom selection, reference frame, equilibration, and simulation setup. Details are documented in the linked analysis notebook.
- **Free energy:** Exploratory free-energy analysis attempts.

The repository contains 46 notebooks documenting iterative attempts (V1/V2). V1/V2 labels indicate learning iterations rather than independent validated experiments.

### Limitations
No experimental validation. Limited computational resources, incomplete equilibration assessment, lack of independent replicates, uncertainty in docking scores and in silico predictions, and incomplete statistical characterization. Results are best viewed as a record of independent learning.

### Phases 01-18: Iterative Attempts
- Phases 01-18: Core and exploratory work including target identification, preliminary docking comparison, initial molecular-dynamics setup and trajectory analysis, conceptual free-energy analysis attempts, prediction-based ADMET screening, and machine-learning exercise using a public dataset (V1, V2).

### Phases 19-23: Interactive 3D Visualizations
- [Phase 19 - Target structure](https://karanveersingh-labs.github.io/ONCO-GUARD/phase19.html)
- [Phase 20 - Docking pose](https://karanveersingh-labs.github.io/ONCO-GUARD/phase20.html)
- [Phase 21 - Dynamics trajectory](https://karanveersingh-labs.github.io/ONCO-GUARD/phase21.html) - exploratory; currently unavailable/not generated; notebook records its current status.
- [Phase 22 - Interaction visualization](https://karanveersingh-labs.github.io/ONCO-GUARD/phase22.html)
- [Phase 23 - Complex visualization](https://karanveersingh-labs.github.io/ONCO-GUARD/phase23.html)

### Reproducibility
The repository contains notebooks and documentation for the exploratory workflows.
- Main tools: AutoDock Vina, GROMACS, SwissADME, pKCSM
- Programming languages: Python, Bash, Jupyter
- Environment: Google Colab with limited resources
- Raw input and output files are included where feasible
- Software versions and box coordinates are documented in notebooks

### Research Interests
I am particularly interested in learning how computational predictions are validated, what controls are appropriate for docking and dynamics workflows, and how to document uncertainty for reproducibility. I would value feedback on rigor and how this learning connects to ongoing KRAS research and am seeking mentorship for an internship.

License: CC-BY-4.0
