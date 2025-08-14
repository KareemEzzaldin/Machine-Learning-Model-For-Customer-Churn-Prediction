# Machine-Learning-Model-For-Customer-Churn-Prediction
Task Title : 

 Customer Churn Prediction with Logistic Regression

Objective :

 Predict subscription cancellations using customer profile and service data while addressing heavy class imbalance.

Approach:

- Loaded and cleaned training and testing datasets.

- Removed null values and duplicates.

- Handled severe class imbalance in both train and test sets using Random - - Over Sampling from imbalanced-learn.

- Applied one-hot encoding to categorical features.

- Scaled numerical features with StandardScaler.

- Ensured consistent feature columns between train and test after encoding.

- Trained a Logistic Regression model with max_iter=1500.

- Evaluated performance on the balanced test set.

Results :

- Accuracy: 98%

- Precision: 98%

- Recall: 98%

- F1-score: 98%

Key Learnings :

- Oversampling with RandomOverSampler is effective for balancing churn data.

- Proper preprocessing ensures stable model training and testing.

- Simple models like Logistic Regression can perform at a high level when features are clean and balanced.

Tools & Technologies :

 Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, imbalanced-learn.

