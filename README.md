# Unsupervised Machine Learning

This is a Python application allowing users to use unsupervised learning to analyze and bucketing crypto coins data

The application works by importing and cleaning data from csv, applying Kmeans and PCA method to clusering data, use hvplot to Visualize and Compare the Results. 
 

 
---

## Technologies

This project leverages python 3.7 +, pandas, KMeans, PCA, hvplot, StandardScaler


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

Step 1: run crypto_inevstiments.ipynb
```python
python crypto_inevstiments.ipynb
```
Step 2: import data from csv.


<img width="936" alt="image" src="https://user-images.githubusercontent.com/99616004/170875072-4fdc2d31-46e5-424a-a628-185675c4f113.png">

Step 3: Find the Best Value for k Using the Original Data by using elbow graph


<img width="713" alt="image" src="https://user-images.githubusercontent.com/99616004/170875125-ce527832-f4c1-449f-8dac-eecb8a45f717.png">



Step 4: Cluster Cryptocurrencies with K-means Using the Original Data


<img width="698" alt="image" src="https://user-images.githubusercontent.com/99616004/170875166-588ff3f1-6f8c-482c-b1a2-5a3ef8cfd168.png">

Step 5: Optimize Clusters with Principal Component Analysis

<img width="697" alt="image" src="https://user-images.githubusercontent.com/99616004/170875216-3defd311-00ba-4233-bf57-02d33841471f.png">

<img width="701" alt="image" src="https://user-images.githubusercontent.com/99616004/170875242-c87c5309-3c98-46c4-a40a-cbce346a0e1f.png">



Conclution:  

it seems Elbow curve didnt change much between orignal data and post PCA method. But clusters seem to have slightly diff shapes, maybe it depends on the columns seleted for visulization



## Contributors

Brought to you by TaoNYC.
connorchen7@gmail.com

---

## License

Columbia Fintech Coding Bootcamp
