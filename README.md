<h1 align="center"> ❤️ CARDIOVASCULAR RISK PREDICTION ❤️ </h1>

<p align="center"> 
<img src="images/heart 463104065 682x408.jpg" height="400px">
</p>

<h2> 📜 Introduction </h2>

The human cardiovascular system is made up of the heart and blood vessels. Cardiovascular disease (CVD) is a set of disorders related to the heart and blood vessels. Annually large number of people die from CVD. Globally it is the number one cause of death. 

The most common cardiovascular disease is coronary artery disease, which can lead to heart attacks, chest pain or stroke. Diagnosing the heart condition of the patient is a challenging task. Heart diseases are diagnosed from the signs, symptoms and physical examination of the patient. There are several factors that increase the risk of heart disease, such as smoking habit, body cholesterol level, obesity, high blood pressure, and lack of physical exercise. 

A major challenge faced by health care organizations, such as hospitals and medical centres, is the provision of quality services at affordable costs. Our project aims to predict the presence of cardiovascular disease in a person using important features.

The proposed system can determine an exact hidden knowledge, i.e., patterns and relationships associated with heart disease from a heart disease dataset. It can also answer the complex queries for diagnosing heart disease; therefore, it can be helpful to health care practitioners to make intelligent clinical decisions.

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

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

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> 🛠️ Tools and Technologies Used </h2> 

The whole project is done using python, in Google Collaboratory. 
Following libraries were used for analyzing the data and visualizing it and to build the model to predict the Netflix clustering

* Pandas: Extensively used to load and wrangle with the dataset.
* Matplotlib: Matplotlib: Used for visualization.
* Seaborn: Seaborn: Used for visualization.
* WarningsWarnings: For filtering and ignoring the warnings.
* NumPy: NumPy: For some math operations in predictions.
* Sklearn: Sklearn: For the purpose of analysis and prediction and evaluation.

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> 🪜 Steps Involved </h2>

* Handling missing values
* Duplicate Values Treatment
* Checking for Outliers
* Exploratory Data Analysis
* Dealing with categorical variables
* Splitting data into train and test datasets
* Model Training
* Model Comparison
* Cross Validation of the best model

![--](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> 💡 Conclusion </h2>

* All attributes selected after the elimination process show P-values lower than 5% and thereby suggesting significant role in the heart disease prediction.
* Men seem to be more susceptible to heart disease than women. Increase in age, number of cigarettes smoked per day, glucose and systolic Blood Pressure also show increasing odds of having heart disease.
* Total cholesterol shows no significant change in the odds of CHD. This could be due to the presence of 'good cholesterol (HDL) in the total cholesterol reading. Glucose too causes a very negligible change in odds (0.2%)
* The model predicted with 0.86 accuracy. The model is more specific than sensitive. Overall model could be improved with more data.

<br>

<p align="center"> 
<img src="images/download (2).jpg" height="400px">
</p>
