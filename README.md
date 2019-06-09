# Linear-Regression-with-SGD

Data Set Characteristics:  

    :Number of Instances: 506 

    :Number of Attributes: 13 numeric/categorical predictive
    
    :Median Value (attribute 14) is usually the target

    :Attribute Information (in order):
        - CRIM     per capita crime rate by town
        - ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
        - INDUS    proportion of non-retail business acres per town
        - CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
        - NOX      nitric oxides concentration (parts per 10 million)
        - RM       average number of rooms per dwelling
        - AGE      proportion of owner-occupied units built prior to 1940
        - DIS      weighted distances to five Boston employment centres
        - RAD      index of accessibility to radial highways
        - TAX      full-value property-tax rate per $10,000
        - PTRATIO  pupil-teacher ratio by town
        - B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
        - LSTAT    % lower status of the population
        - MEDV     Median value of owner-occupied homes in $1000's
        
        
   #### Objective:
        1. Implement your own version of sklearn SGDRegresser.
        2. Plot a chart of predicted values Vs actual values of your own SGD Implementation
        3. Now try out the SGDRegresser of sklearn and plot the chart of predicted values Vs actual values
        4. In a tabular format, compare the weights obtained from your own implementation with the weights obtained after applying sklearn's SGDRegresser.
        5. Also compare the MSE obtained from your custom implementation of SGDRegressor and that of sklearns implementation.
        6. Try to get the weights & MSE of your custom implementation, similar to the weights and MSE of sklearns implementation.
        7. Conclusion
