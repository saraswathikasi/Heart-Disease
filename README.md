# Heart Disease Prediction
We developed a machine learning model to predict the likelihood of heart disease. Using a relevant dataset, we applied various machine learning techniques to analyze the data. This model helps us understand the key signs and symptoms of heart disease, how it manifests, and whether a person is likely to have the disease. Additionally, it can guide individuals on the next steps if the disease is detected and provide recommendations to reduce the risk of serious health outcomes or death.

# The Features in the dataset are:
1.age : Why it's important: The risk of heart disease increases significantly with age. Arteries harden and narrow, and the heart weakens.
✅ Strong predictor for models, especially in tree-based methods (e.g., Random Forest, Gradient Boosting).

2.sex : Why it's important: Men are generally at higher risk for heart disease at a younger age compared to women.
✅ Helps models understand sex-based risk variations.(Male - 1, Female - 0)

3.cp (chest pain type) : What it is: 0 = Typical angina, 1 = Atypical angina, 2 = Non-anginal pain , 3 = Asymptomatic
Why it's important: Type of chest pain strongly correlates with coronary issues. Asymptomatic cases may indicate silent but dangerous conditions.
✅ High feature importance in tree-based models.

4.trestbps ( Resting systolic blood pressure in mm Hg.): High BP stresses arteries and heart. Hypertension is a major risk factor.
✅ Useful in ensemble models especially when combined with cholesterol and age.

5.chol (Serum Cholesterol level in mg/dL.) : High cholesterol can lead to plaque buildup in arteries (atherosclerosis), which causes heart disease.
✅ Often used by boosting classifiers to catch non-linear patterns.

6.fbs (fasting blood sugar > 120 mg/dL):(1 = true, 0 = false) , High fasting blood sugar is a marker of diabetes, which significantly increases cardiovascular risk.
✅ Binary features like this help Logistic Regression and Decision Trees.

7.rstecg (resting ECG results) : 0 = Normal, 1 = ST-T wave abnormality, 2 = Left ventricular hypertrophy , Irregularities in the ECG can indicate problems in heart rhythm or past heart attacks.
✅ Very helpful in ensemble models when combined with thalach.

8.thalach (maximum heart rate achieved in bpm): Lower max heart rate during stress tests is associated with higher risk of coronary disease.
✅ Strong signal in gradient boosting and stacking.

9.exang (exercise induced angina) : 1 = Yes, 0 = No ,  exercise causes chest pain, it's a red flag for reduced blood supply to the heart.
✅ Binary features are easily split by tree-based classifiers.

10.oldpeak (ST depression induced by exercise relative to rest.):  Measures abnormalities in heart function during stress.
✅ Strong interaction with slope and thal in boosting classifiers.

11.slope (slope of the peak exercise ST segment) : 0 = Upslope, 1 = Flat, 2 = DownSloping ,Flat or downsloping ST segments often indicate ischemia or infarction.
✅ Helps ensemble models identify subtle heart strain patterns.

12.ca (number of major vessels colored by fluoroscopy) : 0 - 3 major vessels . Shows level of blood vessel blockage. More blocked vessels = higher risk.
✅ One of the most important features for heart disease prediction.

13.thal (thalassemia) : 1 = Normal, 2 = Fixed Defect, 3 = Reversible defect. Reversible defects indicate stress-related issues in heart muscle perfusion.
✅ Critical for distinguishing disease vs. no disease in Stacking and Random Forest.

14.target (1 = has heart disease, 0 = no heart disease) : This is the label we train all our models to predict.
