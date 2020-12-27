# Customer Segmentation - two ways
This is my final project attending the Data Analytics coding bootcamp at [Ironhack Berlin](https://www.ironhack.com/en/berlin).

*Elin Vängbo* 
*17/12/2020* 


#### -- Project Status: Completed

## Project Objective
The purpose of this project is to do a customer segmentation based on three factors: **recency**, **frequency** and **monetary value** of their purchases. The dataset was found on [Kaggle](https://www.kaggle.com/carrie1/ecommerce-data) and I especially want to thank Miljan Stojiljkovic and your [notebook](https://www.kaggle.com/miljan/customer-segmentation) where you show how to give the RFM score in an easy way using Python. 

The dataset consits of information on over 500 000 transactions spanning over one year for an ecommerce based in the UK who's customers are mostly wholesalers. Two different techniques was used to segment the customers based on the recency, frequency and monetary value of their purchases. One of them was a more simple approach, assigning a score for each factor based on the customers behaviour in relation to other customers. The other one was using the K-Means technique and letting the machine learning algorithm form clusters of the customers based on the same three factors. 

### Methods Used
* Machine Learning
* Quantiles 
* Data Visualization

### Technologies 
* Python
* Pandas, NumPy, Seaborn
* sklearn, plotly, matplotlib
* Tableau

## Dataset 
I utilised the dataset "data2.csv" located in the repo. Can also be found on [Kaggle](https://www.kaggle.com/carrie1/ecommerce-data). 

## Workflow
First the dataset was cleaned, explored and extended by adding more columns. The dataframe was then exported for further exploring using Tableau, here some trends in the data was discovered. Statistical testing was performed to see if these trends were significant. 

The clustering with a simple RFM score was then performed. Score was based on **recency**, **frequency** and **monetary value** and the customers were given the score based on their behaviour in relation to the rest of the population. Appropriate marketing techniques was then recommended based on these scores. The updated dataframe was exported for further vizualisations and dashboard-building in Tableau. 

Then the second clustering technique using K-Means was used. First the data had to be prepared for the model both using log transform and standard scaler. When the appropriate number of clusters had been found, the model was run and the clusters were formed. The number of the segment(cluster) was then added to the same dataframe as the RFM score to enable further analysis and to give marketing advise based on the traits of the clusters. 

## Needs of this project
- data exploration
- data processing
- data cleaning
- statistical modeling
- machine learning
- visualization
- writeup

## Organization
This repository contains the following files:
- Notebook:
    - customer_segmentation_final.ipynb (cleaning, wrangling, modelling)
- Dataset:
    - data2.csv (original dataset)
- Presentation: 
    - presentation.pdf (made with Google Slides)

Vizualisations can be found on [Tableau Public](https://public.tableau.com/profile/elin.v.ngbo#!/vizhome/EcommerceCustomerSegmentation/SegmentOverview)


