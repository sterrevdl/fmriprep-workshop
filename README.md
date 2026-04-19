# fmriPrep Workshop

This repository contains materials for an introductory workshop on fMRI preprocessing using **fMRIPrep**.
The goal of this workshop is to provide a practical, hands-on introduction to reproducible preprocessing of fMRI data using BIDS-formatted datasets and containerized workflows.

Authors: Fabian Dorok and Sterre van de Langenberg

---
 
## 🧠 Workshop Content
 
During this workshop, participants will learn:
 
- The BIDS data structure and BIDS conversion using Heudiconv
- How to run fMRIPrep using Docker (and WSL installation for Windows Users)
- Understanding fMRIPrep outputs
- Quality control of fMRI preprocessing
- Basics of reproducible neuroimaging workflows
 
---
 
## Software Requirements
 
To run the pipeline locally, you will need:
 
- Docker installed
- FreeSurfer license file
- A BIDS-formatted dataset
- At least 8–16 GB RAM (recommended: 32 GB+)
 
## Data
 
Example datasets (defaced) used in this workshop are stored in the `Datasets/` folder.
Unzip to your local machine before running HeuDiConv (BIDS conversion). 
Data can also be found here: https://drive.google.com/file/d/1niOEgwtN6ZeyWhGzxSUMYGn_NtEUdrTl/view?usp=drive_link

## Code

We created a Jupyter notebook for coding along at home (as a reference after the workshop). 
We also uploaded a script on how to mount network drives in WSL (`Scripts/` folder). 


