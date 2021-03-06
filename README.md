# Decision-Trees-for-Breast-Cancer-Dataset
Decision Trees have been developed using Python for Breast Cancer Dataset

The data set has the following attributes:

   1. Class: no-recurrence-events, recurrence-events
   2. age: 10-19, 20-29, 30-39, 40-49, 50-59, 60-69, 70-79, 80-89, 90-99.
   3. menopause: lt40, ge40, premeno.
   4. tumor-size: 0-4, 5-9, 10-14, 15-19, 20-24, 25-29, 30-34, 35-39, 40-44,
                  45-49, 50-54, 55-59.
   5. inv-nodes: 0-2, 3-5, 6-8, 9-11, 12-14, 15-17, 18-20, 21-23, 24-26,
                 27-29, 30-32, 33-35, 36-39.
   6. node-caps: yes, no.
   7. deg-malig: 1, 2, 3.
   8. breast: left, right.
   9. breast-quad: left-up, left-low, right-up,	right-low, central.
  10. irradiat:	yes, no.
  
  Missing Attribute Values: 
   Attribute #:  Number of instances with missing values:
   6.             8
   9.             1.
   
   Class Distribution:
    1. no-recurrence-events: 201 instances
    2. recurrence-events: 85 instances
    Total : 286 instances
    
    Objective: Primarily to establish a decision rule using Decision Trees to classify the recurrence of Cancer based on the other 9 attributes. 
    Both Gini and Entropy methods are tried out. Several machine learning models such as Random Forest, Adaboost and Gradient Descent with Grid Search 
    are worked out as an illustration. Further, confusion matrix, ROC curve, Precision-Recall curves, accuracy and classification reports are generated.
