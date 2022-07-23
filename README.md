<h1 align="center"> ❤️ CARDIOVASCULAR RISK PREDICTION ❤️ </h1>

<p align="center"> 
<img src="images/heart 463104065 682x408.jpg" height="400px">
</p>

<h2> 📜 Introduction </h2>

The human cardiovascular system is made up of the heart and blood vessels. Cardiovascular disease (CVD) is a set of disorders related to the heart and blood vessels. Annually large number of people die from CVD. Globally it is the number one cause of death. 

The most common cardiovascular disease is coronary artery disease, which can lead to heart attacks, chest pain or stroke. Diagnosing the heart condition of the patient is a challenging task. Heart diseases are diagnosed from the signs, symptoms and physical examination of the patient. There are several factors that increase the risk of heart disease, such as smoking habit, body cholesterol level, obesity, high blood pressure, and lack of physical exercise. 

A major challenge faced by health care organizations, such as hospitals and medical centres, is the provision of quality services at affordable costs. Our project aims to predict the presence of cardiovascular disease in a person using important features.

The proposed system can determine an exact hidden knowledge, i.e., patterns and relationships associated with heart disease from a heart disease dataset. It can also answer the complex queries for diagnosing heart disease; therefore, it can be helpful to health care practitioners to make intelligent clinical decisions.

<h2> 💾 Data Description </h2> 

<b>Demographic:</b>
* <b>Sex:</b> male or female ("M" or "F")
* <b>Age:</b> Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous) 

<b>Behavioral:</b>
* <b>is_smoking:</b> whether or not the patient is a current smoker ("YES" or "NO")
* <b>Cigs Per Day:</b> the number of cigarettes that the person smoked on average in one day. (Can be considered continuous as one can have any number of cigarettes, even half a cigarette.) 

<b>Medical(history): </b>
* <b>BP Meds:</b> whether or not the patient was on blood pressure medication (Nominal) 
* <b>Prevalent Stroke:</b> whether or not the patient had previously had a stroke (Nominal)
* <b>Prevalent Hyp:</b> whether or not the patient was hypertensive (Nominal)
* <b>Diabetes:</b> whether or not the patient had diabetes (Nominal) 

<b>Medical(current):</b> 
* <b>Tot Chol:</b> total cholesterol level (Continuous) 
* <b>Sys BP:</b> systolic blood pressure (Continuous) 
* <b>Dia BP:</b> diastolic blood pressure (Continuous) 
* <b>BMI:</b> Body Mass Index (Continuous) 
* <b>Heart Rate:</b> heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.) 
* <b>Glucose:</b> glucose level (Continuous) 

<b>Predict variable (desired target):</b>
* <b>TenYearCHD:</b> 10-year risk of coronary heart disease CHD (binary: “1”, means “Yes”, “0” means “No”) - DV
