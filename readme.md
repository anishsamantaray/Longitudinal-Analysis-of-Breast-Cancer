# Breast Cancer Prognosis Analysis 

  Breast Cancer is of the <strong> most common cancer </strong> not only affecting women but also men. Diagnosis becomes very critical in such a situation  ,
  but after diagnosis also a person after curing also doesn’t lead a normal life , biopsies become a common part of his journey which is very painful. 
  <strong>In such a situation we have proposed to do Longitudinal analysis of Breast cancer patients can be done using Machine Learning and Deep Learning analysis 
  and exploratory data analysis using PowerBI </strong>.
  
## Libraries Required

```bash
pip install numpy as np
pip install Flask
pip install pickle5
pip install lightgbm
```
## Dataset Used

Link: https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(Prognostic)

## My Kaggle Notebook Link

Link : https://www.kaggle.com/code/anishsamantaray/wisconsin-wpbc-breast-cancer-prognosis

Won a Bronze medal for contributing the kernal in Kaggle

## Approach

1. Reading the Data
2. Data Pre-Processing --- Clearing null values, Removing columns which have correlation >0.8 with other column, Log Transforming Skewed Columns, Checking if data is balanced 
3. Applied ML models and check perfomance metrics
4. Since data is unbalanced add class_wight=balanced Hyperparameter,Check performance metrics 
5. Applied PCA and Checked Performance Metrics
6. Export the preprocessed dataset for PowerBI operations
7. Export Best model i.e. LightGBM as Pickle File
8. Created a Web app using Flask and import pickle file and design it.
9. Deploy using a Cloud Service

## Video of the Website

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://youtu.be/i-nkbo0cOv0)