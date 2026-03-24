# Diabetes-prediction
 ML model to predict diabetes

📌 Project Overview

- This project uses Machine Learning to predict whether a person is diabetic based on medical features.
- The model analyzes patient data and classifies the result as:
  - Diabetic (1)
  - Non-Diabetic (0)

 📊 Dataset Information
 
- Features include:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
-Target:
   - 0 → Non-Diabetic
   - 1 → Diabetic

⚙️ Workflow
1. Data Loading
  - Dataset loaded using Pandas
  - Checked for missing values
2. Data Preprocessing
  - Split into Features (X) and Labels (y)
3. Train-Test Split
  - 80% training data
  - 20% testing data
4. Model Training
  - Logistic Regression model used
5. Evaluation
  - Accuracy calculated on training and testing data
6 Prediction System
  - Input patient data
  - Model predicts diabetic or not

🧠 Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- 
📈 Results
- Training Accuracy: ~75–85%
- Testing Accuracy: ~70–80%


