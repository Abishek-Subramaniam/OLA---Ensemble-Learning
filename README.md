# Comparison of Models
**1. Random Forest Classifier**

**Precision:**

 Class 0: 0.75

 Class 1: 0.83

**Recall:**

 Class 0: 0.60

 Class 1: 0.90

**F1-Score:**

 Class 0: 0.67 

 Class 1: 0.86

**Accuracy: 0.81**

**ROC AUC Score: 0.8243**

**2. Gradient Boosting Classifier**

**Precision:**

 Class 0: 0.73

 Class 1: 0.82

**Recall:**

 Class 0: 0.57

 Class 1: 0.90

**F1-Score:**

 Class 0: 0.64

 Class 1: 0.86

**Accuracy: 0.79**

**ROC AUC Score: 0.8225**

**Insights and Recommendations**

***Model Performance:***

Both models perform similarly, with the Random Forest classifier having a slightly better overall accuracy **(0.81 vs. 0.79)** and a marginally higher ROC AUC score **(0.8243 vs. 0.8225)**.

The Gradient Boosting classifier also performs well, but the Random Forest classifier slightly edges it out in terms of precision, recall, and F1-score for **Class 0**, which represents drivers who do not leave the company.

***Class Imbalance Impact:***

Both models exhibit better recall for Class 1 (drivers who leave the company), which is essential for retaining drivers as it helps correctly identify those at risk of leaving. 

However, the precision for Class 0 is lower, indicating that some drivers who are predicted to stay might actually leave.

***Primary Focus for Ola's Driver Retention:***

**Precision:** Focus on improving precision for Class 1 to reduce false positives. This will help Ola more accurately identify drivers who are likely to leave, reducing unnecessary retention efforts.

**Recall:** The recall for Class 1 is already high, which is crucial as it helps in identifying most of the drivers who might leave, allowing for timely interventions.

**ROC AUC:** The ROC AUC score for both models is high, indicating good overall model performance.
