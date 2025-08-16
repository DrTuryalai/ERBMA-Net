# ERBMA-Net: Enhanced Random Binary Multilevel Attention Network for facial depression recognition
This repository contains the implementation of Enhanced Random Binary Multilevel Attention Network (ERBMA-Net), a novel framework for facial depression recognition. ERBMA-Net addresses key limitations in existing methods by introducing random binary convolutional filters for enhanced adaptability and multilevel attention mechanisms to effectively capture both local and global patterns in facial expressions.

# Key Features
Multi-branch Architecture: Extracts global (face) and local (eyes, mouth) features for comprehensive facial analysis.
Enhanced Random Binary Convolutional Neural Network (ERBCNN): Introduces random binary filters and a refinement layer to improve feature processing over traditional LBCNN.
Multilevel Attention Mechanisms: Includes spatial attention for independent feature refinement and self-attention for modeling long-range dependencies.
High Performance: Achieves state-of-the-art results on two datasets:
AVEC2014: MAE = 6.80, RMSE = 8.18
CZ2024: MAE = 6.37, RMSE = 8.08

# Repository Overview
Contains training, testing, and feature extraction scripts.
requirements.txt: Dependencies for setting up the environment.

# Getting Started
Follow the instructions in the README to set up the environment, prepare datasets, and reproduce the results from the paper.

# Citing This Work
If you find this repository useful, please consider citing our paper:

M. T. Khan, Y. Cao, F. Shafait, and W. Jun "ERBMA-Net: Enhanced Random
Binary Multilevel Attention Network for Facial Depression Recognition.” IEEE Transactions on
Computational Social Systems, 2025. DOI: https://doi.org/10.1109/TCSS.2025.3596047
