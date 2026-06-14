# ERBMA-Net: Enhanced Random Binary Multilevel Attention Network for facial depression recognition
This repository contains the implementation of Enhanced Random Binary Multilevel Attention Network (ERBMA-Net), a novel framework for facial depression recognition. ERBMA-Net addresses key limitations in existing methods by introducing random binary convolutional filters for enhanced adaptability and multilevel attention mechanisms to effectively capture both local and global patterns in facial expressions.

Steps to use the code: First run the feature extraction code that will save train, validation, and test csv files. Secondly, run train code to train the regression model on the extracted features. Third, run the test code to verify the performance on test data (test.csv file).

Preprocessing steps: OpenCV for frame extraction at seconds interval. MTCNN for facial key points detection (face, eyes, mouth) Selective cropping of face (224x224), eyes (96x192), and mouth (96x128).

<img width="1066" height="531" alt="image" src="https://github.com/user-attachments/assets/9c7e4e14-5aea-4f36-be69-9c07ffc8dc6c" />


# Key Features
Multi-branch Architecture: Extracts global (face) and local (eyes, mouth) features for comprehensive facial analysis.
Enhanced Random Binary Convolutional Neural Network (ERBCNN): Introduces random binary filters and a refinement layer to improve feature processing over traditional LBCNN.
Multilevel Attention Mechanisms: Includes spatial attention for independent feature refinement and self-attention for modeling long-range dependencies.
High Performance: Achieves state-of-the-art results on two datasets:
AVEC2014: MAE = 6.80, RMSE = 8.18
CZ2024: MAE = 6.37, RMSE = 8.08

# AVEC2014 Dataset
Audio-Visual Emotion Challenge 2014 (AVEC2014) dataset is a public dataset, which contains 300 videos of depressed patients. Each video has corresponding ground truth (BDI-II) scores and varied in duration from 6 to 248 seconds, recorded at 30 frames per second (fps).
# Repository Overview
Contains training, testing, and feature extraction scripts.
requirements.txt: Dependencies for setting up the environment.

# Getting Started
Follow the instructions in the README to set up the environment, prepare datasets, and reproduce the results from the paper.

# Citing This Work
If you find this repository useful, please consider citing our paper:

M. T. Khan, Y. Cao, F. Shafait, and W. Jun "ERBMA-Net: Enhanced Random
Binary Multilevel Attention Network for Facial Depression Recognition.” IEEE Transactions on
Computational Social Systems, 13(1), 409-427, 2026. DOI: https://doi.org/10.1109/TCSS.2025.3596047
