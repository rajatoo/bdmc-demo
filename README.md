# BDMC Demo: GitHub + Biomolecular Visualization (Colab)

This repo contains a short, beginner-friendly demo notebook for visualizing biomolecular structure data in Python.

## Open the notebook in Google Colab (recommended)

No installs required, click to launch:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AdhithJCB/bdmc-demo/blob/main/notebooks/01_biomolecular_visualization.ipynb)

## What you’ll do in the notebook
- Download a protein structure from the Protein Data Bank (PDB)
- Parse the structure and extract Cα (CA) coordinates
- Compute distances from a selected residue and visualize them
- View the structure in 3D and highlight residues of interest

## Workshop instructions
1. Open the notebook using the badge above
2. In Colab: **Runtime → Run all**
3. When prompted, edit `pdb_id` (example IDs: `1ubq`, `1crn`, `4hhb`) and rerun the relevant cells

## Troubleshooting
- **Something errors mid-run:** Runtime → Restart session → Run all  
- **Widgets/slider not showing:** Restart session → Run all  
- **Package install issues:** rerun the `pip install` cell, then Run all  
- **Download issues:** try a different `pdb_id` (some structures are large or occasionally flaky)

## Optional: run locally
If you want to run this notebook locally later, install Python + Jupyter, then:
```bash
pip install biopython py3Dmol
```
## Attendees:
Peter the Anteater
