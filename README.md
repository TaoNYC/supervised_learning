# Supervised Machine Learning

This is a Python application allowing users to use supervised learning to analyze and predict crypto the loan status (good or bad)

The application works by importing and cleaning data from csv, Split the data into training and testing datasets by using `train_test_split`, and applying LogisticRegression and RandomOverSampler (to increase the size of minority samples) to predict loan status
 

 
---

## Technologies

This project leverages python 3.7 +, pandas, sklearn, hvplot


---

## Installation Guide

Before running the application, first make sure below libaries are installed

```python
  pip install pandas


```
Alerternatively you can simply just install requirement file included in this folder
```python
  pip install -r requirement.txt

```

---

## Usage

Step 1: credit_risk_resampling.ipynb
```python
python credit_risk_resampling.ipynb
```
Step 2: import data from csv.


<img width="868" alt="image" src="https://user-images.githubusercontent.com/99616004/173242254-f1179231-aa06-4c66-9320-42c8fee511af.png">

Step 3: Split the data using train_test_split


<img width="591" alt="image" src="https://user-images.githubusercontent.com/99616004/173242309-33cb8ea7-4ba5-43ae-913e-285d0aa25977.png">



Step 4: make prediction using LogisticRegression


<img width="435" alt="image" src="https://user-images.githubusercontent.com/99616004/173242353-7ea78ca9-2d4d-4d79-9f07-bd376025f321.png">

Step 5: Evaluate the model’s performance

<img width="726" alt="image" src="https://user-images.githubusercontent.com/99616004/173242385-d8304c9b-2cef-479d-b94d-50d45bfa8594.png">

Step 6: Predict a Logistic Regression Model with Resampled Training Data

<img width="678" alt="image" src="https://user-images.githubusercontent.com/99616004/173242420-a83b431a-f1aa-436a-b311-bcaaaad73ccd.png">



Conclution:  

it seems logistic regression model predicted '0' almost perfecly, both precison and Recall close to 100%; 
logistic regression model predicted '1' pretty well, 0.85 precison and 0.91 Recall. 

logistic regression model (fit with oversampled data) predicted '0' almost perfecly, both precison and Recall close to 100%. It improved prediction for '1' , similar precison at 0.84 (vs 0.85) but higher Recall at 0.99 (vs. 0.95)



## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp
