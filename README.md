# Job Salary Prediction

## Overview

Predicting job salaries using machine learning provides valuable insights into compensation trends. This project uses a dataset of over 3,000 recent job postings to train a model that estimates salaries based on key job features such as title, skills, experience, location, and industry. The trained model aims to bring transparency and objectivity to salary discussions and negotiations.

## Features

- **Dataset**: Over 3,000 job postings, including job title, location, skills, industry, and experience.
  
- **Algorithms Used**:
  - **Linear Regression**: Explained 75% of salary variance but limited by strong linear assumptions.
  - **Random Forest**: Achieved 90% cross-validation score by capturing non-linear relationships and feature interactions.

- **Insights**:
  - Location and industry significantly influence salaries.
  - Specific skills like Python, React, and Kubernetes are associated with higher pay.
  - Experience leads to consistent salary growth over the first 10 years.

## Project Motivation

The aim of this project is to leverage predictive modeling techniques to provide accurate, data-driven salary estimates that support career planning and salary negotiations.

## Results

- **Model Performance**:
  - Random Forest performed significantly better than Linear Regression, with a cross-validation score of 0.90.
  
- **Predicted Salaries**:
  - Key Account Manager: $65,700
  - Business Development Manager: $72,400
  - Java Developer: $45,800

- **Key Insights**:
  - Developers in San Francisco earned 67% more than those in Philadelphia.
  - Finance industry roles paid 23% more than healthcare.

## Dataset

The dataset used in this project can be found on Kaggle: [Predicting Job Titles from Resumes](https://www.kaggle.com/datasets/thedevastator/predicting-job-titles-from-resumes)

## Technologies Used

- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/job-salary-prediction.git
2.Install the required libraries:

bash
Copy code
   pip install -r requirements.txt
3.Run the Jupyter notebooks or Python scripts to explore the data, train models, and visualize results.

## Future Work
Incorporate more recent data for improved predictions.
Explore advanced deep learning models for better performance.
Include additional features like education level and certifications.

## Acknowledgments
This project was inspired by the Kaggle dataset: Predicting Job Titles from Resumes.

## Author
Michael Thuo Mwithiga
