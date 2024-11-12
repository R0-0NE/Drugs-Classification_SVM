## Drug Classification Using SVM
### This project demonstrates a machine learning model for classifying drug types based on patient data, using Support Vector Machines (SVM). The dataset contains information on patient age, sex, blood pressure, cholesterol levels, sodium-to-potassium ratio, and the type of drug prescribed. The model predicts which drug class is most suitable for a patient based on these features.

### Project Overview

### Dataset: Contains 200 samples with 6 columns — Age, Sex, BP, Cholesterol, Na_to_K, and Drug.

### Objective: To classify the type of drug based on the patient's characteristics.

### Algorithms Used: Support Vector Machine (SVM) with different kernels (linear, RBF, and polynomial).

Steps
### Data Preprocessing:

##### Handled categorical data using label encoding for Sex and Cholesterol.
##### Created dummy variables for BP (blood pressure) and replaced boolean values with binary (1, 0).
##### Standardized the feature values for better model performance.
### Exploratory Data Analysis (EDA):

Visualized relationships between features using pair plots and computed the correlation matrix.

### Model Training:

Split the dataset into training and test sets.
Tested SVM models with different kernels:

1. Linear Kernel: Achieved 92.5% test accuracy.
2. RBF Kernel: Achieved 87.5% test accuracy.
3. Polynomial Kernel: Evaluated for performance comparison.

### Model Evaluation:

Evaluated model performance using accuracy score, confusion matrix, and classification report.

### Results

###### Best Model: The linear SVM model provided the highest test accuracy.
###### Evaluation Metrics: Accuracy, precision, recall, and F1-score for each drug class.

Dependencies
Python 3.x

### Libraries: pandas, numpy, seaborn, matplotlib, sklearn

### Conclusion
This project showcases how SVM can effectively classify drugs based on patient data, with promising accuracy using a linear kernel. This model could serve as a prototype for developing a drug recommendation system based on patient characteristics.

