# **Predicting Employee Attrition**
### Libraries Used in the Project:

1. **pandas**: For data manipulation (loading, cleaning, and handling data).
2. **numpy**: For numerical operations and efficient array handling.
3. **matplotlib & seaborn**: For visualizing data with plots like boxplots, countplots, and heatmaps.
4. **train_test_split**: To split the data into training and testing sets.
5. **LabelEncoder**: Converts categorical data (e.g., "Yes"/"No") into numerical format.
6. **StandardScaler**: Standardizes data (scales features to zero mean and unit variance).
7. **LogisticRegression**: A classification model to predict employee attrition.
8. **RandomForestClassifier**: A powerful ensemble method for classification.
9. **sklearn.metrics**: For model evaluation (accuracy, confusion matrix, classification report).
10. **shap**: For model explainability, providing insights into feature importance.

### Purpose:
- **Data Preprocessing**: `pandas`, `numpy`, and `LabelEncoder` clean and prepare the data.
- **Model Building**: `LogisticRegression` and `RandomForestClassifier` train models to predict attrition.
- **Evaluation**: `sklearn.metrics` assesses model performance.
- **Explainability**: `shap` helps understand feature contributions to predictions.
