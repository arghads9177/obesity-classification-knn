# Obesity Classification Data Science Project

## Overview

This project focuses on the classification of individuals based on their obesity status. The dataset used for this project contains information collected from various sources, including medical records, surveys, and self-reported data. The goal is to analyze and classify individuals into different obesity categories using the provided data.

## Dataset

The dataset includes the following columns:

- **ID**: A unique identifier for each individual
- **Age**: The age of the individual
- **Gender**: The gender of the individual
- **Height**: The height of the individual in centimeters
- **Weight**: The weight of the individual in kilograms
- **BMI**: The body mass index of the individual, calculated as weight divided by height squared
- **Label**: The obesity classification of the individual, which can be one of the following:
  - Normal Weight
  - Overweight
  - Obese
  - Underweight

## Objective

The goal of this project is to:

1. Understand and visualize the dataset.
2. Train a classification model to accurately predict the class of obesity based on the four features.
3. Evaluate the performance of different classification models using metrics such as accuracy, precision, recall, and F1-score.

## Steps Involved

1. **Data Exploration**:
   - Visualize the data to understand the distribution of features for each species.
   - Analyze the relationships between different features using scatter plots, pair plots, and correlation matrices.
   
2. **Data Preprocessing**:
   - Handle any missing values (though none are present in this dataset).
   - Split the data into training and testing sets for model evaluation.
   
3. **Model Training**:
   - Build and train classification the model using algorithms such as:
     - K Nearest Neighbors
   
4. **Model Evaluation**:
   - Evaluate the models using appropriate classification metrics:
     - **Accuracy**: Percentage of correctly classified instances.
     - **Precision**: The proportion of predicted positives that are actually positive.
     - **Recall**: The proportion of actual positives that are correctly predicted.
     - **F1-Score**: The harmonic mean of precision and recall.
     - **Confusion Matrix**: To visualize the true positives, false positives, true negatives, and false negatives.

## Model Performance Metrics

- **Accuracy**: Measures how often the classifier makes the correct predictions.
- **Precision and Recall**: Evaluate the performance when dealing with imbalanced classes (though this dataset is balanced).
- **F1-Score**: Useful when balancing precision and recall.
- **Confusion Matrix**: To visualize how well the model performed in each class.

## Visualizations

Here are some suggested visualizations to explore the Iris dataset:

1. **Scatter Plots**: Compare the distribution of features like Sepal Length, Sepal Width, Petal Length, and Petal Width across different species.
2. **Pair Plots**: Show pairwise relationships between features.
3. **Heatmaps**: Show the correlation between features.
4. **Box Plots**: Display the distribution of features for each species.
   
## Project Structure

The project is organized as follows:

- `data/`: Contains the dataset used for the analysis
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and model development
- `models/`: Saved models and model evaluation results
- `README.md`: Project overview and documentation

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/obesity-classification-knn.git


## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any questions or suggestions, feel free to contact me at [email2argha@gmail.com].
