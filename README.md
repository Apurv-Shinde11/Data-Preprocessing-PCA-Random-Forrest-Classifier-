# PCA Random Forest Classifier

## Project Overview
This project demonstrates the application of a **Random Forest Classifier** after applying **Principal Component Analysis (PCA)** to a dataset. The goal was to predict target values based on preprocessed features, while reducing dimensionality using PCA to improve model efficiency and accuracy.

## Project Structure
- `pca_random_forest_classifier.ipynb`: The Jupyter notebook containing the code for preprocessing, PCA, model training, and evaluation.
- `random_forest_model.pkl`: The trained Random Forest model.
- `scaler.pkl`: The scaler used for feature scaling.
- `pca.pkl`: The PCA object for dimensionality reduction.

## Steps
1. **Data Preprocessing**: Data cleaning, missing value handling, and feature scaling.
2. **Dimensionality Reduction**: PCA was applied to reduce noise and enhance training speed.
3. **Modeling**: A Random Forest Classifier was trained using the preprocessed data, and hyperparameter tuning was performed.
4. **Evaluation**: Model performance was evaluated using accuracy metrics and a confusion matrix.

## Key Insights
- PCA helped in reducing the feature space, improving model training time.
- The Random Forest model achieved a **high accuracy** on the test set.
  
## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ML-PCA-RandomForest-Classifier.git
   cd ML-PCA-RandomForest-Classifier
