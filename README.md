Breakout Activity: Group Work on Popular Machine Learning MethodsBreakout Activity: Group Work on Popular Machine Learning Methods
In this breakout session, work in groups of 4 to apply your knowledge of popular machine learning methods. Implement and compare different algorithms discussed in Week 6, evaluate their performance, and submit your work on GitHub.
Instructions:
Each group should choose one member to act as the group leader.
Dataset Selection: The group must choose a dataset from Kaggle or another source. The dataset should be appropriate for classification tasks (e.g., healthcare, customer churn, etc.).
Model Implementation: The group should implement at least three machine learning models:
Decision Tree (CART)
K-Nearest Neighbors (KNN)
Random Forest or Naive Bayes
Model Evaluation: Evaluate each model using the following metrics:
Accuracy
Precision
Recall
F1-Score
Dimensionality Reduction: Apply PCA (Principal Component Analysis) or another dimensionality reduction technique if applicable to your dataset, and observe the effect on the models' performance.
Documentation: Each group should document:
A brief description of the dataset.
A comparison of model performance.
Any observations on dimensionality reduction and its impact.
Submission Requirements:
GitHub Repository:
Create a GitHub repository containing all project files, including the Jupyter Notebook or Quarto file, and the rendered PDF.
The repository should include clear documentation for anyone reviewing the project.
GitHub Link:
The group leader must submit the GitHub repository link to the instructor via direct chat in MS Teams after the session.
Time Allotted:
1 hour
Breakout Discussion Questions:
How did the performance of each model compare on your dataset?
Did the application of dimensionality reduction improve or worsen the results? Why?
Which model would you choose for deployment based on the results, and why?


Decision Tree Classification Report:
               precision    recall  f1-score   support

           0       0.88      0.88      0.88      2416
           1       0.52      0.53      0.52       584

    accuracy                           0.81      3000
   macro avg       0.70      0.70      0.70      3000
weighted avg       0.81      0.81      0.81      3000

KNN Classification Report:
               precision    recall  f1-score   support

           0       0.86      0.95      0.90      2416
           1       0.63      0.36      0.46       584

    accuracy                           0.83      3000
   macro avg       0.74      0.65      0.68      3000
weighted avg       0.81      0.83      0.81      3000

Random Forest Classification Report:
               precision    recall  f1-score   support

           0       0.88      0.96      0.92      2416
           1       0.76      0.46      0.57       584

    accuracy                           0.87      3000
   macro avg       0.82      0.71      0.75      3000
weighted avg       0.86      0.87      0.85      3000


Decision Tree with PCA Classification Report:
               precision    recall  f1-score   support

           0       0.84      0.83      0.84      2416
           1       0.34      0.36      0.35       584

    accuracy                           0.74      3000
   macro avg       0.59      0.59      0.59      3000
weighted avg       0.74      0.74      0.74      3000


