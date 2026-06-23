## KNN Projects
This repository contains analysis codes for Korean Neonatal Network (KNN)-based research projects, with a focus on neonatal intestinal injury, unsupervised phenotyping, and survival modelling.  
The repository is intended to organise project-specific Jupyter notebooks and Python-based analysis workflows used for data preprocessing, feature preparation, clustering, statistical analysis, model validation, and survival analysis.

# Project overview
The main project included in this repository is based on Korean Neonatal Network data for preterm and very-low-birth-weight infants. The analysis workflow includes:
- data preprocessing and variable preparation
- clinical feature cleaning and translation of variable names
- unsupervised clustering analysis
- cluster-level statistical comparison
- revision and external-experiment analysis workflows
- survival model development and validation
- supplementary analysis
The repository currently includes code-only materials.
Raw clinical data, processed datasets, model outputs, figures, and result files are intentionally excluded.

# Repository structure
KNN_Projects/  
│  
├── 0701/  
│   └── Early-stage KNN analysis notebooks  
│  
├── 0716/  
│   ├── Data preprocessing notebooks  
│   ├── Statistical analysis notebooks  
│   ├── Clustering analysis notebooks  
│   └── Analysis codes  
│  
├── Ubuntu/  
│   └── Ubuntu-server-side codes  
│  
├── README.md  
└── .gitignore
  
The 0701/ and 0716/ folders contain Windows-side Jupyter notebook workflows.  
The Ubuntu/ folder is reserved for codes processed from the Ubuntu server environment.

# Main analysis components
1. Data preprocessing  
The preprocessing notebooks include workflows for preparing KNN-derived clinical variables, handling missingness, organising analysis columns, and preparing datasets for clustering and downstream statistical analyses.

2. Unsupervised clustering  
The clustering analysis codes include workflows for identifying clinical phenotypes using unsupervised learning approaches. These notebooks are used to evaluate cluster structure, compare cluster-level clinical characteristics, and support manuscript-level interpretation.

3. Statistical analysis  
The statistical analysis notebooks include scripts for comparing demographic, perinatal, clinical, and outcome variables across clusters. These workflows are used to generate manuscript-ready statistical summaries.

4. Survival and supervised modelling  
The repository also includes codes related to survival modelling and model validation, including workflows used to evaluate clinical outcomes across identified phenotypes.

5. Revision analyses  
The PedRes_Revision/-related codes contain additional analyses performed during manuscript revision, including alternative preprocessing, imputation, clustering, and sensitivity analysis workflows.

# Data availability
Raw data and processed clinical datasets are not included in this repository.  
The following file types and directories are intentionally excluded:
- raw and processed clinical datasets
- CSV, Excel, SAV, and DTA files
- model objects and checkpoints
- generated figures
- output directories
- log files
- result summary files
- local environment or secret configuration files  

This is to prevent accidental sharing of sensitive clinical data and unnecessary large output files.

# Environment
The analysis workflows were mainly developed using Python and Jupyter Notebook.  
Typical Python libraries used across the analysis workflow may include:
- pandas
- numpy
- scipy
- scikit-learn
- matplotlib
- seaborn
- survival-analysis-related Python packages, depending on the specific notebook
  
Package versions may differ between the Windows-side and Ubuntu-server-side workflows.  For reproducibility, users should check the execution environment used for each notebook.


# Notes
This repository is primarily for internal research code management and manuscript-related analysis tracking.  The codes are not intended to provide a fully reproducible public analysis package because the original clinical datasets are not included.

# Author
J. Ahn  
Ph.D.Candidate in AI for Healthcare and Medicine, Radiological Technologist  
AI-WM Lab, Department of Biomedical Engineering, Kyung Hee University
