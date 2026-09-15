# Structure-Based Identification of Phytochemical Inhibitors Targeting PfPGM1

### Computational identification and evaluation of potential phytochemical inhibitors of *Plasmodium falciparum* phosphoglycerate mutase (PfPGM1)

## Overview

This project presents an **in silico drug-discovery study** aimed at identifying potential phytochemical inhibitors targeting phosphoglycerate mutase 1 (PfPGM1) from *Plasmodium falciparum*.

The study combines **active-site identification, molecular docking, drug-likeness and ADME evaluation, and molecular dynamics simulation** to investigate phytochemical compounds as potential PfPGM1 inhibitors.

---

## Research Workflow

PfPGM1 (PDB: 1XQ9)
        ↓
Protein Preparation
        ↓
BLASTp-based Reference Identification
        ↓
Active-Site Prediction
(SiteMap + Structural Alignment)
        ↓
Phytochemical Library
(58 compounds)
        ↓
Molecular Docking
(AutoDock Vina)
        ↓
Top 10 Docking Hits
        ↓
SwissADME Analysis
        ↓
AD53 (Tectograndone)
        ↓
10 ns Molecular Dynamics Simulation
(GROMACS)
        ↓
Trajectory Analysis
(RMSD, RMSF, H-bonds, Rg, Energy)

