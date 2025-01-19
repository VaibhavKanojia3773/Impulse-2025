# Impulse-2025
# EEG Seizure Classification and Synthetic Data Generation

## Overview

This project is designed to tackle the challenge of classifying EEG seizure types using advanced signal processing and machine learning techniques. By combining cutting-edge methods such as **Generative Adversarial Networks (WGAN-GP)** for synthetic EEG signal generation, and state-of-the-art **explainability techniques**, this work not only achieves high classification accuracy but also fosters clinical trust and transparency in the healthcare domain.

### Key Contributions:
- **Synthetic Data Generation**: Leveraging WGAN-GP to generate realistic synthetic EEG data, augmenting training datasets and improving model performance.
- **Advanced Feature Extraction**: Both time-domain and frequency-domain features (Fourier Transform and Wavelet Decomposition) were used to enhance classification power and improve model robustness.
- **Explainability**: Implemented advanced Explainable AI techniques (e.g., SHAP and saliency maps) to make predictions interpretable and actionable, fostering trust in clinical environments.
- **Denoising**: Utilized signal denoising techniques to handle noisy data and increase the accuracy of the classifier.
- **Comprehensive Evaluation**: Emphasized thorough validation of the models using various metrics, including classification reports, ROC AUC, and balanced accuracy.

## Approach

1. **Data Preprocessing & Feature Extraction**:
   - Time-domain features (Mean, Zero Crossing Rate, Energy, RMS, etc.) were computed to understand the signal’s underlying characteristics.
   - Frequency-domain features (Fourier Transform & Wavelet Decomposition) were extracted for deeper insights into brain activity and signal patterns.

2. **Model Building**:
   - **Baseline Model**: Built a robust SVM classifier using Fourier and Zero Crossing Rate features as a baseline model.
   - **Best Model**: Advanced techniques were applied, including hyperparameter tuning, deep learning models, and ensemble methods to outperform the baseline model.

3. **Synthetic Data Augmentation**:
   - Used **WGAN-GP** (Wasserstein Generative Adversarial Network with Gradient Penalty) to generate synthetic EEG signals, mimicking real EEG data for all classes.
   - The synthetic data was used to augment training datasets and improve model robustness.

4. **Explainability and Interpretability**:
   - Deployed **SHAP** and saliency maps to analyze and explain the model's decisions, focusing on the most important EEG channels for each class prediction.

5. **Denoising**:
   - Applied denoising techniques to clean noisy EEG data, improving model accuracy and ensuring high signal quality.

## Results
![14](https://github.com/user-attachments/assets/1228ec1b-24d9-40f6-87c9-048c7c003d92)
![15](https://github.com/user-attachments/assets/4757e278-16f6-415a-8c11-e4b558535347)
![16](https://github.com/user-attachments/assets/e0a1332b-a160-40d6-b59f-ee26e92a3371)

- Achieved **exceptionally high classification accuracy**, leveraging a combination of advanced generative models and feature extraction techniques.
- **Synthetic Data**: Demonstrated that synthetic EEG signals could be effectively integrated into the training process, significantly improving model performance.
- **Model Interpretability**: Our explainable AI approach ensured clinical transparency, enabling healthcare professionals to understand the model’s decision-making process.


