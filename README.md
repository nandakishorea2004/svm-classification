# SVM Classification with PCA Visualization

A machine learning classification project using a **Support Vector Machine (SVM)** to classify data into low, medium, and high target classes.

The project includes data preprocessing, feature scaling, SVM classification, model evaluation, and PCA-based visualization.

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Support Vector Machine (SVM)
- PCA
- Machine Learning

## ⚙️ Machine Learning Workflow

1. Load the dataset
2. Rename the target column
3. Create three target classes:
   - Low
   - Medium
   - High
4. Separate features and target
5. Split the dataset into training and testing sets
6. Apply StandardScaler for feature scaling
7. Train a Linear SVM classifier
8. Generate predictions
9. Evaluate the classification model
10. Apply PCA for two-dimensional visualization

## 🤖 Model

**Algorithm:** Support Vector Machine (SVM)

**Kernel:** Linear

**Test Size:** 20%

**Random State:** 42

## 📊 Visualization

Principal Component Analysis (PCA) is used to reduce the test data to two dimensions and visualize the distribution of the three target classes.

## 📈 Evaluation

The project imports the following evaluation metrics:

- Accuracy Score
- Classification Report
- Confusion Matrix

## 📁 Project Structure

```text
svm-classification/
│
├── SVM DATA.csv
├── svm_classification.ipynb
├── README.md
└── requirements.txt
