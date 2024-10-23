# Ola Driver Attrition Analysis using decison tree,random forest ,lightGBM

### Goal
The primary goal of this project was to understand and predict driver churn at Ola. By identifying the factors contributing to driver attrition, the project aims to enhance recruitment and retention strategies, ultimately reducing turnover rates and improving operational efficiency.

### Dataset Overview
The analysis utilized a dataset containing driver information from 2019 and 2020, including demographics, tenure, and performance metrics.

### Key Features
- **Demographics**: Age, Gender, City, Education Level
- **Tenure**: Dates of joining and last working date
- **Performance Metrics**: Quarterly ratings, monthly income, and total business value

### Exploratory Data Analysis (EDA)
The EDA phase involved:
- Analyzing the dataset structure and identifying missing values.
- Aggregating data by driver ID to ensure accuracy.
- Engineering new features related to performance changes.
- Performing statistical summaries and correlation analysis to understand relationships between features.
- Visualizing data distributions and relationships to uncover patterns.

### Data Preprocessing
Steps included:
- Using KNN for missing value imputation.
- Creating new features to indicate changes in ratings and income.
- Balancing the dataset using SMOTE to address class imbalances.
- Standardizing numerical features and applying one-hot encoding to categorical variables.

### Model Building
The project implemented several modeling techniques:
- **Decision Tree**: A baseline model for understanding feature importance and relationships.
- **Random Forest**: An ensemble method that improves predictive performance through bagging.
- **Gradient Boosting**: A boosting technique used to enhance model accuracy.
- **LightGBM**: A gradient boosting framework that is efficient and capable of handling large datasets.

### Hyperparameter Tuning
- **Grid Search**: Employed for fine-tuning the Random Forest model to achieve optimal parameters.
- **Random Search**: Utilized for exploring hyperparameters in the Gradient Boosting and LightGBM models.

### Results Evaluation
Model performance was assessed using:
- **Classification metrics**: Precision, recall, F1-score, and accuracy.
- **ROC AUC scores**: To evaluate the models' discrimination capabilities. The LightGBM model achieved the highest ROC AUC score, demonstrating its effectiveness in predicting driver attrition.

### Insights and Recommendations
The analysis identified critical factors influencing driver churn, such as income fluctuations and performance ratings, leading to actionable recommendations for enhancing driver retention strategies.

### Conclusion
This comprehensive analysis provides valuable insights for Ola to improve driver retention and reduce attrition rates, ultimately benefiting the organization.
