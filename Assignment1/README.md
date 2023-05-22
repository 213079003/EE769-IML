## PART1:
- Coded and tested gradient descent to train and validate L1 and L2 penalized linear regression from scratch.
- Also the weights for L2 Regularisation Linear Regression are obtained by finding the Pseudo-inverse Method. They are computed by using the below formula:
           w = (X'X + λI)^(-1) X't
        where
        X : data matrix with m sample points and n features(including the column of 1's) i.e mxn matrix
        X': transpose of X i.e of order nxm matrix
        I : identity matrix of order same as X'X (i.e nxn) in order to obey addition
        λ: Regularisation Parameter
        t : the target variable of order mx1 
        w : weights vector of order nx1

## PART2: 
- Read training data from: https://www.ee.iitb.ac.in/~asethi/Dump/TempTrain.csv only.
- Find the best lamda for 
    - **MSE+λL2(w)** loss function.
    - **MSE+λL1(w)** loss function.
    - **pseudo-inv method**
- Plot the training and validation RMSE vs. 1/λ (1/λ represents model complexity) for above 3 methods. Print weights, validation RMSE, validation NRMSE for the best λ.
- Read test data from: https://www.ee.iitb.ac.in/~asethi/Dump/TempTest.csv only. Predict its dependent (missing last column) using the model with the lowest MSE, RMSE, or NRMSE. 
