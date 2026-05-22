ANIPH Machine Learning Models

This repository contains the machine learning workflow developed in the ANIPH project for predicting rheological properties (storage modulus and loss modulus) of PHBV polymers. Models are developed separately for short-chain-length PHAs (sclPHAs) and medium-chain-length PHAs (mclPHAs).

Each subfolder corresponds to a specific property/material combination and contains:

Original dataset (*PHAs.xlsx)

Preprocessing notebook (*_data_preprocessing_LM.ipynb)

Cleaned dataset (*_LM.csv) Dataset obtained after preprocessing (cleaning, filtering, unit harmonization, removing invalid samples).

Final training and deployment on Jaqpot notebook (*_regression_LM.ipynb)

The deployed model was trained and optimized using Random Forest–based techniques tailored to the available experimental data. Log10-transformation applied to target values for improved model stability and handling of data spanning multiple orders of magnitude.
