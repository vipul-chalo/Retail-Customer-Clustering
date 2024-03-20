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

### Example for Transactional Datasets:
A whole transaction made by a certain cardholder would look like:  
2023-03-01 08:09:00,2,1,75,0,1,2.990,327298  
2023-03-01 08:09:00,2,1,114,0,1,1.990,327298  
2023-03-01 08:09:00,2,1,253,0,1,2.190,327298  
2023-03-01 08:09:00,2,1,347,0,1,1.490,327298  






