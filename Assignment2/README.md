# Down Syndrome Prediction from Mice Protein Expression Levels
Background: Some experiments were conducted on mice to see if a treatment of Down’s syndrome works or not. Mice were divided into control and diseased (genotype), treated or untreated and whether it shows a particular behavior or not (treatment_behavior). Readings for 77 proteins were recorded for the mice, but some of the readings were discarded if they seemed unreliable (out of range). Your job is to develop a pre-processing pipeline and a classifier, and also find out which subset of proteins is important in predicting which class. 

Train data: https://www.ee.iitb.ac.in/~asethi/Dump/MouseTrain.csv

Test data:  https://www.ee.iitb.ac.in/~asethi/Dump/MouseTest.csv

- We performed exploratory data analysis and eliminated correlated variables and imputed missing variables.
- We also trained and validated hyperparameters of elastic net logistic regression, neural networks, support vector machines, and random forests for a classification problem.
- We also checked feature importance, and eliminated variables to improve model performance.

