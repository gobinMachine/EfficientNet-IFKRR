# EfficientNet-IFKRR
Leakage-free subject-wise pipeline for pMCI–sMCI for dimension reduction using Auto Encoder

This repository contains the implementation of a leakage-free,
subject-wise pipeline used for pMCI–sMCI classification.

## Key Properties
- Subject-level splitting prior to slice extraction
- One slice per subject
- Autoencoder trained only on training data
- Dimensionality reduction without representation leakage

## Data
Raw ADNI data are not shared due to data usage restrictions by ADNI.
The code expects subject-level feature CSVs.

## Reproducibility
Random seeds are fixed and subject-wise splitting is enforced
as a precautionary measure to prevent any potential data leakage.
