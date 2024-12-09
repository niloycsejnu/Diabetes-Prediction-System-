# Diabetes Prediction System Using Machine Learning
## Introduction
Diabetes is a growing global health issue caused by insufficient insulin production or improper insulin utilization. If not managed early, it can lead to severe complications such as:
- Heart Disease
- Stroke
- Kidney Damage
- Nerve Damage

This project focuses on predicting diabetic retinopathy (DR) using machine learning. Unlike traditional methods that rely on retinal images, we analyze structured health records, including numerical data.

---

## Problem Specification
- The  most  usual  and  conventional  method  for  diagnosis  and  detection  of diabetic retinopathy is by using human fundus images or retinal images.

- In  our  project,  we  focus  on  prediction  of  DR  using  health  records  of  the diabetic patients.

- By  using  machine  learning  techniques,  knowledge  is  acquired  through these records, containing numerical values, to predict whether the patient is having DR or not.

- For this prediction , Logistic Regression, SVM algorithm have been used.


### Target Customers:
- Hospitals & Clinics
- At-risk Individuals
- Health Insurance Companies
- Pharmaceutical Companies
- Research Institutions
- Public Health Organizations

---

## System Design & Analysis
![Screenshot (332)](https://github.com/user-attachments/assets/7c6bcfba-6af2-4187-824c-0dc97e80e0db)

1. **Diabetes Dataset**:
   - Preprocessing
   - Splitting into Training (80%) and Testing (20%) sets
2. **Machine Learning Models**:
   - Logistic Regression (LR)
   - Support Vector Machine (SVM)
3. **Evaluation Metrics**:
   - Model Accuracy

---

## Methodology
1. Collect and preprocess the dataset.
2. Apply machine learning algorithms.
3. Visualize the dataset to derive insights.
4. Train models using an 80:20 train-test split.
5. Evaluate model performance.

---

## Technologies Used
- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Django Web Framework
- **Model Training**: Jupyter Notebook
- **Libraries**: Numpy, Pandas, Matplotlib, Seaborn, Joblib (for saving/loading models)

---

## Dataset
The project uses the **Pima Diabetes Dataset**, which includes medical predictors (independent variables) such as:
- Number of pregnancies
- BMI
- Insulin level
- Age
- Glucose
- Blood Pressure
- Skin Thickness
- The target variable is **Outcome**, which indicates the presence or absence of diabetes.

---

## User Interface
The user interface is developed using Django. It is designed to be user-friendly, enabling seamless interaction for:
- Uploading health records
- Viewing predictions
  ![image](https://github.com/user-attachments/assets/15d6cee2-6f73-4ded-a487-3f0fca2a8743)
  ![image](https://github.com/user-attachments/assets/e2d94929-d2e3-4a84-a6c0-2a326dbf2963)
  ![image](https://github.com/user-attachments/assets/f3d949a9-ad71-45d5-a018-14bb0c7e9b4b)    ![image](https://github.com/user-attachments/assets/8f3f59ad-6b14-402b-9fd5-e02a3f221e2f)

This project integrates Python scripts to preprocess data, train models and evaluate predictions. Key machine learning models include Logistic Regression and SVM. The trained model is saved and deployed for predictions in the web application.

---

## Results
The trained machine learning models provide accurate predictions of diabetic retinopathy, assisting in early diagnosis and management of diabetes-related complications.

---

## Future Scope
- Experiment with different algorithms for better performance.
- Enhance data similarity metrics to improve representation.
- Develop a more intuitive application interface.
- Integrate secure login systems for user data management.
- Provide direct access to healthcare professionals for consultations.
- Implement advanced data visualization tools for deeper health insights.

---

## Conclusion
This project demonstrates the application of machine learning in predicting diabetic retinopathy using structured health records. By processing and analyzing patient data, the system provides valuable insights for early diagnosis and management of diabetes.

---

**Thank you for exploring the Diabetes Prediction System!**
