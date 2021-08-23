<h1 align="center"> Stroke Prediction and Analysis with Machine Learning </h1>

![brain](https://user-images.githubusercontent.com/41158838/130395889-5cf2dc2c-060e-4f0c-a11d-4e2e7f1e6936.jpg)

According to the **World Health Organization (WHO)** stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.This dataset is used to predict whether a patient is likely to get a stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relevant information about the patient.

This project describes step-by-step procedures for building a **Machine Learning (ML) Model for Stroke Prediction** and for analysing which features are most useful for the prediction.

</br>

This project describes step-by-step procedure for building a machine learning (ML) model for stroke prediction and for analysing which features are most useful for the prediction.

## Dependencies
- Python (v3.7)
- Pandas (v1.0.3)
- Numpy (v1.18.1)
- Matplotlib (v3.2.1)
- Scikit-Learn (v0.22.1)
- Imbalanced-Learn (v0.6.2)
- LightGBM (v2.3.1)
- XGBoost (v1.0.2)

### About Dataset

The dataset contains 5110 real world observations and 10 different attributes:
- `gender` : "Male", "Female" or "Other"
- `age` : age of the patient
- `hypertension`: 
    - 0: if the patient doesn't have hypertension 
    - 1: if the patient has hypertension
- `heart_disease`: 
    - 0: if the patient doesn't have any heart diseases 
    - 1: if the patient has a heart disease
- `ever_married` : "No" or "Yes"
- `Residence_type` : "Rural" or "Urban"
- `avg_glucose_level` : average glucose level in blood
- `bmi` : body mass index
- `smoking_status` : "formerly smoked", "never smoked", "smokes" or "Unknown"
- `stroke` : 1 if the patient had a stroke or 0 if not

## Dataset
Dataset can be downloaded from the [Kaggle stroke dataset](https://www.kaggle.com/asaumya/healthcare-problem-prediction-stroke-patients)



