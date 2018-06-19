# healthcare-analytics
The project aims at performing analytics on various medical databases.
# Framingham case study
We will build models using the Framingham data to predict and prevent heart disease. <br />

![alt text](https://www.the-dermatologist.com/sites/default/files/issues/Screen%2BShot%2B2014-10-24%2Bat%2B5.57.37%2BPM.png)
The Framingham Heart Study was started in 1948 under the direction of the National Heart Institute (now known as the National Heart, Lung, and Blood Institute). The initial study recruited 5,209 men and women between 30 and 62 years of age. Researchers asked participants questions about their general health, medications and asked about illnesses, including cancer.<br />
Patients were given a questionnaire and exam every 2 years and were asked to write down:<br />
• Physical characteristics<br />
• Behavioral characteristics<br />
• Test results<br />
Exams and questions expanded over time.<br />
## Dataset description
The dataset is a rather small subset of possible FHS dataset, having 4240 observations and 16 variables. <br />  The models are supposed to predict coronary heart disease(CHD) in ten years.

Attributes:
1. gender : the gender of the observations. The variable is a binary named “male” in the dataset.
2. age : Age at the time of medical examination in years.
3. education : A categorical variable of the participants education, with the levels: Some high school (1), high school/GED (2), some college/vocational school (3), college (4)

4. currentSmoker: Current cigarette smoking at the time of examinations
5. cigsPerDay: Number of cigarettes smoked each day

6. BPmeds: Use of Anti-hypertensive medication at exam
7. prevalentStroke: Prevalent Stroke (0 = free of disease)
8. prevalentHyp: Prevalent Hypertensive. Subject was defined as hypertensive if treated
9. diabetes: Diabetic according to criteria of first exam treated

10. totChol: Total cholesterol (mg/dL)
11. sysBP: Systolic Blood Pressure (mmHg)
12. diaBP: Diastolic blood pressure (mmHg)
13. BMI: Body Mass Index, weight (kg)/height (m)^2
14. heartRate: Heart rate (beats/minute)
15. glucose: Blood glucose level (mg/dL)
16. TenYearCHD : The 10 year risk of coronary heart disease(CHD).
# Good health case Study
We build a machine learning model using the Pima Indians Diabets dataset in order to predict whether a person has diabetes or not.<br />
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.<br />

## Dataset description
The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.<br />
Attributes:
1. Number of times pregnant
2. Plasma glucose concentration
3. Diastolic blood pressure (mm Hg)
4. Triceps skin fold thickness (mm)
5. 2-Hour serum insulin (mu U/ml)
6. Body mass index (weight in kg/(height in m)^2)
7. Diabetes pedigree function ( a sort of ancestor’s history)
8. Age (years)

# Hepatitis case Study
We build a machine learning model to understand survival statistics of those who contract hepatitis.

## Dataset description
Attribute Information:
1. Class: DIE, LIVE
2. AGE: 10, 20, 30, 40, 50, 60, 70, 80
3. SEX: male, female
4. STEROID: no, yes
5. ANTIVIRALS: no, yes
6. FATIGUE: no, yes
7. MALAISE: no, yes
8. ANOREXIA: no, yes
9. LIVER BIG: no, yes
10. LIVER FIRM: no, yes
11. SPLEEN PALPABLE: no, yes
12. SPIDERS: no, yes
13. ASCITES: no, yes
14. VARICES: no, yes
15. BILIRUBIN: 0.39, 0.80, 1.20, 2.00, 3.00, 4.00
16. ALK PHOSPHATE: 33, 80, 120, 160, 200, 250
17. SGOT: 13, 100, 200, 300, 400, 500,
18. ALBUMIN: 2.1, 3.0, 3.8, 4.5, 5.0, 6.0
19. PROTIME: 10, 20, 30, 40, 50, 60, 70, 80, 90
20. HISTOLOGY: no, yes 

# Algorithms 
The machine learning algorithms used in these projects are:
<br />
  1. Logistic regression for classification<br />
  2. K Nearest Neighbours algorithm<br />



