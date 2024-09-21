# Datathon 2024 - Evaluation Score Prediction Project

This project was developed as part of the Datathon 2024 competition hosted by the Entrepreneurship Foundation. The goal is to predict the Evaluation Score of candidates based on provided data, using machine learning models to achieve the best accuracy.

## Table of Contents
- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [EDA (Exploratory Data Analysis)](#eda-exploratory-data-analysis)
- [Results](#results)


## About the Project

This competition aims to predict the Evaluation Scores of candidates who have applied to the Entrepreneurship Foundation. The data underwent various cleaning and transformation processes, filling missing values, and converting features like birthdate into useful formats. The project’s final performance was measured using the RMSE (Root Mean Squared Error) metric.

## Dataset

The project involves two main datasets:
- **train.csv**: Training data containing candidates' personal information and their evaluation scores.
- **test_x.csv**: Test data containing only personal information; scores need to be predicted.

## EDA (Exploratory Data Analysis)

Key steps taken during data analysis:
- **Missing Data Handling**: Missing values were filled using techniques like KNN and Simple Imputer.
- **Data Cleaning**: Text fields were processed and converted into numeric formats.


## Results

The model with the lowest RMSE was selected as the final model. Detailed performance metrics are provided in the results section of the project.


## Contact

For any inquiries about this project, feel free to reach out to [Metehan Ayhan](mailto:metehanayhan1213@gmail.com).
