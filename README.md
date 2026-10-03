# Wine Classification using Machine Learning

## Project Overview

This project focuses on classifying wines into different classes using machine learning algorithms based on their chemical properties.

The Wine dataset contains 178 wine samples with 13 chemical features and 3 target classes.

## Dataset

The dataset contains the following features:

- Alcohol
- Malic Acid
- Ash
- Alcalinity of Ash
- Magnesium
- Total Phenols
- Flavanoids
- Nonflavanoid Phenols
- Proanthocyanins
- Color Intensity
- Hue
- OD280/OD315 of Diluted Wines
- Proline

### Dataset Details

- Number of samples: 178
- Number of features: 13
- Number of classes: 3
- Target variable: `target`

## Project Workflow

1. Load the Wine dataset
2. Perform exploratory data analysis
3. Check missing values
4. Analyze target class distribution
5. Perform correlation analysis
6. Separate features and target
7. Split the dataset into training and testing data
8. Apply feature scaling
9. Train machine learning classification models
10. Compare model performance
11. Evaluate the final model using a classification report and confusion matrix
12. Analyze feature importance

## Machine Learning Algorithms

The following algorithms were implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

## Train-Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

Stratified splitting was used to maintain the class distribution.

Feature scaling was performed using `StandardScaler`.

## Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 97.22% |
| KNN | 97.22% |
| Decision Tree | 94.44% |
| Random Forest | 100.00% |
| SVM | 97.22% |

Random Forest achieved **100% accuracy on the unseen test set for the selected 80:20 train-test split**, correctly classifying all 36 test samples.

## Evaluation

The final Random Forest model was evaluated using:

- Accuracy
- Classification Report
- Confusion Matrix
- Feature Importance

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Conclusion

The project demonstrates that machine learning algorithms can effectively classify wine samples based on their chemical properties.

Among the models evaluated, Random Forest achieved the highest test accuracy of 100% on the selected unseen test set.
