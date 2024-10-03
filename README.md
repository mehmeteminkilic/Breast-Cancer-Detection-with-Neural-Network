Breast Cancer Detection with Machine Learning

Overview
This repository contains a project focused on breast cancer detection using a dataset derived from the scikit-learn library. The dataset comprises tumor characteristics of cell nuclei extracted from digitized images of fine needle aspirates of breast masses. The target label, named "diagnosis," consists of binary values (0 and 1), representing benign and malignant tumors, respectively.

Objective
The primary objective of this project is to compare the performance of various machine learning classifiers in detecting breast cancer and to visualize the accuracy of each model.

Classifiers Used
The following classifiers were implemented and evaluated in this project:
Logistic Regression (LR)
K-Nearest Neighbor (KNN)
Linear Discriminant Analysis (LDA) 
Decision Tree Classifier (DTC) 
Random Forest Classifier (RFC) 
Support Vector Machine (SVM) 
Naive Bayes (Bernoulli) (NB) 
Neural Network (NN)

Methodology
Data Loading: The breast cancer detection dataset was loaded from the scikit-learn library. Preprocessing: Basic data preprocessing steps were performed (if applicable).
Model Training: Each classifier was trained using Grid Search for optimal hyperparameter tuning.
Model Evaluation: Accuracy scores for each model were calculated to assess performance. Results Visualization: The accuracy scores were compared and visualized through plots.

Results
The performance of each model is summarized and compared through visual plots, allowing you to see which classifier performs best in terms of accuracy.

Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for suggestions and improvements.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements
scikit-learn for the dataset and tools. Matplotlib and Seaborn for data visualization.
