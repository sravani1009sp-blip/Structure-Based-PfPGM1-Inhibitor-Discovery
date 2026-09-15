# Structure-Based Identification of Phytochemical Inhibitors Targeting PfPGM1

### Computational identification and evaluation of potential phytochemical inhibitors of *Plasmodium falciparum* phosphoglycerate mutase (PfPGM1)

## Overview

This project presents an **in silico drug-discovery study** aimed at identifying potential phytochemical inhibitors targeting phosphoglycerate mutase 1 (PfPGM1) from *Plasmodium falciparum*.

The study combines **active-site identification, molecular docking, drug-likeness and ADME evaluation, and molecular dynamics simulation** to investigate phytochemical compounds as potential PfPGM1 inhibitors.

---


   ## Research Workflow

**1. Target Protein**  
PfPGM1 (PDB: 1XQ9)

↓

**2. Protein Preparation**

↓

**3. BLASTp-based Reference Identification**

↓

**4. Active-Site Prediction**  
SiteMap + Structural Alignment

↓

**5. Phytochemical Library**  
58 compounds

↓

**6. Molecular Docking**  
AutoDock Vina

↓

**7. Top 10 Docking Hits**

↓

**8. SwissADME Analysis**

↓

**9. Lead Selection**  
AD53 (Tectograndone)

↓

**10. Molecular Dynamics Simulation**  
10 ns using GROMACS

↓

**11. Trajectory Analysis**  
RMSD • RMSF • H-bonds • Radius of Gyration • Energy    

---

## Target Protein

**Protein:** Phosphoglycerate mutase 1 (PfPGM1)  
**Organism:** *Plasmodium falciparum*  
**PDB ID:** 1XQ9  
**Structure:** X-ray crystallographic structure  
**Resolution:** 2.58 Å  
**Oligomeric state:** Homotetramer

PfPGM1 was selected as the target protein because of its role in the glycolytic pathway of *Plasmodium falciparum*. The protein structure used in this study was obtained from the RCSB Protein Data Bank.

### Reference Protein Selection

Because experimentally characterized active-site information was not available for 1XQ9, BLASTp was used to identify a suitable reference protein.

| PDB ID | Sequence Identity | Selection |
|---|---:|---|
| 3KKK | 99% | Not selected |
| 4ODI | 75% | **Selected** |

Although 3KKK showed higher sequence identity, 4ODI was selected because published active-site information was available for this structure. The active-site information from 4ODI was subsequently mapped onto 1XQ9 using structural alignment.

---

