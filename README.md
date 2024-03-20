# 📈 Customer Clustering in a Retail Market: Data Driven Approaches

## ✏️ Introduction

Master Thesis Research Project exploring different data driven approaches to clustering customers in a retail industry.

Implemented Unsupervised Learning models in Python and visulaized results using Microsoft PowerBI. Based on datasets provided by a confidential and credible source. The datasets included customer shopping and demographic data from two distinct locations of the same grocery retailer based in Rome, Italy.

I performed extensive exploratory data analysis and implemented multiple approaches to clustering to reach conclusive answers to multiple business questions and demands of the retailer. Furthermore, I extracted some of the treated data to PowerBI to create interactive reports and visualizations for better understanding.

See the `Master Thesis.pdf` file for a detailed report of my work or `Master Thesis Presentation.pdf` for a brief summary of my work.

## 📦 Installation

In Python, the following packages are required to run the code:

- [Pandas](https://pandas.pydata.org/)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [sklearn](https://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)

You should also have some sort of Python environment manager installed, such as [Anaconda](https://www.anaconda.com/).

You should also have access to [Microsoft PowerBI](https://www.microsoft.com/en-us/power-platform/products/power-bi/) to create your own dashboards and view my results.

## ⚠ Exploratory Data Analysis:

1. Demographic Analysis
2. Transactional Analysis
3. Item Sector Analysis
4. Item Category Analysis
5. Daily & Hourly Analysis
6. Big Basket Analysis
7. Cardholder Demographic Associations

## 🎯 Included Clustering Methods:

1. Predefined Customer Segmentation through RFM
2. RFM based K-Means Clustering
3. Transactional Data focused K-Means Clustering
4. Transactional Data focused DBSCAN
5. Sectoral Shopping K-Means Clustering
6. Promotional Shopping K-Means Clustering

## 🏗️ Datasets:

A total of 6 datasets were under investigation. The data files are not provided due to confidentiality reasons. The structure of the datasets and the information provided by them can be understood from the following:

### 1️⃣ Dataset 1 - Transactional Data for Location 1:
Dataset Features (8 count): Date & Time Stamps, Cash Register Number, Number of Transaction on that cash register for the day, Item Category ID, Count bought on offer, Total Count bought, Total Amount spent, Cardholder ID

### 2️⃣ Dataset 2 - Transactional Data for Location 2:
Dataset Features (8 count): Date & Time Stamps, Cash Register Number, Number of Transaction on that cash register for the day, Item Category ID, Count bought on offer, Total Count bought, Total Amount spent, Cardholder ID

### Examples for Transactional Datasets:
If a whole transaction made by a certain cardholder includes 4 unique items, it would look like following:  
  
2023-03-01 08:09:00,2,1,75,0,1,2.990,327298  
2023-03-01 08:09:00,2,1,114,0,1,1.990,327298  
2023-03-01 08:09:00,2,1,253,0,1,2.190,327298  
2023-03-01 08:09:00,2,1,347,0,1,1.490,327298  

If a whole transaction made by a certain non-cardholder includes 8 unique items, it would look like the following:  

2023-03-01 08:52:00,3,1,20,0,2,4.180,00  
2023-03-01 08:52:00,3,1,29,0,1,2.690,00  
2023-03-01 08:52:00,3,1,31,0,2,3.000,00  
2023-03-01 08:52:00,3,1,145,0,1,1.990,00  
2023-03-01 08:52:00,3,1,265,0,1,0.150,00  
2023-03-01 08:52:00,3,1,311,2,2,1.580,00  
2023-03-01 08:52:00,3,1,351,0,2,2.580,00  
2023-03-01 08:52:00,3,1,353,1,1,1.890,00  

### 3️⃣ Dataset 3 - Cardholder Demographic Information for Location 1:
Dataset Features (4 count): ID Number, Birth Year, Sex, CAP

### 4️⃣ Dataset 4 - Cardholder Demographic Information for Location 2:
Dataset Features (4 count): ID Number, Birth Year, Sex, CAP

### Examples for Cardholder Demographic Information Datasets:
These datasets included demographic data for the cardholders that made any transactions in the transactional data. The data could look like the following:  
  
4051, NULL, NULL, NULL  
4211, 1926, M, 00152  
4718, 1973, F, NULL  
4833, NULL, M, 00100  

### 5️⃣ Dataset 5 - Item Sector Information:
Dataset Features (2 count): Sector ID Number, Sector Name

### Examples for Item Sector Dataset:
The data looked like the following:  

1,Beverages  
2,Self-Service Counter  
3,Non-Food Items  

### 6️⃣ Dataset 6 - Item Category Information:
Dataset Features (4 count): Category ID Number, Sector ID Number, Category Code, Category Name

### Examples for Item Category Dataset:
The data looked like the following:  
  
2,1,ABAA,NONALCOHOLIC BEVERAGES  
3,1,ABAC,WATER  
