## Restaurant Review (Classification Analysis)

### Introduction
This repository focuses on performing sentiment analysis on a dataset comprising restaurant reviews. The goal is to classify reviews into two categories: positive (labeled as 1) and negative (labeled as 0). Three different machine learning models—Naïve Bayes, Random Forest, and XGBoost—have been implemented to predict sentiment.

### Dataset
The dataset consists of entity-level sentiment annotations for restaurant reviews. Each review is labeled as either positive or negative, providing a binary classification challenge. The target is to build models that accurately classify sentiments based on the review text.

### Models Implemented
- Naïve Bayes:
Utilizing the probabilistic approach of Naïve Bayes, this model leverages the independence assumption between features to predict sentiment.
- Random Forest:
Random Forest employs an ensemble of decision trees, each trained on a subset of the data. The final prediction is based on the votes of individual trees.
- XGBoost:
XGBoost is an optimized gradient boosting algorithm known for its efficiency and accuracy. It sequentially builds trees to correct errors made by previous models.

### Evaluation Metric
The performance of each model is assessed using the accuracy_score, which measures the proportion of correctly classified instances among all instances.

### Usage
1. Data Preparation:
Ensure your dataset is formatted similarly to the provided example.
Split the data into training and testing sets.
2. Model Implementation:
Choose the desired model script (naive_bayes.py, random_forest.py, xgboost.py) to train and evaluate the respective model.
3. Evaluation:
Evaluate the model's performance using the accuracy_score provided in the results.
4. Results
The repository includes the accuracy scores for each model, allowing for a direct comparison of their performance on the given dataset.

### Conclusion
Explore and experiment with these models to understand their strengths and limitations in sentiment analysis for restaurant reviews. Contributions and enhancements are welcomed!

Feel free to open issues for questions or improvements, and enjoy exploring sentiment analysis in restaurant reviews!

