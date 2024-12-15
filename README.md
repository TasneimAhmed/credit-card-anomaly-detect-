## **One-Class Support Vector Machines (One-Class SVM)**
## Overview
One-Class Support Vector Machine (One-Class SVM) is an anomaly detection algorithm used to identify outliers or anomalies in datasets where the majority of data belongs to a single class. It is particularly effective for unbalanced datasets or cases where only "normal" data is available during training.

Unlike traditional classification algorithms, One-Class SVM is not designed for binary or multiclass classification tasks. Instead, its primary goal is to detect outliers or novelties within the dataset.

## How It Works
**Training Process:**
The One-Class SVM model is trained only on the "normal" data points.
It learns a decision boundary (hyperplane) in the transformed feature space that separates the normal data points from the origin.

**Maximizing the Margin:**
The core idea is to maximize the margin between the normal data points and the decision boundary.
This ensures a robust separation, improving the model's ability to identify anomalies.

**Key Parameters:**
Kernel Function: Determines the shape of the hyperplane in the transformed space. Common kernels include linear, RBF (Radial Basis Function), and polynomial.
Nu (ν): A critical parameter that specifies the upper bound on the fraction of margin errors and support vectors. It effectively controls the model’s tolerance for anomalies.

## Why One-Class SVM for Anomaly Detection?
**Handles Imbalanced Datasets:** Works well when one class dominates the data distribution.
**No Need for Labeled Anomalies:** Can train solely on normal data points without requiring labeled anomalies.
**Robust Separation:** Maximizes the margin to ensure a clear boundary between normal instances and potential outliers.
## Key Points to Remember
One-Class SVM is not a standard classification tool but a specialized anomaly detection technique.
It is sensitive to the choice of kernel and nu parameter. Careful tuning can greatly enhance its performance.
It excels in unsupervised anomaly detection tasks where labeled data is limited or unavailable.

## Dataset URL: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

![credit-card-fraud-detection](https://github.com/user-attachments/assets/0cacc82c-3583-49fd-8946-875f3d0e0f99)
