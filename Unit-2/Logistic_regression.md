# Logistic Regression in Machine Learning

- Logistic regression is one of the most popular Machine Learning algorithms, which comes under the Supervised Learning technique.

- It is used for predicting the categorical dependent variable using a given set of independent variables.

- Logistic Regression is much similar to the Linear Regression except that how they are used. Linear Regression is used for solving Regression problems, whereas Logistic regression is used for solving the classification problems.

- In Logistic regression, instead of fitting a regression line, we fit an "S" shaped logistic function, which predicts two maximum values (0 or 1).

- The outcome must be a categorical or discrete value. It can be either Yes or No, 0 or 1, true or False, etc. but instead of giving the exact value as 0 and 1, it gives the probabilistic values which lie between 0 and 1.

- Logistic Regression can be used to classify the observations using different types of data and can easily determine the most effective variables used for the classification. `The below image is showing the logistic function:`

![graphLogistic](https://static.javatpoint.com/tutorial/machine-learning/images/logistic-regression-in-machine-learning.png)

---

## Types of Logistic Regression :

Generally, logistic regression means binary logistic regression having binary target variables, but there can be two more categories of target variables that can be predicted by it. Based on those number of categories, Logistic regression can be divided into following types −

### **Binary or Binomial :**

In such a kind of classification, a dependent variable will have only two possible types either 1 and 0. For example, these variables may represent success or failure, yes or no, win or loss etc.

### **Multinomial:**

In such a kind of classification, dependent variable can have 3 or more possible unordered types or the types having no quantitative significance. For example, these variables may represent “Type A” or “Type B” or “Type C”.

### **Ordinal:**

In such a kind of classification, dependent variable can have 3 or more possible ordered types or the types having a quantitative significance. For example, these variables may represent “poor” or “good”, “very good”, “Excellent” and each category can have the scores like 0,1,2,3.

## Logistic Regression Equation:

The Logistic regression equation can be obtained from the Linear Regression equation. The mathematical steps to get Logistic Regression equations are given below:

- We know the equation of the straight line can be written as:

   ![Equation st line](https://static.javatpoint.com/tutorial/machine-learning/images/logistic-regression-in-machine-learning2.png)

- In Logistic Regression y can be between 0 and 1 only, so for this let's divide the above equation by (1-y):

   ![eqn](https://static.javatpoint.com/tutorial/machine-learning/images/logistic-regression-in-machine-learning3.png)

- But we need range between `-[infinity] to +[infinity]`, then take logarithm of the equation it will become:

   ![eqn](https://static.javatpoint.com/tutorial/machine-learning/images/logistic-regression-in-machine-learning4.png)

- *The above equation is the final equation for Logistic Regression.*

