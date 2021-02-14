# Support Vector Machine Algorithm

- Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms.

- It is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

- The goal of the SVM algorithm is to create the best line or decision boundary that can segregate n-dimensional space into classes so that we can easily put the new data point in the correct category in the future. This best decision boundary is called a hyperplane.

- SVM chooses the extreme points/vectors that help in creating the hyperplane.

- These extreme cases are called as support vectors, and hence algorithm is termed as Support Vector Machine.

![SVM](https://static.javatpoint.com/tutorial/machine-learning/images/support-vector-machine-algorithm.png)

- **Consider the above diagram in which there are two different categories that are classified using a decision boundary or hyperplane**

## **Types of SVM:**

- **There can be two type of SVM :**

     - ### Linear SVM: 

         - Linear SVM is used for linearly separable data, which means if a dataset can be classified into two classes by using a single straight line, then such data is termed as linearly separable data, and classifier is used called as Linear SVM classifier.

    - ### Non-linear SVM:

        - Non-Linear SVM is used for non-linearly 
        separated data, which means if a dataset cannot 
        be classified by using a straight line, then such 
        data is termed as non-linear data and classifier 
        used is called as Non-linear SVM classifier.

---

## Hyperplane and Support Vectors in the SVM algorithm:

**Hyperplane:**

 -  There can be multiple lines/decision boundaries to segregate the classes in n-dimensional space, but we need to find out the best decision boundary that helps to classify the data points. This best boundary is known as the hyperplane of SVM.

 - We always create a hyperplane that has a maximum margin, which means the maximum distance between the data points.

 **Support Vectors:**

 - The data points or vectors that are the closest to the hyperplane and which affect the position of the hyperplane are termed as Support Vector. Since these vectors support the hyperplane, hence called a Support vector.

 ----

 ### ***Numericals based on Hyperplane:***


 - **Plot hyperplane of the following points. (1,1),(2,1),(2,-1),(1,-1),(4,0),(5,1),(5,-1),(6,0).** 

   ![](https://raw.githubusercontent.com/AyushJoker/content_aktu/main/assets/HyperplaneSoln-1.jpg)


   ![](https://raw.githubusercontent.com/AyushJoker/content_aktu/main/assets/HyperplaneSoln-2.jpg)
  