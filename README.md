## Sustainable Future through Natural Disaster Prediction

## Description
Machine Learning Project, Python

## Abstract
This ML project, entitled "Sustainable Futures through Natural Disaster Prediction," embarks on a transformative quest towards promoting heightened resilience and sustainable practices globally. The primary goal of this project is to promote the preservation of sustainability. By employing predictive techniques, we strive to reduce the detrimental impact that disasters have on ecosystems, natural resources, and the environment. The objective aligns with worldwide endeavors in addressing climate change. Through our machine learning models such as K-means neighbor, Random Forest, Support Vector Machine (SVM), and Naive Bayes are used as early warning indicators, thus facilitating proactive approaches for disaster preparedness and response strategies. By thoroughly analyzing historical data on diverse types of calamities such as earthquakes, hurricanes, floods, and wildfires and by employing feature engineering, and machine learning algorithms our aim is to develop precise prediction models that offer practical insights for effective action. We will meticulously assess the performance of our prediction models in order to ensure their reliability and accuracy.

**Technical Report**<br>
Data_245_MachineLearning_Group_6

**Presentation Slides**<bR>
Data_245_MachineLearning_Group_6_Slides.pdf

**Industry Case study**<br>
DATA_245_Industry_CaseStudy_Group_6.pd

**Significant Paper Blog**<br>
Significant_paper_slides_Balivada-Lagisetty-Sha-Vichare.pdf https://medium.com/@sarahsha4991/training-and-assessing-classification-rules-with-imbalanced-data-69e9c50765f3

**CSV file**<br>
natural_disasters_dataset.csv

**Preprocessed dataset**<br>
preprocessed_data.csv

**Code Implementation**<br>
Data_245_MachineLearning_Group_6

**New unseen dataset**<br>
new_unseen_dataset.csv

**Testing saved model**<Br>
Data_245_MachineLearning_Group_6_Testing_the_saved_model.ipynb

**Saved Model Joblib drive link**<br>
https://drive.google.com/drive/u/1/folders/1ND3XnuUrvSIkmtFcO-zI6ovv2ykQyWp3

## Table of Contents

1.Data: We obtained a diverse dataset of historical natural disasters from Kaggle. Metadata provided information such as timestamps, location details, and event characteristics

2.Exploratory Data Analysis (EDA) : We have visualized and interpreted using histograms, bar graphs, and time series analyses during a collaborative EDA. Our goal is to identify distribution patterns, correlations, outliers, and intricate details related to probable disaster situations.We have performed EDA before data preprocessing.

3.Data Preprocessing :Checked for missing values and handled them by imputing the  Numerical values with Mean and Categorical values with Mode and encoded categorical variables. We have done EDA after data preprocessing to gain futhur insights about the data. 

4.Feature Selection: Based on Mutal Information and Domain knowledge we selected the Features and have been loaded into preproceesed_data.csv file.We have selected 6 features and one target variable which is Diaster Type.

All above 4 steps are implemented in DataCollection_EDA_DataPreprocessing_FeatureSelection.ipynb file.

5.Model Development: We have carefully chosen four machine learning techniques to best match the distinctive characteristics of natural disasters in order to properly predict them.Four different machine learning models are Random Forest, SVM, K-NN, and Naive Bayes.

6.Model Evaluation: We have perfomred evaluation metrics such as Accuracy,F1 Score,Recall and precision. 

Above 5th and 6th steps are implemented in ModelDevelopment_ModelEvaluation.ipynb file.

7.Balacning the data: We have balanced our data and performed the model developemnt and again to check the performnace of our models. Implemented soft and hard voting ensemble techniques.

This is implemented in BalancedData_ModelDevelopment.ipynb file

8.Hyperparameter Tuning: We have performed hyperparameter tuning using GridSearchCV and also done visualization of Performance metrics using Grouped Bar chart. Next model deployment was done using Joblib Approach and tested on new unseen data. 

This is implemented in HyperParameterTuning_ModelDeployment and new unseen data testing is in Testing_the_saved_model.ipynb


### Prerequisites
- Python (version used: 3.7)

