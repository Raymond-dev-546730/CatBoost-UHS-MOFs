# Machine Learning for H₂/CH₄ Selectivity in MOFs (UHS Conditions)

This repository provides datasets and trained model weights associated with the study:

> **“Machine Learning-Derived Stage-Specific Design Rules for Metal-Organic Framework Selection in Seasonal Hydrogen Storage”** 

## Repository Contents

~~~
Data/
├── Processed/                 
│   ├── Datasets/              
│   │   ├── MOF_UHS_Dataset.csv        # Full dataset
│   │   └── MOF_UHS_Dataset_Clean.csv  # Cleaned dataset used for ML
│   ├── GCMC_Simulation_Logs/          # Grand Canonical Monte Carlo outputs
│   └── LAMMPS_Structures/             # Processed MOF structures for simulations
└── Unprocessed/
    └── CIF_Files/                     # Raw MOF structure files (.cif)

CatBoost/                            # Pre-trained CatBoost model weights
~~~


