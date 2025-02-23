# Heart-Disease-Prediction

## Introduction
The ability to predict heart disease is crucial for early diagnosis and prevention. This project leverages machine learning techniques to analyze patient data and assess the risk of heart disease. The dataset used consists of medical indicators that help classify whether a patient has heart disease.

## Dataset Description
- **Dataset**: Medical records with key health indicators.
- **Total records**: Approximately X samples.
- **Features include**:
  - Age, Sex, Chest pain type
  - Resting blood pressure, Cholesterol levels
  - Fasting blood sugar, Resting ECG results
  - Maximum heart rate achieved, Exercise-induced angina
  - Oldpeak (ST depression induced by exercise)
  - Slope of the peak exercise ST segment
  - Number of major vessels colored by fluoroscopy
  - Thalassemia type
- **Target Variable**: Presence (1) or absence (0) of heart disease.

## Challenges
- Data imbalance in certain heart disease categories.
- Handling missing values and outliers.
- Feature selection for improving model interpretability.

## Techniques Used
1. **Data Preprocessing**:
   - Handled missing values through imputation techniques.
   - Encoded categorical variables for machine learning models.
   - Normalized numerical features for better convergence.
2. **Feature Engineering**:
   - Selected key features for improved model performance.
   - Created new features based on domain knowledge.
3. **Model Training & Evaluation**:
   - Logistic Regression
   - Decision Trees
   - Random Forest (Best Performing Model)
   - Support Vector Machine (SVM)
   - Neural Networks
   - Evaluated using Accuracy, Precision, Recall, and F1-score.

## Models and Performance
1. **Random Forest (Best Model)**
   - Accuracy: **85%**
   - Feature Importance utilized for explainability.
2. **Logistic Regression**
   - Simpler model with reasonable accuracy.
3. **Decision Tree**
   - Overfitting observed, but provides interpretability.
4. **SVM**
   - Handles complex relationships but requires more computational power.

## Comparison of Models
| Model                 | Accuracy (%) | Training Time | Interpretability |
|----------------------|-------------|--------------|-----------------|
| Random Forest       | 85          | Moderate     | High            |
| Logistic Regression | 78          | Fast         | High            |
| Decision Tree       | 80          | Fast         | High            |
| SVM                 | 82          | High         | Medium          |

## Results and Conclusion
- **Best Model**: Random Forest achieved **85% accuracy**.
- **Feature Engineering Impact**: Improved performance by **30%**.
- **Interpretability**: Decision Trees and Logistic Regression offer better insights but lower accuracy.
- **Future Improvements**:
  - Hyperparameter tuning to improve accuracy.
  - Exploring deep learning methods for better predictions.

