📌 Project Overview-
  This project aims to predict the likelihood of heart disease in patients based on clinical parameters. Using machine learning models like Logistic Regression and Random Forest, we analyze medical data to identify high-risk individuals and support early diagnosis.

📊 Dataset

Source: The dataset contains 14 medical attributes, including age, cholesterol levels, blood pressure, and chest pain type.

Key Features:

age =	Patient's age

sex =	Gender (0 = Female, 1 = Male)

cp =	Chest pain type (0 = Typical angina, 1 = Atypical angina, 2 = Non-anginal pain, 3 = Asymptomatic)

trestbps =	Resting blood pressure (in mm Hg)

chol =	Serum cholesterol level (mg/dl)

fbs =	Fasting blood sugar (> 120 mg/dl → 1, else 0)

restecg = Resting electrocardiographic results (0 = Normal, 1 = ST-T wave abnormality, 2 = Left ventricular hypertrophy)

thalach = Maximum heart rate achieved

exang =	Exercise-induced angina (1 = Yes, 0 = No)

oldpeak = ST depression induced by exercise relative to rest

slope =	Slope of the peak exercise ST segment (0 = Upsloping, 1 = Flat, 2 = Downsloping)

ca =	Number of major vessels (0–3) colored by fluoroscopy

thal = 	0 = Normal, 1 = Fixed defect, 2 = Reversible defect

target = Presence of heart disease (0 = No, 1 = Yes)

🛠️ Data Preprocessing

Handled missing values and duplicate entries

Removed outliers using box plot analysis

Standardized numerical features for better model performance

🔍 Exploratory Data Analysis (EDA)

Visualized the distribution of heart disease cases by age group and gender

Analyzed the impact of chest pain type, cholesterol levels, and blood pressure on heart disease

Used Seaborn & Matplotlib for visual insights

🚀 Machine Learning Models
Logistic Regression

Accuracy: 77.0%

Precision & Recall: Balanced for both classes

Random Forest Classifier

Accuracy: 83.6%

Performed better in handling complex relationships in data

📈 Performance Evaluation

Compared accuracy, precision, recall, and F1-score

Random Forest outperformed Logistic Regression, making it the preferred model

📌 Visualizations

✅ Age distribution of heart disease patients

✅ Gender-wise risk factors

✅ Impact of chest pain type on heart disease

✅ Model performance comparison

💡 Key Takeaways

✔ Early detection of heart disease is possible using ML models

✔ Random Forest provided better predictions with higher accuracy

✔ Feature engineering and data cleaning significantly impact model performance
