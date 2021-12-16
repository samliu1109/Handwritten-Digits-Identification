# Handwritten-Digits-Identification

Executive Summary

Problem:
The MNIST ("Modified National Institute of Standards and Technology") Handwritten Digits dataset is considered as the “Hello World” of Computer Vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

In this project, I built three models to identify digits from a dataset of tens of thousands of handwritten images. I will discover the handwritten digits from 0 – 9, which is a multi-classification problem. 

Model Performance Summary & Interpretation:

model_name	        (accuracy)


mlp_training(0.8967585) | mlp_testing (0.8772423)

rf_training(0.9998566) | rf_testing(0.9659973)

xgboost_training(0.9739530) | xgboost_testing(0.9472557)

* Comparing three models in the analysis, the random forest shows the highest accuracy in the test data, roughly 96.5%, which is higher than the mlp's 87% and xgboost’s 94%.



