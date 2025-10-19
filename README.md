# Machine Learning for Hydrogen Storage in Metal-Organic Frameworks

This repository contains datasets, molecular simulation outputs, MOF structures, and a trained machine learning model from:

> **"Machine Learning-Derived Stage-Specific Design Rules for Metal-Organic Framework Selection in Seasonal Hydrogen Storage"**  

## Overview

We apply machine learning (ML) to predict H₂ and CH₄ adsorption, as well as H₂/CH₄ selectivity in metal-organic frameworks (MOFs) under underground hydrogen storage (UHS) conditions to derive stage-specific design rules. This repository provides the dataset and the best-performing model (CatBoost) to accelerate the discovery and optimization of MOFs for clean energy storage applications.

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

Models/
└── CatBoost/                          # Pre-trained CatBoost model weights
~~~
