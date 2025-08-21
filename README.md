# Stellar Classification using Supervised Learning

This project applies supervised machine learning techniques to classify celestial objects such as stars, galaxies, and quasars based on their astronomical features.

## Features
- **Data Preprocessing**: Removed outliers, balanced classes using SMOTE, and standardized features for improved model performance.
- **Exploratory Data Analysis (EDA)**: Visualized key features to identify patterns and correlations in the dataset.
- **Model Training**: Implemented and trained multiple classifiers, including Random Forest, Linear SVM, CatBoost, and LightGBM.
- **Model Validation**: Evaluated models using cross-validation, achieving high accuracy (up to 97.7%).

## Dataset
The dataset used in this project is `stellar_classification.csv`, which contains astronomical features such as alpha, delta, redshift, and photometric filters (u, g, r, i, z).

## Libraries and Tools
- **Python**: Core programming language
- **Libraries**: 
  - Data Processing: `Pandas`, `NumPy`
  - Visualization: `Matplotlib`, `Seaborn`
  - Machine Learning: `Scikit-learn`, `LightGBM`, `CatBoost`
  - Oversampling: `SMOTE` (from `imblearn`)

## Project Workflow
1. **Data Loading**: Loaded the dataset and performed an initial overview.
2. **EDA**: Explored and visualized the data to understand its distribution and key features.
3. **Data Preprocessing**:
   - Removed outliers using the IQR method.
   - Balanced the dataset using SMOTE to handle class imbalance.
   - Standardized the features for consistent scaling.
4. **Model Training**:
   - Trained models such as Random Forest, Linear SVM, and Decision Tree on the preprocessed data.
   - Used cross-validation to validate models like CatBoost and LightGBM.
5. **Model Evaluation**:
   - Achieved up to 97.7% accuracy using LightGBM with cross-validation.

## Results
The Light Gradient Boosting Classifier (LightGBM) achieved the highest accuracy of 97.7%, demonstrating the effectiveness of the preprocessing and modeling pipeline.

## Acknowledgments
This project demonstrates the application of machine learning in astronomy, showcasing the importance of data preprocessing, visualization, and model evaluation in achieving high classification accuracy.
