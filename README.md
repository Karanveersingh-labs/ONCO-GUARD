# ONCO-GUARD

ONCO-GUARD is an independent, exploratory computational-learning project focused on KRAS-targeted ligand exploration. 

I am Karanveer Singh, a first-year B.Tech Biotechnology student at SGGSWU, Punjab, India. This repository is a learning record - not a validated drug-discovery program. The results are in silico and hypothesis-generating.

I am sharing the project to request expert feedback on methodology, reproducibility, and next learning steps.

### 1. Project Summary
An exploratory in silico study to learn structure-based drug design workflow: target preparation, ligand design, molecular docking, molecular dynamics, and ADMET predictions. Developed with mobile-first tooling under limited computational resources.

Internal project codename: "Khanna Protocol." This is not a clinical or pharmaceutical protocol.

Archived: DOI 10.5281/zenodo.22843776 (v23.0) and 10.5281/zenodo.22711779 (concept). Archive, not peer-reviewed publication.

### 2. Research Question
Can a self-directed, low-resource workflow be used to learn and document the steps of computational oncology (KRAS G12C as a learning example) while maintaining scientific honesty about limitations?

### 3. Author and Learning Context
Author: Karanveer Singh
First-year B.Tech Biotechnology student, SGGSWU, Punjab, India.
Project is an independent learning effort conducted with limited hardware, primarily using Google Colab and a mobile phone (46 notebooks).

### 4. Methods and Software
- Target preparation: Biopython, PDB structure 408E
- Docking: AutoDock Vina (Box: [4.645, -14.532, 46.621] as per initial setup)
- Dynamics: GROMACS concept, basic trajectory analysis
- ADMET: SwissADME, pKCSM (predictions, not experimental data)
- Visualization: 3Dmol.js
- Code environment: Python in Google Colab / Spck Editor

### 5. Data and Structures
- Protein: PDB 408E (KRAS G12C)
- Ligand library: CUM series - computationally designed molecules (exploratory molecular design)
- Current illustrative example: CUM-002 - a hypothetical ligand, computationally designed molecule
- All poses are conceptual models unless stated otherwise.

### 6. Results - Clearly Labeled Exploratory
All values below are computational outputs and should not be interpreted as evidence of efficacy, safety, or biological activity.

- An exploratory docking estimate was obtained for CUM-002 in the defined Vina box. This is not evidence of a lead compound.
- The trajectory showed an average ligand/protein RMSD of approximately 1.85 Å under the stated simulation setup; this is not evidence of biological activity or binding affinity.
- An exploratory free-energy estimate was obtained, but the calculation is not sufficiently validated to support quantitative binding claims.
- ADMET predictions are in silico predictions with high uncertainty.
- The Cys12 structure is an illustrative pose and should not be interpreted as experimentally confirmed covalent binding. Actual covalent docking using a validated covalent-docking program was not performed; poses are manually constructed conceptual visualizations near Cys12.
- Exploratory machine-learning classification on a public cancer dataset was performed. This is not a clinical diagnostic model. Dataset details, train/test split, and evaluation metrics are documented in Phase 09 notebooks.

### 7. Limitations
- No experimental validation has been performed. Independent experimental validation is required.
- Calculations are not sufficiently validated to support quantitative claims.
- Force field, equilibration, replicate simulations, and uncertainty were not fully characterized.
- Results are hypothesis-generating only.

### 8. Reproducibility Instructions
Basic self-checks were performed; independent reproduction has not yet been completed. Notebooks include box coordinates, atom counts (5725 atoms COM), and tool versions where available. Detailed steps are in each phase notebook.

### 9. Phase / Notebook Index
The repository contains 46 notebooks organized into 23 phases, generally with V1 and V2 iterations. Some phases are complete, some exploratory, some illustrative.

- PHASE 01-04: Target ID, Docking, Molecular Dynamics, Free Energy (exploratory)
- PHASE 05-08: Research summary draft, ADMET predictions, Comparison as hypothetical ligand, DNA binding off-target screening (computational)
- PHASE 09: Exploratory machine-learning classification on a public cancer dataset
- PHASE 10-14: FEP concept, Optimization, Real docking, Mutation dG shift, Target network / PPI
- PHASE 15-18: Data compilation dashboard (illustrative), Data verification learning notes, Dual & triple resistance (exploratory analysis), Draft figures
- PHASE 19-23: Live visualizations: Phase19 3D view, Phase20 summary, Phase21 ADMET predictions, Phase22 MD, Phase23 guidance request - https://karanveersingh-labs.github.io/ONCO-GUARD/

### 10. Request for Feedback
I am seeking mentorship on: proper methodology, documentation standards, appropriate validation, and how to present exploratory work without overclaiming.

### 11. Glossary
- CUM: Computationally designed molecule series used in this learning project
- CUM-002: One example from CUM series, hypothetical ligand
- PDB 408E: Protein Data Bank entry for KRAS G12C used as learning example
- COM: Center of Mass
- ANM: Anisotropic Network Model
- FEP: Free Energy Perturbation (exploratory concept in this project)
- PPI: Protein-Protein Interaction
- TUMS HPC: Concept reference for high-performance computing, not used directly
- triple resistance: Exploratory analysis of multiple resistance mutations
- V1/V2: Version 1 and Version 2 iterations of same phase

### References and License
CC-BY-4.0. Built as honest learning effort. Seeking guidance for future research.

### 12. Live Links
- Phase19: https://karanveersingh-labs.github.io/ONCO-GUARD/phase19.html
- Phase20: https://karanveersingh-labs.github.io/ONCO-GUARD/phase20.html
- Phase21: https://karanveersingh-labs.github.io/ONCO-GUARD/phase21.html
- Phase22: https://karanveersingh-labs.github.io/ONCO-GUARD/phase22.html
- Phase23: https://karanveersingh-labs.github.io/ONCO-GUARD/phase23.html
