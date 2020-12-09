# Project-with-Tidymodels

### Option A

Train, evaluate, and compare binary classifiers for outcome_2 as a function of the inputs: xA,xB,x01:x11.

### Option B

Train, evaluate, and compare regression models for response_1 as a function of the Step 1 inputs: xA,xB,x01:x06.
Train, evaluate, and compare binary classifiers for outcome_2as a function of the inputs: xA,xB,response_1,x07:x11.

## Part II: Exploration

•Visualize the distribution of the variables in the data set.

•Consider breaking up the continuous variables based on the discrete xA and xB variables.

•Visualize the relationships between the inputs.

•Visualize the relationships between response_1and the Step 1 inputs.

## Part II: Regression models – A

•response_1 as a function of the step 1 inputs using linear modeling techniques.

•Use lm()to fit linear models with the entire data set. 

1. Just the discrete inputs –additive terms.

2. Just the continuous inputs –additive terms.

3. All step 1 inputs –additive terms.

4. All.

•performance metric

•Visualize the coefficient summaries for best two models. 

## Part II: Regression models – B

•Bayesian linear models.

•Laplace Approximation approach.

•rstanarm’s stan_lm() function to fit full Bayesian linear models with syntax similar to R’s lm()function.

•performance metric

•Visualize the posterior distributions on the coefficients for best model. 

•the uncertainty in the noise (residual error), 𝜎, lm() maximum likelihood estimate (MLE) on 𝜎 relate to the posterior uncertainty on 𝜎

## Part II: Regression models – C

•Train, evaluate, tune, and compare more complex methods via resampling using tidymodels. 

1. Linear additive model (method=‘lm’)

2. Regularized regression with Elastic net (method=‘glmnet’).

3. Neural network

4. Random forest

5. Gradient boosted tree

6. SVM

7. KNN

## Part III and Part IV: Binary classification Option B and A

•Train, evaluate, tune, and compare binary classifiers via resampling using tidymodels. 

1. Linear additive model (method=‘lm’)

2. Regularized regression with Elastic net (method=‘glmnet’).

3. Neural network

4. Random forest

5. Gradient boosted tree

6. SVM

7. KNN

## Part V: Interpretation and “optimization”

•Identify the most important variables associated with best performing models.

•Visualize the probability of failure as a function of most important variables.

