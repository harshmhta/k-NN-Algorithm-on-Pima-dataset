# k-NN Algorithm on Pima Indians Diabetes dataset 

This project focuses on experimenting with the k-NN algorithm on the Pima Indians Diabetes dataset from the UCI repository to find the optimal value for the number of neighbors k. The dataset has 768 rows of data (potential diabetes patients) and 9 columns (8 input features including Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, and 1 target output).

## Getting Started

To get started with this project, please follow the instructions below:

## Prerequisites

Anaconda with Python 3.7

## Installation

Clone this repository to your local machine

Open Anaconda and launch Jupyter Notebook

Open the Problem4.ipynb file

Run the code cells in the notebook

## Project Tasks

This project has the following tasks:

1. Load the Pima.csv data file using pandas and report the statistics of each feature (min, max, average, standard deviation) and the histogram of the labels (target outputs).

2. Split the data into training and test sets with 80% training and 20% test data sizes.

3. Use 5-fold cross-validation on training data to decide the best number of neighbours k. For k = 1, 2, 3, . . . , 15 compute the 5-fold cross validation error and plot the results (with values of k on the x-axis and accuracy on the y-axis).

4. Evaluate the k-NN algorithm on test data with the optimal number of neighbours obtained in the previous step and report the test error.

5. Process the input data by subtracting the mean and dividing by the standard deviation over each dimension (feature), repeat the previous step, and report the accuracy. Do centralization and standardization affect the accuracy? Why?

## Running the Project

You can run this project by opening the Problem4.ipynb file in Jupyter Notebook and running each code cell in order. The results and discussion for each task will be displayed in the notebook.

## Results

The results of this project are included in the Problem4.ipynb file. The results include the statistics of each feature, the histogram of the labels, the best number of neighbors k, the accuracy of the k-NN algorithm on test data, and the effect of centralization and standardization on the accuracy.

## Conclusion

In conclusion, this project provided an introduction to the k-NN algorithm and how to use it on a dataset to find the optimal number of neighbors. It also showed the effect of centralization and standardization on the accuracy of the algorithm. By following the instructions in the notebook, you can replicate the results of this project and experiment with different values of k to find the best number of neighbors for your own dataset.

## Academic Integrity Statement

Please note that all work included in this project is the original work of the author, and any external sources or references have been properly cited and credited. It is strictly prohibited to copy, reproduce, or use any part of this work without permission from the author.

If you choose to use any part of this work as a reference or resource, you are responsible for ensuring that you do not plagiarize or violate any academic integrity policies or guidelines. The author of this work cannot be held liable for any legal or academic consequences resulting from the misuse or misappropriation of this work.

In summary, any unauthorized copying or use of this work may result in serious consequences, including but not limited to academic penalties, legal action, and damage to personal and professional reputation. Therefore, please use this work only as a reference and always ensure that you properly cite and attribute any sources or references used.
