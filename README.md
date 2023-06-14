# APS Failure Prediction using Random Forest

Welcome to the Scania truck maintenance prediction project! This project was developed as part of my post-graduation program. This repository contains a classification project for predicting failures in the APS (Air Pressure System) of heavy Scania trucks. The main objective of the project is to minimize costs associated with unnecessary checks performed by mechanics and maintenance failures that may result in breakdowns.

<p align="center">
  <img src="https://www.scania.com/content/www/group/en/home/products-and-services/trucks/_jcr_content/root/responsivegrid/responsivegrid_copy/responsivegrid/heroimage.coreimg.85.1920.jpeg/1585221957546.jpeg" width="70%">
</p>

## File Description

- `APS failure in Scania trucks PCA.ipynb`: This file contains the exploration and preparation of the data. It includes techniques such as exploratory data analysis, handling missing data, and the application of PCA (Principal Component Analysis) technique for dimensionality reduction.

- `APS failure in Scania trucks model implementation.ipynb`: This file contains the implementation of the Random Forest (RF) model for predicting failures in the APS system. It includes data splitting into training and testing sets, model training, performance evaluation, and generation of evaluation metrics. 

During the project, a comparison was made between two classification models: Random Forest (RF) and XGBoost (XGB). This comparison aimed to explore the knowledge and functioning of algorithms. Although the RF model was used in the project, this research was of great value as it allowed a more comprehensive analysis and provided additional information about the performance and capabilities of these two classification models.

- `Curse of Dimensionality.ipynb`: This file contains a text explaining the concept of the Curse of Dimensionality and how it can impact the accuracy of machine learning models. Techniques to mitigate this effect, such as feature selection and dimensionality reduction, are also discussed.

## Dataset

The dataset used in this project consists of data collected from heavy Scania trucks in everyday usage. It was sourced from the APS Failure and Operational Data for Scania Trucks and contains 60,000 training examples and 16,000 test examples. Each example has 171 attributes, including operational data and histogram variables. The attribute names have been anonymized for proprietary reasons. https://www.kaggle.com/datasets/uciml/aps-failure-at-scania-trucks-data-set

## Contribution

Feel free to reach out if you have any questions or suggestions regarding this project. Thank you for your interest!
