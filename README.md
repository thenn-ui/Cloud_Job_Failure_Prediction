# Cloud Job Failure Prediction

## Overview
This project aims to predict job failures in cloud computing environments, enabling proactive resource management and minimizing operational costs. By leveraging machine learning models, we address the critical issue of cloud resource optimization while handling the challenges of imbalanced datasets.

## Problem Statement
Cloud architectures often face challenges with job failures, which can lead to increased queue sizes, delayed dependent jobs, and reduced overall efficiency. Current solutions rely on passive approaches like redundancy and load balancing, which increase operational costs. Our objective is to develop predictive models that identify potential failures early, allowing for timely rescheduling or termination of problematic jobs.

## Key Features
- **Dataset**: Google Cluster Trace 2011 dataset, processed into combined tables from job, task event, and task usage data.
- **Imbalance Handling**: Applied SMOTE oversampling to address class imbalance and improve prediction of failure cases.
- **Machine Learning Models**: Implemented Logistic Regression, Random Forest, Gradient Boosting, Support Vector Machines, K-Nearest Neighbors, Naive Bayes, and Neural Networks.
- **Hyperparameter Tuning**: Used GridSearchCV for optimal model configuration.
- **Evaluation Metrics**: Employed precision, recall, F1-score, and accuracy, along with bias-variance analysis.
- **Visualization**: Included comprehensive plots to analyze model performance and training time.

## Results
The models demonstrated high accuracy but varied performance on failure predictions due to the dataset's imbalance and over-sampling techniques. Metrics such as precision, recall, and F1-score highlighted the trade-offs across models, emphasizing the need for careful tuning and evaluation.

## Conclusion
This project showcases the potential of predictive modeling in cloud resource optimization. By identifying potential failures early, cloud services can improve their performance-per-dollar (PPD) ratio, reduce downtime, and enhance user satisfaction.

## How to Run
1. Clone the repository.
2. Install dependencies from `requirements.txt`.
3. Run the preprocessing scripts to generate the combined dataset.
4. Execute the training script to evaluate models and view results.

## Contact
For inquiries, please open an issue or reach out to the repository owner.
