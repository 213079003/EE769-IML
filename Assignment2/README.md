# Down Syndrome Prediction from Mice Protein Expression Levels
- This repository consists of a classification task where we predict the genotype and treatment_behavior of mice in [Train data](https://www.ee.iitb.ac.in/~asethi/Dump/MouseTrain.csv)
- Input Features: 77 numerical  and Target Features: 2 categorical (Genotype, Treatment_Behavior)
- The Genotype column has 2 classes 'Control', 'Ts65Dn' thereby leading to Binary Classification.
- The Treatment_Behavior column has 4 classes 'Memantine_C/S', 'Memantine_S/C', 'Saline_C/S', 'Saline_S/C' thereby leading to Multi Classification.
- Techniques used for data preprocessing:
    - Missing value imputation
    - Removing the features with high correlations using correlation matrix
    - Checking whether the classes are balanced in both the target columns
- Classification Models used: Elastic Net Logistic Regression, Neural Networks, Support Vector Machines, and Random Forests and finding the best hyperparameters for both binary and multi-class classification problems 
- Evaluating Metrics Used: Accuracy and F1-score
- Finding the important features by using the coefficients of each feature obtained after training in each model. Also removed the features of less importance with reference to all the 4 models and again trained the top models to see the improvement in the model performance.
- Preproccessed the [Test data](https://www.ee.iitb.ac.in/~asethi/Dump/MouseTest.csv) and predicted the target columns using the top models.



