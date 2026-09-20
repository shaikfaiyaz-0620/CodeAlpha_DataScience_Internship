
# Iris Flower Classification using Machine Learning

## Project Objective

The objective of this project is to classify Iris flowers into three species — Iris-setosa, Iris-versicolor, and Iris-virginica — using machine learning classification algorithms.

## Dataset

The Iris dataset contains 150 samples with 4 features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The target variable is `Species`.

## Data Analysis

The project includes:

- Dataset information and structure
- Missing value checking
- Target class distribution
- Species distribution visualization
- Pair plot visualization
- Feature correlation heatmap
- Separation of features and target
- Train-test split

## Machine Learning Algorithms Used

The following classification algorithms were implemented and compared:

1. Random Forest
2. K-Nearest Neighbors (KNN)
3. Logistic Regression
4. Decision Tree
5. Support Vector Machine (SVM)

## Model Comparison

The models were trained and evaluated using the same train-test split.

| Model | Accuracy |
|---|---:|
| Random Forest | 90.00% |
| KNN | 100.00% |
| Logistic Regression | 96.67% |
| Decision Tree | 93.33% |
| SVM | 96.67% |

## Best Model

The K-Nearest Neighbors (KNN) model achieved **100% test accuracy**, correctly classifying all 30 test samples.

The final evaluation includes:

- Accuracy
- Classification Report
- Confusion Matrix
- Actual vs Predicted comparison

## Final Model

KNN was used as the final model for Iris flower classification.

The trained KNN model was also saved using Joblib as:

`iris_knn_model.pkl`

## Conclusion

The project successfully demonstrates how machine learning classification algorithms can be used to classify Iris flower species based on their sepal and petal measurements.
