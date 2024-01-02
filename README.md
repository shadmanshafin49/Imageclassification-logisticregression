# Image Classification with Logistic Regression

This project demonstrates a simple image classification task using the MNIST dataset and a Logistic Regression model. The goal is to classify handwritten digits as either the digit '2' or not ('non-2').

## Overview

- **Dataset:** The project uses the MNIST dataset, consisting of 28x28 grayscale images of handwritten digits (0 through 9).
- **Model:** Logistic Regression is employed as a binary classifier to distinguish between the digit '2' and other digits.
- **Framework:** TensorFlow is used for data manipulation and logistic regression modeling.

## Contents

- `image_classification.ipynb`: Jupyter Notebook containing the code and steps of the image classification project.
- `README.md`: This file, providing an overview and instructions for the project.

## How to Run

1. **Dependencies:**
   - Ensure you have the necessary dependencies installed by running the following commands:
     ```bash
     pip install numpy tensorflow matplotlib pandas scikit-learn
     ```

2. **Run the Notebook:**
   - Open and run the `image_classification.ipynb` notebook in a Jupyter environment.

3. **Explore the Code:**
   - Understand the steps involved in loading the MNIST dataset, preprocessing the data, building a Logistic Regression model, and evaluating its performance.

## Project Structure

- **Loading Data:**
   - The MNIST dataset is loaded using the `fetch_openml` function from scikit-learn.

- **Data Preprocessing:**
   - Data is split into training and testing sets.
   - A random permutation is applied to the training set.

- **Model Building:**
   - A Logistic Regression model is created and trained to classify digits as '2' or 'non-2'.

- **Model Evaluation:**
   - The model is evaluated using cross-validation, and accuracy scores are calculated.

## Visualization

- **Display Image:**
   - The notebook includes code to display a sample image from the dataset.

## Conclusion

This project serves as a simple introduction to image classification using a Logistic Regression model. Feel free to explore and modify the code for further experimentation.

**Note:** Make sure to run the notebook in a TensorFlow-compatible environment, such as Google Colab.
