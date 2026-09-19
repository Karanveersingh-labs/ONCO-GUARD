# ONCO-GUARD

I am Karanveer Singh, a first-year B.Tech Biotechnology student at SGGSWU, Punjab, India. This repository documents an independent, self-directed learning project in computational oncology. The project explores computational workflows under limited-compute conditions, including KRAS as a learning example. The work is exploratory and intentionally limited to in silico methods, with no experimental validation or clinical claims. My primary goals are to learn computational biology, practice reproducible analysis, and seek feedback.

**What problem:** Exploring computational ligand-binding workflows for KRAS [verified mutation: G12C] under low-resource constraints.
**Why it matters:** To practice reproducible computational biology and document uncertainty.
**Skills practiced:** Molecular docking, trajectory analysis, and in silico ADMET workflows.
**What I am asking:** Feedback on methodology and documentation.

Archived: DOI 10.5281/zenodo.22843776 (v23.0) | Concept: 10.5281/zenodo.22711779. Archive, not peer-reviewed publication.

### 1. Project Summary
Exploratory in silico study to learn structure-based drug design. Conducted under limited-compute conditions using Google Colab on a phone, 46 notebooks. Notebooks are organized into iterative phases for learning and documentation.

### 2. Methods and Software
- Target structure: PDB ID 4LUC - KRAS G12C, downloaded from the RCSB PDB. [Please verify this matches your notebooks - 4LUC is a validated G12C structure, unlike 4OBE which is G12V]
- Docking: AutoDock Vina, Box [4.645, -14.532, 46.621] (as per initial setup), exhaustiveness and poses documented in notebooks
- Molecular dynamics: workflow exploration and limited trajectory analysis; no independent production run validated
- Analysis: RMSD/RMSF calculated from the resulting trajectory (setup-specific, not validated)
- ADMET: SwissADME, pKCSM (predictions only)
- Visualization: 3Dmol.js

### 3. Data and Structures
- Protein: PDB 4LUC (KRAS G12C) - verify and update all notebooks that refer to 408E/4OBE
- Ligand library: An exploratory ligand series generated for this project; these molecules are hypothetical and experimentally untested
- Example: CUM-002 (hypothetical ligand, illustrative only)

### 4. Selected Computational Observations - Exploratory
Scientific honesty: All values below are computational outputs and should not be interpreted as evidence of efficacy, safety, or biological activity. Results are hypothesis-generating only.

- Docking estimate for CUM-002 obtained in defined Vina box (exploratory, not evidence of a lead compound)
- In one setup-specific analysis, the calculated mean RMSD was approximately 1.85 Å; this value has not been independently validated
- Free-energy: exploratory MM/GBSA concept; FEP was not performed as a production free-energy calculation, method not sufficient for quantitative binding claims
- ADMET predictions are in silico with high uncertainty
- Cys12 pose is illustrative, not experimentally confirmed covalent binding; actual covalent docking using a validated covalent-docking program was not performed
- Exploratory classification using [public cancer dataset name to be added]. This is a computational benchmarking exercise, not a diagnostic model. Dataset, train/test split, and metrics in Phase 09 - to be documented precisely.

### 5. Limitations
No experimental validation. Force field, water model, equilibration, replicates, random seeds, and uncertainty not fully characterized. Independent validation required.

### 6. Reproducibility
The prepared system contained 5,725 atoms (if correct for exact system); the reported box coordinates are in notebooks. 46 notebooks in 23 phases (V1/V2 iterations).

Recommended reading order for reviewers:
1. Target and structure validation
2. Docking workflow
3. Molecular dynamics setup and analysis
4. ADMET prediction limitations
5. Exploratory ML analysis
6. Reproducibility and limitations

- PHASE 01-04: Target ID, Docking, MD setup, Free Energy concept
- PHASE 05-09: ADMET, hypothetical comparison, off-target screen, ML exploratory
- PHASE 10-18: FEP concept, optimization, network/PPI, dashboards, verification notes
- PHASE 19-23: Live 3D visualizations: https://karanveersingh-labs.github.io/ONCO-GUARD/

Requirements: Python, Biopython, Vina. See notebooks for versions. A requirements.txt to be added.

### 7. Request for Feedback
Seeking mentorship on methodology, documentation standards, appropriate validation, and presenting exploratory work without overclaiming.

### 8. Glossary
CUM: computationally designed molecule series (learning project) | CUM-002: hypothetical example | COM: Center of Mass | FEP: Free Energy Perturbation (concept only) | PPI: Protein-Protein Interaction | V1/V2: iterations

License: CC-BY-4.0 | Built as honest learning effort.

### 9. Live Links
- Phase19: https://karanveersingh-labs.github.io/ONCO-GUARD/phase19.html
- Phase20: https://karanveersingh-labs.github.io/ONCO-GUARD/phase20.html
- Phase21: https://karanveersingh-labs.github.io/ONCO-GUARD/phase21.html
- Phase22: https://karanveersingh-labs.github.io/ONCO-GUARD/phase22.html
- Phase23: https://karanveersingh-labs.github.io/ONCO-GUARD/phase23.html
