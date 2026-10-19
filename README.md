# Netflix Movie Recommendation System

## Overview
This project implements a movie recommendation system using collaborative filtering to predict user ratings and recommend movies based on predicted preferences.

## Algorithm
- Singular Value Decomposition (SVD)
- Collaborative Filtering
- Cross-validation for model evaluation
- Root Mean Squared Error (RMSE) for evaluating prediction performance

## Workflow
1. Load and preprocess the user-movie ratings dataset.
2. Prepare the data using the Scikit-Surprise library.
3. Train an SVD recommendation model.
4. Evaluate the model using 3-fold cross-validation.
5. Predict ratings for movies for a given user.
6. Rank movies by their predicted ratings and recommend the top-rated options.

## Technologies Used
- Python
- Pandas
- Scikit-Surprise
- Jupyter Notebook

## Model Evaluation
The model achieved an average cross-validation RMSE of approximately **1.046** on the selected dataset. A lower RMSE generally indicates better rating prediction performance.

## How to Run
1. Install the required libraries:
   ```bash
   pip install pandas scikit-surprise jupyter
   ```
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Ensure the required dataset files are available and update file paths if necessary.
4. Run the notebook cells in order.

