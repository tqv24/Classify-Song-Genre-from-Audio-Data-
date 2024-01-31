# Music Genre Classification Project

## Overview

This project focuses on classifying music tracks into two genres: Hip-Hop and Rock. The classification is performed using machine learning techniques, including data preprocessing, feature scaling, principal component analysis (PCA), and training models such as Decision Trees and Logistic Regression.

## Dataset

The dataset used in this project is sourced from The Echo Nest, a research group that provides track metadata and musical features. The data includes information about tracks, such as title, artist, and genre labels, alongside metrics like danceability, energy, and instrumentalness.

## Project Structure

The project is structured as follows:

- **1. Preparing our dataset**: Loading track metadata and metrics, merging datasets, and inspecting the resulting dataframe.

- **2. Pairwise relationships between continuous variables**: Analyzing correlations between different features to identify potential redundancies.

- **3. Splitting our data**: Splitting the data into features and labels, and further dividing it into training and testing sets.

- **4. Normalizing the feature data**: Scaling features to ensure a consistent scale using StandardScaler.

- **5. Principal Component Analysis on our scaled data**: Reducing the dimensionality of the dataset using PCA.

- **6. Further visualization of PCA**: Analyzing explained variance to determine the number of components to use.

- **7. Projecting on to our features**: Performing PCA and projecting data onto components.

- **8. Train a decision tree to classify genre**: Using a Decision Tree classifier to classify music genres.

- **9. Compare our decision tree to a logistic regression**: Evaluating model performance using both Decision Trees and Logistic Regression.

- **10. Balance our data for greater performance**: Addressing imbalances in the dataset by balancing the number of data points for each genre.

- **11. Does balancing our dataset improve model bias?**: Evaluating model performance after balancing the dataset.

- **12. Using cross-validation to evaluate our models**: Applying K-fold cross-validation to assess model performance across different data splits.

## Model Performance

- **Decision Tree**: Precision, recall, and F1-score for both Hip-Hop and Rock genres.

- **Logistic Regression**: Precision, recall, and F1-score for both Hip-Hop and Rock genres.

