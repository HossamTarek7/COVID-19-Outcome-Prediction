# Coronavirus Recovery Prediction Project

## Overview
This project aims to develop and compare different classifiers to predict the recovery outcome (death/recovered) of individuals admitted to the hospital with coronavirus symptoms. The dataset used for this project contains daily-level information on affected cases, deaths, and recoveries, starting from January 22, 2020. The data is preprocessed and cleaned, focusing on 14 major variables that influence recovery.

## Dataset Description
1. **Country:** Residency location of the individual.
2. **Location:** Specific part within the country.
3. **Age:** Age group classification based on WHO Age Group Standard.
4. **Gender:** Male or Female.
5. **Visited_Wuhan:** Whether the person has visited Wuhan, China.
6. **From_Wuhan:** Whether the person is from Wuhan, China.
7. **Symptoms:** Six families of symptoms coded in six fields.
8. **Time_before_symptoms_appear:** Time duration before symptoms appear.
9. **Result:** Binary outcome - death (1) or recovered (0).

## Project Structure
1. **Data Partitioning:**
    - The dataset will be divided into three partitions: training, validation, and testing.

2. **Classifier Design:**
    - K-Nearest Neighbors
    - Logistic Regression
    - Naïve Bayes (to be completed by the end of week 11)
    - Decision Trees
    - Support Vector Machines (to be completed by the end of week 14)

3. **Optimal Hyperparameters:**
    - For each classifier, an effort will be made to find the optimal hyperparameters to enhance model performance.

4. **Evaluation Metrics:**
    - Precision, Recall, F1-score, and ROC/AUC curves will be used to compare the performance of all classifiers.


3. **Results and Metrics:**
    - Results, metrics, and visualization outputs will be stored in separate folders for each classifier.
    - Precision, Recall, F1-score, and ROC/AUC curves will be documented and compared.

