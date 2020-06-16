# Heart-Disease-Prediction
Develop a classification model for predicting whether a patient is likely to have a heart disease. 

## Introduction

<p>&nbsp;</p>

### What is a Heart Disease

The term “heart disease” refers to several types of heart conditions. The medical definition includes any disorder that affects the heart. Sometimes the term "heart disease" is used narrowly and incorrectly as a synonym for coronary artery disease. Heart disease is synonymous with cardiac disease but not with cardiovascular disease which is any disease of the heart or blood vessels.

<p>&nbsp;</p>

### Facts about Heart Diseases

* Heart diseases remain the leading cause of death in the United States, responsible for 840,768 deaths (635,260 cardiac) in 2016. From 2006 to 2016, the US death rate from CVD decreased by 18.6% and from coronary heart disease by 31.8%
* In a survey, 92% respondents recognized chest pain as a symptom of a heart attack. Only 27% were aware of all major symptoms and knew to call 9-1-1 when someone was having a heart attack
* About 47% of sudden cardiac deaths occur outside a hospital. This suggests that many people with heart disease don’t act on early warning signs

*Source: https://www.cdc.gov/heartdisease/facts.htm*

Many forms of heart disease can be prevented or treated with healthy lifestyle choices. Here we will perform an analysis to understand the health metrics that are associated with the presence and absence of heart diseases. 

<p>&nbsp;</p>

### Kaggle Heart Diseases Dataset
The dataset on which we will be carrying out the analysis pertaining to heart diseases has been obtained from Kaggle - https://www.kaggle.com/ronitf/heart-disease-uci. The dataset contains various heart health metrics corresponding for individuals with and without a heart disease. All types of heart diseases are being considered as one. 

<p>&nbsp;</p>

## Steps involved in this analysis are as below

* Defining the objective of the analysis
* Getting an initial understanding of the dataset and missing value treatment
* Performing exploratory data analysis to summarizing the data characteristics
* Carrying out statistical analyses for identifying features of importance
* Training and validating a base classification model with all features
* Evaluating the base model on unseen test data points
* Training and validating an improved classification model with only the important features
* Evaluating the improved model on unseen test data points
* Generating conclusions from the analysis

<p>&nbsp;</p>

## Objectives of the analysis

Early action is important for averting potential risks posed by heart diseases. Hence it is important to be aware about the possibility of having a disease so that corrective actions can be taken before it is too late. 

The objective of the analysis is thus to identify the health metrics associated with heart diseases and build a classification model to predict whether an individual with given health metrics is likely to have a heart disease or not. 

<p>&nbsp;</p>

## Initial understanding of the underlying data

Following is some information about the dataset obtained from the source.

1. *age*: Age of the individual in years
2. *sex*: Sex of the individual. 1 = male, 0 = female
3. *cp*: Chest pain type (4 values)
4. *trestbps*: Resting blood pressure (in mm Hg on admission to the hospital)
5. *chol*: Serum cholestoral in mg/dl
6. *fbs*: Fasting blood sugar > 120 mg/dl. 1 = male, 0 = female
7. *restecg*: Resting electrocardiographic results (values 0,1,2)
8. *thalach*: Maximum heart rate achieved
9. *exang*: Exercise induced angina. 1 = yes, 0 = no
10. *oldpeak*: ST depression induced by exercise relative to rest
11. *slope*: The slope of the peak exercise ST segment
12. *ca*: Number of major vessels (0-3) colored by flourosopy
13. *thal*: 3 = normal, 6 = fixed defect, 7 = reversable defect
14. *target*: 0 = With heart disease, 1 = Without heart disease

