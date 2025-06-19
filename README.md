# Machine learning project overview - README
## Topics coverered: Classification Trees, A/B Testing, Predictive Modeling, Hate Speech Detection

Exercise 1: Classification Tree & Evaluation
Task: Analyze a binary classification problem using a decision tree.

Metrics Calculated:

Accuracy: 86.79%

Sensitivity (Recall): 73.76%

Specificity: 92.95%

Diagnosis Logic: Manually applied tree rules to predict diabetes diagnosis based on patient data (e.g., glucose, age, BMI).

Insight: Emphasized the trade-off between sensitivity and specificity, especially in medical contexts like diabetes or COVID testing.

Exercise 2: Hate Speech Classification (Data Analysis)
Goal: Predict whether a sentence contains hate speech using supervised learning methods based on numerical text features.

Models Implemented:
Bagging + Random Forest

Achieved 100% accuracy on training (but likely overfitted)

Dropped high-dimensional text features due to hardware limitations

Support Vector Machine (SVM)

Best performance: ~89.4% accuracy

Handled full feature set and generalized well to unseen data

Included PCA-based decision boundary visualization

Logistic Regression

Final accuracy with optimal threshold: 67.38%

Included ROC curve and odds ratio analysis

Performance limited by feature significance
