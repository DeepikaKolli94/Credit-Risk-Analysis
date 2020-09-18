# Credit-Risk-Analysis

The German Credit data set contains observations on 30 variables for 1000 past applicants for credit. Each applicant was rated as “good credit” or “bad credit”. New applicants for credit were evaluated on these 30 “predictor” variables. Developed a credit scoring rule that can be used to determine if a new applicant is a good credit risk or a bad credit risk, based on values of the predictor variables. 

Converted the variables to necessary data types and obtained the significant variables from logistic model. Later with these variables built classification models, Decision Tree (RPART & CTREE) and Random forest to predict applicants loan eligibility. Visualized the ROC, Lift curves and selected the optimal threshold cutoff values which maximized the cumulative profits.

Major concern in this project was to reduce the false positives and also to get higher true positives as the cost incurred if we falsely predict it is high when compared to true positives. So, we gave different weights to FP and FN and tried to get the optimal cut point. Using this optimal threshold value we tried to predict the class. If the probability is greater than or equal to the threshold value, we predicted the class as 1 else 0. Doing this can improve our model which helps to minimize the cost incurred. From the models built, Random forest was giving better specificity  and also better sensitivity.

Code for this project is available in Credit Risk Analysis.Rmd file.

# Technology 
R 
