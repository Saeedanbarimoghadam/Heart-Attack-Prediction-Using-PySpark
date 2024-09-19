# Heart Attackn Prediction Using PySpark
Heart Attack Prediction Using PySpark
This project aims to predict the likelihood of a heart attack using various machine learning models implemented in PySpark. The dataset used includes 303 records with 14 features, such as age, gender, cholesterol levels, resting blood pressure, chest pain type, maximum heart rate, and other clinical measurements. The target variable represents the presence or absence of a heart attack.

Data Overview:
Features: The dataset contains various clinical attributes including age, sex, chest pain type, cholesterol, fasting blood sugar, resting ECG results, exercise-induced angina, and more.
Target: The output variable is binary, indicating the presence (1) or absence (0) of a heart attack.
No Missing Data: The dataset is complete, with no missing values.
Models Implemented:
Linear Regression: This model was tested but did not perform well in adapting to the data, likely due to the nature of the binary target variable.
Random Forest Classifier: This model showed the best results, with only a 1% difference in accuracy between training and testing data, indicating good generalization.
Logistic Regression: Also used as a classification model, though the report emphasizes the superior performance of the Random Forest model.
Data Splitting:
The dataset was split into training (75%) and testing (25%) sets. The Random Forest model demonstrated better accuracy and minimal overfitting compared to Logistic Regression.

Conclusion:
Among the models tested, the Random Forest classifier provided the best prediction results, making it the most suitable model for this dataset. Logistic Regression also provided reasonable results, though not as robust as Random Forest.
