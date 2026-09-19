# ONCO-GUARD

I am Karanveer Singh, a first-year B.Tech Biotechnology student at SGGSWU, Punjab, India. This repository documents an independent, self-directed learning project in computational oncology focused on KRAS G12C. The work is exploratory and intentionally limited to in silico methods, with no experimental validation or clinical claims. My goal is to learn structure-based drug design workflows, improve methodological rigor, and seek expert feedback on reproducibility, documentation, and next steps.

**What problem:** Learning KRAS G12C ligand exploration under low-resource constraints.
**Why it matters:** To build a reproducible, honest workflow for computational biology as a student.
**What I learned:** Docking, molecular dynamics, ADMET prediction workflow (see Methods).
**What I am asking:** Feedback on methodology and documentation.

Archived: DOI 10.5281/zenodo.22843776 (v23.0) | Concept: 10.5281/zenodo.22711779. Archive, not peer-reviewed publication.

### 1. Project Summary
Exploratory in silico study to learn structure-based drug design. Developed with mobile-first tooling (Google Colab on phone, 46 notebooks). Internal codename "Khanna Protocol" - personal note only.

### 2. Methods and Software
- Target prep: Biopython, PDB 408E (KRAS G12C)
- Docking: AutoDock Vina, Box [4.645, -14.532, 46.621]
- Dynamics: GROMACS concept, basic trajectory analysis
- ADMET: SwissADME, pKCSM (predictions only)
- Visualization: 3Dmol.js

### 3. Data and Structures
- Protein: PDB 408E
- Ligand library: CUM series (computationally designed molecules, exploratory)
- Example: CUM-002 (hypothetical ligand, illustrative only)

### 4. Results - Exploratory
Scientific honesty: All values below are computational outputs and should not be interpreted as evidence of efficacy, safety, or biological activity. Results are hypothesis-generating only.

- Docking estimate for CUM-002 obtained in defined Vina box.
- Trajectory showed avg RMSD ~1.85 Å (setup-specific).
- Free-energy estimate is exploratory, not validated for quantitative claims.
- ADMET predictions are in silico with high uncertainty.
- Cys12 pose is illustrative, not experimentally confirmed covalent binding.
- ML classification on public cancer dataset - not a diagnostic model (see Phase 09 for dataset/split/metrics).

### 5. Limitations
No experimental validation. Force field, equilibration, replicates, and uncertainty not fully characterized. Independent validation required.

### 6. Reproducibility
Box coordinates, atom counts (5725 atoms COM), tool versions in notebooks. 46 notebooks in 23 phases (V1/V2 iterations).

- PHASE 01-04: Target ID, Docking, MD, Free Energy
- PHASE 05-09: ADMET, hypothetical comparison, off-target screen, ML exploratory
- PHASE 10-18: FEP concept, optimization, network/PPI, dashboards, verification notes
- PHASE 19-23: Live 3D visualizations: https://karanveersingh-labs.github.io/ONCO-GUARD/

### 7. Request for Feedback
Seeking mentorship on methodology, documentation standards, appropriate validation, and presenting exploratory work without overclaiming.

### 8. Glossary
CUM: computationally designed molecule series | CUM-002: hypothetical example | COM: Center of Mass | FEP: Free Energy Perturbation (concept) | PPI: Protein-Protein Interaction | V1/V2: iterations

License: CC-BY-4.0 | Built as honest learning effort.

### 9. Live Links
- Phase19: https://karanveersingh-labs.github.io/ONCO-GUARD/phase19.html
- Phase20: https://karanveersingh-labs.github.io/ONCO-GUARD/phase20.html
- Phase21: https://karanveersingh-labs.github.io/ONCO-GUARD/phase21.html
- Phase22: https://karanveersingh-labs.github.io/ONCO-GUARD/phase22.html
- Phase23: https://karanveersingh-labs.github.io/ONCO-GUARD/phase23.html
