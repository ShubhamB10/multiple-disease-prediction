# multiple-disease-prediction
ABSTRACT
The use of machine learning techniques in healthcare has shown significant progress in recent 
years, especially in the development of multiple disease prediction systems. These systems 
utilize machine learning algorithms to predict the likelihood of a patient developing various 
diseases. The primary goal of these systems is to enable early diagnosis and treatment of 
diseases, resulting in better patient outcomes and reduced healthcare costs.To develop a 
multiple disease prediction system, the first step is to collect patient data from electronic health 
records, medical imaging, or other diagnostic tools. The collected data should be 
comprehensive and include all relevant information about the patient's health, including their 
medical history, lifestyle habits, family history, age, and gender. Machine learning algorithms 
such as logistic regression, decision trees, random forests, and neural networks are then applied 
to this data to develop a predictive model that accurately predicts the likelihood of a patient 
developing various diseases. Multiple disease prediction systems offer several advantages over 
traditional diagnostic methods. Firstly, they enable early detection of diseases, leading to timely 
treatment and improved patient outcomes. Secondly, they minimize the need for expensive 
diagnostic tests and procedures, thereby reducing healthcare costs. Finally, they provide 
personalized healthcare services tailored to individual needs, leading to improved patient 
satisfaction Our web application aims to provide a comprehensive prediction of multiple 
diseases, including diabetes, heart disease, and skin cancer disease. We have used Support 
Vector Machine (SVM) for diabetes prediction, logistic regression for heart disease prediction, 
and classification for skin cancer disease detection. Our application uses Streamlit for the 
frontend, where the models and tflite file are loaded for skin cancer disease detection.

WHAT's THE USE OF PROJECT
Many of the existing machine learning models for health care analysis are concentrating on 
one disease per analysis. If a user wants to predict more than one disease, he/she has to go 
through different sites. There is no common system where one analysis can perform more than 
one disease prediction. Some of the models have lower accuracy which can seriously affect 
patients’ health. When an organization wants to analyze their patient’s health reports, they have 
to deploy many models which in turn increases the cost as well as time Some of the existing 
systems consider very few parameters which can yield false results.

<img width="415" alt="image" src="https://github.com/ShubhamB10/multiple-disease-prediction/assets/83441267/f0557abd-81df-4341-be55-215c33fb22c7">

HOW TO RUN
Download the datasets of the project
Skin Cancer: https://www.kaggle.com/datasets/fanconic/skin-cancer-malignant-vs-benign
Heart Disease: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset
Diabetes: https://www.kaggle.com/datasets/mathchi/diabetes-data-set

Edit the python file with the path of models

install streamlit library and use command streamlit run filename.

Vola the project is running
