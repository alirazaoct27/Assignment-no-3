# Assignment No. 4 – Machine Learning Model Application & Evaluation

**Student:** Ali Raza  
**Roll No.:** 014  
**Section:** BSCS 3A

## Project
Student Academic Risk Prediction using Machine Learning.

- **Problem type:** Binary classification
- **Dataset:** UCI Student Performance dataset (Math and Portuguese records)
- **Target:** At Risk = 1 if final grade G3 < 10, else 0
- **Models:** Logistic Regression, Decision Tree, Random Forest
- **Metrics:** Accuracy, Precision, Recall, F1-score, Confusion Matrix

## Run the notebook
Open the notebook in Google Colab and run all cells from top to bottom. It downloads the dataset from the UCI repository automatically, then trains and compares the three models.

## Methodology
G1, G2 and G3 are excluded from model features to prevent target leakage. The top model is selected by the measured F1-score after execution, not by assuming a result in advance.

## Dataset citation
Cortez, P. & Silva, A. (2008). *Using data mining to predict secondary school student performance*. UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/320/student+performance

## Limitations
This is an educational demonstration. It should not be used for consequential decisions about individual students without local validation, fairness checks, privacy controls and human oversight.
