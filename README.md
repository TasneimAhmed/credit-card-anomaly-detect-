**One-Class Support Vector Machines**:

One-Class Support Vector Machine (One-Class SVM) is an anomaly detection algorithm used to detect outliers or anomalies in a dataset where the majority of data points belong to one class. It is particularly useful when dealing with unbalanced datasets or when only normal data is available for training.

one-class SVM is not used to perform binary or multiclass classification tasks but to detect outliers or novelties within the dataset. 
The heart of OCSVM lies in its commitment to maximizing the margin between the normal instances and the boundary. 
A larger margin provides a robust separation, enhancing the model's ability to discern anomalies during testing. 
achieved through a specified kernel function and a nuanced parameter termed "nu." This parameter acts as an upper limit on the fraction of margin errors and support vectors

The training process involves fitting the One-Class SVM model to the normal data points. The algorithm learns a hyperplane (or decision boundary) that separates the normal data points from the origin in the transformed feature space.


![credit-card-fraud-detection](https://github.com/user-attachments/assets/0cacc82c-3583-49fd-8946-875f3d0e0f99)
