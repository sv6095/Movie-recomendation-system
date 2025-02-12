# Movie-recomendation-system
Movie Recommendation System

Overview

This project implements a movie recommendation system using various collaborative filtering techniques, including Singular Value Decomposition (SVD), SVD++, and K-Nearest Neighbors (KNN). A hybrid recommendation approach combines these models to improve accuracy. The system uses the MovieLens 20M dataset.

Features

Data Preprocessing: Handles sparsity by filling missing ratings with user mean ratings.

Model Training: Implements SVD, SVD++, and KNN-based collaborative filtering (user-based and item-based).

Hyperparameter Tuning: Optimizes SVD using GridSearchCV.

Hybrid Recommendation System: Combines multiple models to generate better recommendations.

Evaluation Metrics: Computes precision, recall, and F1 score.

Dataset

The project uses the MovieLens 20M dataset. It contains user ratings and movie metadata.

Installation

Prerequisites

Ensure you have Python installed along with the necessary dependencies.

Usage

1. Load the Dataset

The dataset is downloaded using KaggleHub and loaded into Pandas DataFrames.

2. Data Preprocessing

Missing ratings are filled with user mean ratings.

3. Train-Test Split

A 75%-25% train-test split is applied.

4. Model Training and Hyperparameter Tuning

SVD hyperparameters are tuned using GridSearchCV.

5. Collaborative Filtering Approaches

SVD++, user-based, and item-based KNN models are trained.

6. Generating Recommendations

A hybrid approach combines multiple models.

7. Evaluation

The model is evaluated using precision, recall, and F1 score.
