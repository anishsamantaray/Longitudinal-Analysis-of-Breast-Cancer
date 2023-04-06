# Breast Cancer Prognosis Analysis 

  Breast Cancer is of the <strong> most common cancer </strong> not only affecting women but also men. Diagnosis becomes very critical in such a situation  ,
  but after diagnosis also a person after curing also doesn’t lead a normal life , biopsies become a common part of his journey which is very painful. 
  <strong>In such a situation we have proposed to do Longitudinal analysis of Breast cancer patients can be done using Machine Learning and Deep Learning analysis 
  and exploratory data analysis using PowerBI </strong>.

## Requirements

1. Python 3.10
2. Jupyter Notebook
3. Pycharm IDE/ any other code editor or IDE
  
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

## Results

Performance Metrics Initially
![image](https://user-images.githubusercontent.com/84379934/230446172-c06b6962-1e6b-4339-80c0-057b16265430.png)

Performance Metrics after Balancing Class Weights

![image](https://user-images.githubusercontent.com/84379934/230446517-fbe9b593-9734-48af-9908-28e8137a2b63.png)

Performance Metrics after PCA

![image](https://user-images.githubusercontent.com/84379934/230446667-89c319d3-bec5-483d-aa83-f4901a9cb65a.png)

* All Values are in % and Yellow Colour denotes improvement in value from initial

## Website Demo

[screen-capture.webm](https://user-images.githubusercontent.com/84379934/230427516-aac769b4-c333-455a-898f-038af79d18e4.webm)

## PowerBI Report Demo



https://user-images.githubusercontent.com/84379934/230436833-c62896a4-2237-427e-853e-08a1eb508e5e.mp4

