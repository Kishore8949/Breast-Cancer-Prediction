# Breast-Cancer-Prediction


**Objective**:

 This repository is a learning exercise in understanding the basic concepts of machine learning and its implementaion.

**Understanding the Problem**:

Predicting the severity of Breast Cancer.

**Dataset Description**:

Mammography is the most effective method for breast cancer screening available today. However, the low 
positive predictive value of breast biopsy resulting from mammogram interpretation leads to approximately 
70% unnecessary biopsies with benign outcomes. To reduce the high number of unnecessary breast biopsies, 
several computer-aided diagnoses (CAD) systems have been proposed in the last years. These systems help 
physicians in their decision to perform a breast biopsy on a suspicious lesion seen in a mammogram or to 
perform a short-term follow-up examination instead. 
This data set can be used to predict the severity (benign or malignant) of a mammographic mass lesion from 
BI-RADS attributes and the patient's age. It contains a BI-RADS assessment, the patient's age and three BIRADS attributes together with the ground truth (the severity field).
Attribute Information:
1. BI-RADS assessment: 1 to 5 (ordinal, non-predictive!)
2. Age: patient's age in years (integer)
3. Shape: mass shape: round=1 oval=2 lobular=3 irregular=4 (nominal)
4. Margin: mass margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal)
5. Density: mass density high=1 iso=2 low=3 fat-containing=4 (ordinal)
6. Severity: benign=0 or malignant=1 (binominal, goal field!)

The Analysis is divided into four sections

1. Pre-processing the Data.
2. Exploratory Data Analysis.
3. Feature engineering.
4. Decision Tree with Best ccp_alphas (Using it as Base model for Random Forest Classifier, Cross-Validation and Hyper parameter tuning using Grid Searcv CV).












