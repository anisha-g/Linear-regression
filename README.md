# Linear regression

In this Project, we'll build a linear regression model to predict Sales using an appropriate predictor variable.


## Steps Involved

### 1.Reading and Understanding the Data

### 2.Visualising the Data
        Inference-: The variable TV seems to be most correlated with Sales.Hence, we perform simple linear           regression using TV as our feature variable.



### 3.Performing Simple Linear Regression

#### Equation of Linear Regression

        The equation of a linear regression model is expressed as:
        
        $$ y = c + m_1x_1 + m_2x_2 + \ldots + m_nx_n $$
        
        Where:
        - \( y \) is the response (dependent variable).
        - \( c \) is the intercept (constant term).
        - \( m_1 \) is the coefficient for the first feature (\( x_1 \)).
        - \( m_n \) is the coefficient for the nth feature (\( x_n \)).
        
        In our specific case, the linear regression model is:
        
        $$ y = c + m_1 \times TV $$
        
        Here, the \( m \) values are referred to as the model **coefficients** or **model parameters**.
        These coefficients indicate the strength and direction of the relationship between each feature and
        the response variable.

#### Generic Steps in model building

##### Create X and y
    We first assign the feature variable, `TV`, in this case, to the variable `X` and the response
    variable Sales`, to the variable `y`.

##### Create train and test sets(70-30),
##### Train your model on the training set(i.e, learn the coefficients)
##### Evaluate the model(training set, test set)