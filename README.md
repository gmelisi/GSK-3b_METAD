# Metadynamics Simulations Reveal the Protonation-Dependent Conformational Landscape of GSK-3β Dual Inhibitors

<div align="center">
  <img src="https://github.com/gmelisi/GSK-3b_METAD/blob/main/TOC.jpg" alt="TOC" width="640">
</div>


In this repository, sample input files are provided to carry out for the complex between GSK-3β and compound **4** (ARN25494):
- **PCV-metadynamics simulations** to assess the conformational preference of D3R/GSK-3β dual target-directed ligands.
- **Funnel-metadynamics simulations** to measure the free-energy cost for ligand detachment.

The ligands have been recently published in the "*European Journal of Medicinal Chemistry*" as [Di Martino *et al.*, 2025](https://www.sciencedirect.com/science/article/pii/S0223523425006646).
Complex with ligands **2**, **3** and **5** have been relased as PDB structures [9HUK](https://www.rcsb.org/structure/9HUK),[9HUL](https://www.rcsb.org/structure/9HUL) and [9HV3](https://www.rcsb.org/structure/9HV3), respectively.
Conversely, complex with ligand **4** has been retrieved via docking calculations.


## Input files

The zip file (deposited as egg in the Plumed-NEST), includes:
- Gromacs topology, equilibrated structure, index and MD parameters files.
- Plumed input specifics for the simulation.
- PDB templates read by Plumed files to recompact the system for PBC treatment, define PCVs for ligand conformational change, apply restraints, including the funnel used during unbinding.


## Authors and acknowledgements
- Gian Marco Elisi
- Vittorio Lembo
- Adriana Coricello
- Giovanni Bottegoni
