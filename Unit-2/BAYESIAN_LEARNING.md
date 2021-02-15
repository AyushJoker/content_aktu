# Bayes theorem 

- Bayes Theorem is a method of calculating conditional probability.
- Conditional probability is the probability of an event happening

  ![Bayes](https://cdn.analyticsvidhya.com/wp-content/uploads/2019/05/thomasBayes.png)

- Now, let’s understand this mathematically. This will be pretty simple now that our basics are clear.

- Consider that A and B are any two events from a sample space S where P(B) ≠ 0. Using our understanding of conditional probability, we have:

```
P(A|B) = P(A ∩ B) / P(B)
Similarly, P(B|A) = P(A ∩ B) / P(A)
It follows that P(A ∩ B) = P(A|B) * P(B) = P(B|A) * P(A)
Thus, P(A|B) = P(B|A)*P(A) / P(B)
```

This is the Bayes’ Theorem.

- Here, P(A) and P(B) are probabilities of observing A and B independently of each other. That’s why we can say that they are marginal probabilities. P(B|A) and P(A|B) are conditional probabilities.

- P(A) is called Prior probability and P(B) is called Evidence.

- P(B|A) is called Likelihood and P(A|B) is called Posterior probability.

  ![Bayes theorem](https://cdn.analyticsvidhya.com/wp-content/uploads/2019/05/Capture.jpg1.jpg)

---

## Bayes Optimal Classifier

- The Bayes Optimal Classifier is a probabilistic model that makes the most probable prediction for a new example.

- It is described using the Bayes Theorem that provides a principled way for calculating a conditional probability.

-  It is also closely related to the Maximum a Posteriori: a probabilistic framework referred to as MAP that finds the most probable hypothesis for a training dataset

- In general, the most probable classification of the new instance is obtained by combining the predictions of all hypotheses, weighted by their posterior probabilities.

---

#  Naïve Bayes classifier

- Naive Bayes classifiers are a collection of classification algorithms based on Bayes’ Theorem. It is not a single algorithm but a family of algorithms where all of them share a common principle, i.e. every pair of features being classified is independent of each other.

- Naive Bayes is called naive because it assumes that each input variable is independent. This is a strong assumption and unrealistic for real data; however, the technique is very effective on a large range of complex problems.

***Numerical :***

**Apply the algo to predict fruit type in below type :**

| Fruits | Yellow | Sweet | Long | Total |
| --     | --     | --    | ---  | --    |
| Orange  | 350    | 450   | 0    | 650   |   
| Banana | 400    | 300   | 350  | 400   |
| Others | 50     | 100   | 50   | 150   |
|Total   | 800    | 850   | 400  | 1200  |










