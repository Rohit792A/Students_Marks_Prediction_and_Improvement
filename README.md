# Students Marks Prediction and ImprovementMarks:
This project focuses on predicting students' academic performance (pass or fail) based on their attributes, such as attendance, class test scores, and total assignments. It uses the K-Nearest Neighbors (KNN) classification algorithm and incorporates Random Over-Sampling (ROS) to handle imbalanced datasets.

● Introduction

● Usage

● Results

## Introduction
The goal of this project is to predict whether a student will pass or fail based on certain academic attributes. It utilizes the KNN classification algorithm, which is a simple and effective method for making predictions based on similarities between data points. To improve the model's performance, we employ Random Over-Sampling (ROS) to handle imbalanced datasets where the number of passing students may be significantly different from the number of failing students.

## Usage
1. Place your datasets in Excel format (.xlsx) in the 'data' directory.

2. Update the list_of_data_path variable in the students_marks_prediction.py file with the file paths of your datasets.

## Results
The classification results will be displayed for each dataset in the format of a confusion matrix and a classification report. The classification report includes metrics such as precision, recall, F1-score, and accuracy, providing insights into the performance of the model on each dataset.
