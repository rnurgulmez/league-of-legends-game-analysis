# League of Legends High Diamond Ranked Game Analysis

This Python project analyzes high diamond ranked games from the game "League of Legends". The dataset used in this analysis is `high_diamond_ranked_10min.csv`.

## Overview

The project involves data preprocessing, exploratory data analysis, and building a machine learning model to predict the outcome of the games based on various features.

## Dataset

- The dataset contains various features related to each game such as wards placed, kills, deaths, gold earned, experience gained, etc.
- The target variable is `blueWins`, indicating whether the blue team won the game (1) or not (0).

## Exploratory Data Analysis (EDA)

- EDA includes visualization and analysis of various features like gold advantage, first blood, dragons, heralds, elite monsters, minion kills, jungle minion kills, etc.
- Heatmap is used to visualize the correlation between features.

## Machine Learning Model

- A neural network model is built using TensorFlow and Keras to predict game outcomes.
- The model architecture consists of multiple dense layers with ReLU activation.
- The model is trained using the Adam optimizer and sparse categorical crossentropy loss function.
- Evaluation metrics such as confusion matrix and classification report are used to assess the model's performance.

## Outlier Detection

- Outliers in selected columns are detected using z-score and box plot visualization.

## Conclusion

- The analysis provides insights into various factors affecting game outcomes in high diamond ranked games of League of Legends.

## Usage

- Clone the repository and run the Jupyter Notebook file to explore the analysis.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Seaborn
- Matplotlib
- TensorFlow
- Scikit-learn

