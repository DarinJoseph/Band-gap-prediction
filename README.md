Band-Gap Prediction

The goal of this project is to predict the band-gap of different materials using machine learning algorithms. The band-gap is a fundamental property of materials that determines their electronic properties, and accurate prediction of the band-gap is crucial for material science research and applications.

Data :

Bandgap_data.xlsx: Dataset containing the band-gap and other properties of various materials.

Code :

Band-gap_predictor.ipynb: Jupyter notebook implementing the training of the dataset using different models.

Project Overview

1. Initial Model Training:

   Four different machine learning models were initially employed to predict the band-gap: Linear Regression, Support Vector Machine (SVM), Random Forest, K-Nearest Neighbors (KNN).
   After evaluating the performance of these models, the Random Forest model emerged as the best performer with the highest initial accuracy.

2. Feature Selection and Tuning:

  Correlation Matrix: Analyzed the correlation matrix to identify and include more relevant features.
  Grid Search: Performed a grid search to optimize the hyperparameters of the Random Forest model.

3. Refinement with Lasso Regression:

   Utilized Lasso Regression to remove redundant features and further refine the dataset, improving the training process.

4. Final Model Training:

   Trained the Random Forest model with the refined features and optimized hyperparameters.

Results

The final Random Forest model achieved an accuracy of 91% on the test set.
