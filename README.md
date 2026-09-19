# ONCO-GUARD

**Status: Exploratory learning project; not experimentally validated and not intended for clinical, therapeutic, or drug-development decisions.**

ONCO-GUARD is an independent computational biology learning project by Karanveer Singh, a first-year B.Tech. Biotechnology student at Sri Guru Granth Sahib World University (SGGSWU), Punjab.

The project explores an end-to-end, in silico workflow related to KRAS G12C, including exploratory free-energy analysis attempts, an introductory FEP workflow attempt, initial molecular-dynamics setup and trajectory analysis, and in silico ADMET predictions.

This is an exploratory learning project, not a validated drug-discovery study. It should not be used to support clinical or therapeutic conclusions.

- Archived release: 10.5281/zenodo.22843776
- Concept DOI: 10.5281/zenodo.22711779

### Current Scope
PDB ID 4LUC was used as the structural starting point for an exploratory workflow related to KRAS G12C. The repository documents the structure's identity, construct, ligand state, and preparation decisions.

- **Exploratory docking:** AutoDock Vina, center = [4.645, -14.532, 46.621] Å. Box size and exhaustiveness documented in notebook.
- **Dynamics:** Initial molecular-dynamics setup and trajectory analysis. In one setup-specific trajectory analysis, the selected atoms showed an average RMSD of approximately 1.85 Å over the analyzed trajectory window. This value is not presented as evidence of biological stability and depends on the atom selection, reference frame, equilibration, and simulation setup.
- **Tools:** AutoDock Vina, GROMACS, SwissADME, pKCSM. Languages: Python, Bash, Jupyter.

The repository contains 46 notebooks documenting iterative attempts (V1/V2 as learning iterations, including incomplete stages).

### Phases 01-23
- **Phases 01-18:** Iterative attempts - target prep, preliminary docking comparison, initial dynamics setup, exploratory free-energy attempts, prediction-based ADMET screening (V1/V2)
- **Phases 19-23: Interactive 3D Visualizations**
    - [Phase 19 - Target](https://karanveersingh-labs.github.io/ONCO-GUARD/phase19.html)
    - [Phase 20 - Docking](https://karanveersingh-labs.github.io/ONCO-GUARD/phase20.html)
    - [Phase 21 - Dynamics trajectory - exploratory; currently unavailable/not generated; notebook records status](https://karanveersingh-labs.github.io/ONCO-GUARD/phase21.html)
    - [Phase 22 - Interaction](https://karanveersingh-labs.github.io/ONCO-GUARD/phase22.html)
    - [Phase 23 - Complex](https://karanveersingh-labs.github.io/ONCO-GUARD/phase23.html)

### Research Interests
I am particularly interested in learning how computational predictions are validated and how to assess rigor and reproducibility. Seeking mentorship and feedback for internship.

License: CC-BY-4.0
