

![GitHub repo size](https://img.shields.io/github/repo-size/sumit0072/Diabetes-Disease-Prediction-Project?style=plastic)
![GitHub language count](https://img.shields.io/github/languages/count/sumit0072/Diabetes-Disease-Prediction-Project?style=plastic)
![GitHub top language](https://img.shields.io/github/languages/top/sumit0072/Diabetes-Disease-Prediction-Project?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/sumit0072/Diabetes-Disease-Prediction-Project?color=red&style=plastic)


<h1>Diabetes_prediction</h1>

<h2>Table of contents</h2>

<div class="alert alert-info alert-info" style="margin-top: 20px">

1. [Objective](#1)<br>
2. [Quick Demo](#2)<br>   
3. [Dataset Prview](#3)<br>
4. [Description of variables in the dataset](#4)<br>
5. [Car Price Prediction directory tree](#5)<br>
6. [Installation](#6)<br>
7. [Technologies Used](#7)<br>
</div>
<hr>

<h3>Objective</h3><a id="1"></a>
In this project, the objective is to predict whether the person has Diabetes or not based on various features like Glucose level, Insulin, Age, BMI. We will use the Pima Indians dataset from the UCI Machine learning repository.

<h3>Quick Demo</h3><a id="2"></a>

![demo_gif](https://github.com/sumit0072/Diabetes-Disease-Prediction-Project/blob/main/demo.gif)

<p>We can predict diabetes by filling the data over UI and after that prediction will be displayed over UI.</p>

<h3>Dataset Prview</h3><a id="3"></a>
A preview of Piama Indians Dataset is as below:

| | Pregnancies | Glucose | BloodPressure | SkinThickness | Insulin |  BMI | DiabetesPedigreeFunction | Age | Outcome |
|-| ----------- | ------- | ------------- | ------------- | ------- | ---- | ------------------------ | --- | ------- |
|0|	          6	|     148 |            72 |            35 |       0 | 33.6 |                    0.627 |  50 |       1 |
|1|	          1	|      85 |            66 |            29 |       0 | 26.6 |                    0.351 |  31 |       0 |
|2|	          8	|     183 |            64 |             0 |       0 | 23.3 |                    0.672 |  32 |       1 |
|3|           1 |      89 |            66 |            23 |      94 | 28.1 |                    0.167 |  21 |       0 |
|4|	          0 |	  137 |            40 |            35 |     168 | 43.1 |                    2.288 |  33 |       1 |
|5|	          5 |	  116 |            74 |             0 |       0 | 25.6 |                    0.201 |  30 |       0 |
|6|	          3 |	   78 |            50 |            32 |      88 | 31.0 |                    0.248 |  26 |       1 |
|7|          10 |     115 |             0 |             0 |       0 | 35.3 |                    0.134 |  29 |       0 |
|8|           2 |     197 |            70 |            45 |     543 | 30.5 |                    0.158 |  53 |       1 |
|9|	          8 |     125 |            96 |             0 |       0 |  0.0 |                    0.232 |  54 |       1 |



<h3>Description of variables in the dataset</h3><a id="4"></a>

```Pregnancies:``` Number of times pregnant

```Glucose:``` Plasma glucose concentration a 2 hours in an oral glucose tolerance test

```BloodPressure:``` Diastolic blood pressure (mm Hg)

```SkinThickness:``` Triceps skin fold thickness (mm)

```Insulin:``` 2-Hour serum insulin (mu U/ml)

```BMI:``` Body mass index (weight in kg/(height in m)²)

```DiabetesPedigreeFunction:``` Diabetes pedigree function

```Age:``` Age (years)

```Outcome:``` Class variable (1: tested positive for diabetes, 0: tested negative for diabetes)

<h3>Car Price Prediction directory tree</h3><a id="5"></a>

```
├─ static
│  ├─ happy.web
│  └─ sad.webp
│
├─ Templates
│  ├─ index.html
│  └─ result.html
│
├─ app.py
│
├─ demo.gif
│
├─ diabetes_model.pkl
│  
├─ Diabetes_Notebook.ipynb
│
├─ LICENSE
│  
├─ Pima Indians diabetes.csv
│
├─ Procfile
│
├─ README.md 
│
└─ requirements.txt
    

```
    
```static``` : contains static file (css, webp) for UI
    
```templates``` : contains templates for UI

```app.py``` : Front and back end portion of the web application

```Diabetes_Notebook.ipynb``` : conatains ipynb file (Jypiter Notebook file)

```diabetes_model.pkl```  : contains model for prediction

```requirements.txt``` : required libraries 

```Pima Indians diabetes.csv```  : conatins raw data as csv file



<h3>Installation</h3><a id=""></a>

* Clone this repository and unzip it.

* create new env with python 3 and activate it .

* Install the required packages using pip install -r requirements.txt

* Execute the command: python app.py

* Open ```http://127.0.0.1:5000/``` in your browser.

<h3>Technologies Used</h3><a id=""></a>

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) 

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)