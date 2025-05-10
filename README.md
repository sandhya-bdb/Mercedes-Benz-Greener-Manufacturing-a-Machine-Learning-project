🚗 Mercedes-Benz Test Bench Time Reduction

📌 Project Overview
This project aims to optimize the testing process of Mercedes-Benz vehicles by predicting the time each car configuration spends on the test bench. By leveraging machine learning techniques, we can reduce testing durations, leading to increased production efficiency and decreased carbon dioxide emissions, all while maintaining the company's high safety and quality standards.

🎯 Objectives
Data Cleaning: Remove features with zero variance and handle missing values.

Feature Encoding: Apply label encoding to categorical variables.

Dimensionality Reduction: Utilize Principal Component Analysis (PCA) to address the curse of dimensionality.

Model Training: Implement the XGBoost regression algorithm to predict testing times.

Model Evaluation: Assess model performance using the R² (Coefficient of Determination) metric.

🗂️ Dataset Description
The dataset comprises anonymized features representing various configurations of Mercedes-Benz vehicles. Each row corresponds to a unique car configuration, with the target variable 'y' indicating the time (in seconds) the car spent on the test bench.

train.csv: Training data containing features and the target variable.

test.csv: Test data containing features without the target variable.

🛠️ Tools & Technologies
Programming Language: Python

Libraries:

pandas, numpy: Data manipulation and numerical operations.

scikit-learn: Data preprocessing, PCA, and evaluation metrics.

xgboost: Implementation of the XGBoost regression algorithm.

matplotlib, seaborn: Data visualization.
Kaggle

🔍 Methodology
Data Preprocessing:

Identified and removed features with zero variance.

Checked for null values and ensured data consistency.

Applied label encoding to convert categorical variables into numerical format.

Dimensionality Reduction:

Implemented PCA to reduce the feature space while retaining 95% of the variance, mitigating the curse of dimensionality.

Model Training & Evaluation:

Trained the XGBoost regressor on the processed training data.

Evaluated model performance using R² score, achieving a score of 0.9341, indicating high predictive accuracy.

Prediction:

Applied the trained model to the test dataset to predict the testing times for unseen car configurations.

Insights:

The model effectively predicts testing times, enabling Mercedes-Benz to streamline their testing process.

Reducing test bench time contributes to lower emissions and increased production efficiency
