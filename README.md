# Instance-based-learning-Euclidean-distance-K-selection
# Iris Dataset - KNN Regression

This project demonstrates the application of **K-Nearest Neighbors (KNN) Regression** on the popular **Iris dataset** using Python. It involves loading, preprocessing, training, and evaluating a regression model to predict features of iris flowers.

## Dataset

The Iris dataset contains 150 samples from three species of Iris flowers: Setosa, Versicolor, and Virginica. Each sample includes four features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

## Objective

To predict one of the features (e.g., petal width) using the others through KNN Regression, and analyze the model's performance.

## Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (for visualization, if used)

## Steps Performed

1. **Data Loading**: Loaded the Iris dataset using `sklearn.datasets`.
2. **Preprocessing**: Converted the data into a DataFrame, selected features and target variable.
3. **Train-Test Split**: Divided the dataset into training and testing sets.
4. **Modeling**: Applied `KNeighborsRegressor` from Scikit-learn.
5. **Evaluation**: Measured performance using metrics such as:
   - Mean Squared Error (MSE)
   - R² Score
   - Visualization of predictions (if included)

## Results

The model was trained and evaluated, showing how well KNN Regression can approximate the selected feature. The accuracy depends on the chosen number of neighbors (`k`) and the distribution of input features.

