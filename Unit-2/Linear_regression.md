# Linear Regression 

- Linear regression is one of the easiest and most popular Machine Learning algorithms. 

- It is a statistical method that is used for predictive analysis. Linear regression makes predictions for continuous/real or numeric variables such as sales, salary, age, product price, etc.

- Linear regression algorithm shows a linear relationship between a dependent (y) and one or more independent (y) variables, hence called as linear regression.

- The linear regression model provides a sloped straight line representing the relationship between the variables.

  - **Consider the below image :**

  ![Linear regression model](https://static.javatpoint.com/tutorial/machine-learning/images/linear-regression-in-machine-learning.png)

- we can represent a linear regression as:

`y= a0+a1x+ ε`
### **Here**,

- Y= Dependent Variable (Target Variable)
- X= Independent Variable (predictor Variable)
- a0= intercept of the line (Gives an additional degree of freedom)
- a1 = Linear regression coefficient (scale factor to each input value).
- ε = random error

## Types of Linear Regression :

- Linear regression can be further divided into two types of the algorithm:
  - **Simple Linear Regression:**

     If a single independent variable is used to predict the value of a numerical dependent variable, then such a Linear Regression algorithm is called Simple Linear Regression.
  - **Multiple Linear regression:**

    If more than one independent variable is used to predict the value of a numerical dependent variable, then such a Linear Regression algorithm is called Multiple Linear Regression.

##  Linear Regression Line :

A linear line showing the relationship between the dependent and independent variables is called a regression line. A regression line can show two types of relationship:

- ### Positive Linear Relationship:

   If the dependent variable increases on the Y-axis and independent variable increases on X-axis, then such a relationship is termed as a Positive linear relationship.

   ![+ve linear regression](https://static.javatpoint.com/tutorial/machine-learning/images/linear-regression-in-machine-learning2.png)

- ### Negative Linear Relationship:

  If the dependent variable decreases on the Y-axis and independent variable increases on the X-axis, then such a relationship is called a negative linear relationship.

  ![-ve linear](https://static.javatpoint.com/tutorial/machine-learning/images/linear-regression-in-machine-learning3.png)]

 ## **Finding the best fit line:**

 - our main goal is to find the best fit line that means the error between predicted values and actual values should be minimized.
 - The different values for weights or the coefficient of lines (a0, a1) gives a different line of regression, so we need to calculate the best values for a0 and a1 to find the best fit line, so to calculate this we use `cost function.`

 ### Cost function:

- The different values for weights or coefficient of lines (a0, a1) gives the different line of regression, and the cost function is used to estimate the values of the coefficient for the best fit line.

- Cost function optimizes the regression coefficients or weights. It measures how a linear regression model is performing.

- We can use the cost function to find the accuracy of the mapping function, which maps the input variable to the output variable. This mapping function is also known as Hypothesis function.

For Linear Regression, we use the Mean Squared Error (MSE) cost function, which is the average of squared error occurred between the predicted values and actual values. It can be written as:

- For the above linear equation, MSE can be calculated as:
![MSE](https://static.javatpoint.com/tutorial/machine-learning/images/linear-regression-in-machine-learning4.png)

**Where,**

- N=Total number of observation
- Yi = Actual value
- (a1xi+a0)= Predicted value.
---

## **Simple Linear Regression in Machine Learning :**

- Simple Linear Regression is a type of Regression algorithms that models the relationship between a dependent variable and a single independent variable. The relationship shown by a Simple Linear Regression model is linear or a sloped straight line, hence it is called Simple Linear Regression.

- The key point in Simple Linear Regression is that the dependent variable must be a continuous/real value.

- The `Simple Linear Regression model` can be represented using the below equation:

>y= a0+a1x+ ε 

**Where:**

- a0= It is the intercept of the Regression line (can be obtained putting x=0)
- a1= It is the slope of the regression line, which tells whether the line is increasing or decreasing.
- ε = The error term. (For a good model it will be negligible)
---

## **Multiple Linear Regression :**

- Multiple Linear Regression is an extension of Simple Linear regression as it takes more than one predictor variable to predict the response variable. We can define it as:

> *Multiple Linear Regression is one of the important regression algorithms which models the linear relationship between a single dependent continuous variable and more than one independent variable.*

**Example:**

- Prediction of CO2 emission based on engine size and number of cylinders in a car.

- **Some key points about MLR:**
 
  - For MLR, the dependent or target variable(Y) must be the continuous/real, but the predictor or independent variable may be of continuous or categorical form.
   - Each feature variable must model the linear relationship with the dependent variable.
   - MLR tries to fit a regression line through a multidimensional space of data-points.

   ### Formula and Calculation of Multiple Linear Regression : 

   >Y = b0 + b1 * x1 + b2 * x2 + b3 * x3 + …… bn * xn

   **Here,**
   - Y = Dependent variable
   - x1, x2, x3, …… xn = multiple independent variables

