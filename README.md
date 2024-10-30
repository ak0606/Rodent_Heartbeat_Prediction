# rodent heartbeat Prediction
## Overview
This project explores the integration of machine learning techniques in analyzing electrocardiogram (ECG) data from rodents, focusing on automating heartbeat prediction. By leveraging various machine learning models and Python toolkits like NeuroKit2 and BioSPPy, this study aims to enhance the efficiency and accuracy of ECG analysis, addressing challenges posed by the nonlinear nature of ECG data.

## Objectives
- Implement and evaluate multiple machine learning models for heartbeat prediction from rodent ECG datasets.
- Utilize feature engineering techniques to improve model performance.
- Identify the most effective models through rigorous testing and evaluation.

## Methodology
- Trained and tested several models, including Support Vector Machines (SVM), Long Short-Term Memory (LSTM), XGBoost, and LinearSVC.
- Fine-tuned hyperparameters to optimize model performance.
- Analyzed prediction accuracy, sensitivity, and specificity across different models.

## Key Findings
- SVM implemented on windowed data outperformed other models, followed closely by BioSPPy and NeuroKit2.
- LSTM, while effective in human ECG tasks, did not yield satisfactory results for rodent data.
- A future endeavor includes developing a web-based user interface to facilitate dataset interaction.

## Significance
The study provides valuable insights into the applicability of machine learning in biomedical research, particularly for rodent ECG analysis, which has implications in pharmacology, physiology, and heart disease research. By automating heartbeat detection, this project aims to improve diagnostic accuracy and streamline the analysis process.
