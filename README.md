# Earthquake-Magnitude-Forecasting-and-Spatial-Analysis
  - This project aims to predict earthquake magnitudes using a Random Forest Regressor model and visualize potential earthquake-prone areas using heatmaps and geographical representations.

## Features
  - Preprocesses earthquake data by encoding categorical variables and handling missing values
  - Applies Principal Component Analysis (PCA) for dimensionality reduction
  - Trains a Random Forest Regressor model to predict earthquake magnitudes
  - Evaluates the model's performance using RMSE and R-squared score
  - Visualizes feature importance for the model
  - Generates a heatmap to identify potential earthquake-prone areas
  - Creates a geographical representation using Cartopy to provide a spatial context

## Requirements
  - Python 3.7 or higher
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - joblib
  - cartopy

## The script will generate the following outputs:
  - earthquake_prone_areas_heatmap.png: A heatmap of potential earthquake-prone areas
  - earthquake_prone_areas_map_geographical_representation.png: A geographical representation of potential earthquake-prone areas
  - explained_variance.png: A plot showing the explained variance ratio of principal components
  - principal_components.png: A scatter plot of the first two principal components
  - feature_importance.png: A bar plot showing the feature importance for earthquake magnitude prediction
  - predicted_vs_actual.png: A scatter plot comparing predicted and actual earthquake magnitudes
  - The trained model will be saved as earthquake_magnitude_model.joblib for future use.
