Objective
This analysis aims to predict the 10-year risk of coronary heart disease (CHD) based on patient health data, utilizing machine learning to uncover key risk factors for early detection and prevention.

Data Preprocessing
Removed irrelevant columns and handled missing values by filling binary features (e.g., smoker status) with the mode and numeric features (e.g., cholesterol, BMI) with the median.

Exploratory Data Analysis (EDA)
Explored the relationship between features like smoking, blood pressure, cholesterol, and diabetes, identifying them as significant risk factors.

The target variable distribution shows 15.2% individuals with heart disease, 84.8% without.

Analyzed key features (age, gender, smoking, cholesterol, BMI) and their distribution.

Feature Engineering
Balanced the dataset by upsampling the minority class (heart disease patients).

Scaled the features using StandardScaler to improve model performance.

Model Building
Trained a Decision Tree Classifier to predict the 10-year risk of CHD.

Evaluated model performance with accuracy, confusion matrix, and classification report.

Model Performance
Accuracy: 91.17%

Key risk factors: age, systolic blood pressure, and cholesterol levels.

Conclusion
The predictive model demonstrates high accuracy in estimating the 10-year risk of coronary heart disease, emphasizing the need for early detection and preventive strategies.
