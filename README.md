# Stroke-Prediction
Visululize the relationships between various Healthy and Unhealthy habits to Heart Strokes, and there by predict the stroke probability with best model and hypertuned parameters.
## Introduction
<img src="stroke prediction.png?raw=true"/>

strokes are a leading global cause of death and disability, and early prediction can help identify individuals at risk, enabling timely interventions that could save lives and reduce long-term health complications. It empowers healthcare providers and individuals to take proactive measures to manage risk factors such as hypertension, smoking, and other lifestyle choices. This contribute to the broader field of preventive medicine, advancing our understanding of stroke risk factors and facilitating the development of personalized healthcare strategies to improve public health outcomes and have the potential to save lives, reduce healthcare costs, and enhance the overall well-being of communities.
## Dataset
This dataset "healthcare-dataset-stroke-data.csv" is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

### Attribute Information

1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not
*Note: "Unknown" in smoking_status means that the information is unavailable for this patient
