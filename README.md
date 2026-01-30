Project Title:
KNN – Handwritten Digit Classification

Objective:
This project focuses on classifying handwritten digits using the K-Nearest Neighbors (KNN) algorithm and understanding distance-based classification.

Datasets Used:
Sklearn Digits Dataset (load_digits)
MNIST Handwritten Digit Dataset

Tools & Libraries:
Python
Scikit-learn
Matplotlib
TensorFlow (for MNIST)
NumPy

Steps Performed:

➊ Loaded both datasets and checked their structure
➋ Visualized sample digit images to verify labels
➌ Split the data into training and testing sets
➍ Applied feature scaling using StandardScaler
➎ Trained the KNN model with K values (3, 5, 7, 9)
➏ Evaluated accuracy for each K value
➐ Plotted Accuracy vs K graph
➑ Generated confusion matrices for performance analysis

Results:
The KNN model achieved good accuracy on both datasets.
Lower K values performed better in most cases.

Conclusion:
This project demonstrates distance-based classification using KNN and highlights the importance of K value tuning and feature scaling for better performance.
