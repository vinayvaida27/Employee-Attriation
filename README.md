# Predicting Employee Attrition with Machine Learning and Analytics

## Overview

The **Employee-Attrition** project aims to predict employee turnover using machine learning models. By identifying key factors influencing attrition, it helps businesses proactively manage employee retention. Models evaluated include Logistic Regression and Random Forest, with and without SMOTE for handling class imbalance.


## Problem Statement

Employee attrition is a critical issue for organizations, and understanding the reasons behind it can help businesses improve retention strategies. This project applies machine learning models to predict employee attrition, helping organizations identify at-risk employees and take proactive measures.

## Dataset

The dataset used in this project includes various employee attributes such as age, gender, department, salary, job satisfaction, work environment, and more. It serves as the foundation for building and evaluating predictive models.

## Features

- **Age**: Age of the employee.
- **Department**: The department to which the employee belongs.
- **Job Satisfaction**: Employee's job satisfaction level.
- **Salary**: The salary of the employee.
- **Work Environment**: The quality of the work environment.

## Technologies Used

- R
- dplyr
- ggplot2
- randomForest
- SMOTE
- caret

## Before smote and After smote Data distribution
![image](https://github.com/user-attachments/assets/6d9bfeb3-bb82-4d2f-bd72-c0f078a32b7e)
![image](https://github.com/user-attachments/assets/fb12f6da-90b1-45e7-8cb9-b286d6fc67e5)


## Model Comparison & Performance
- Logistic Regression (No SMOTE): Accuracy = 84.98%, AUC = 0.83
- Random Forest (No SMOTE): Accuracy = 85.67%, AUC = 0.84
- Logistic Regression (SMOTE): Accuracy = 76.39%, AUC = 0.82
- Random Forest (SMOTE): Accuracy = 89.25%, AUC = 0.87 (Best Performance)

- The best performing model for predicting employee attrition was **Random Forest (With SMOTE)**, achieving an accuracy of 89.25% and an AUC of 0.87. This model effectively handles class imbalance and provides excellent recall and precision for both "stay" and "leave" classes, making it the best candidate for real-world deployment.

## Results
- The Random Forest (With SMOTE) model was the most effective in predicting employee attrition, with a high accuracy and strong performance across both "stay" and "leave" classes.
- Confusion Matrix of Random Forest with SMOTE
![image](https://github.com/user-attachments/assets/32dc87c4-2b88-4b6f-be57-00c73a168c33)
- The project demonstrates the ability to predict employee attrition with high accuracy, offering valuable insights for HR departments to take preemptive actions.

## Presentation
- ![image](https://github.com/user-attachments/assets/ac4f4e42-d291-4964-b550-26bcde47f1a5)

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/vinayvaida27/BreadcrumbsPredicting-Employee-Attrition-with-Machine-Learning-and-Analytics.Rmd.git
    ```

2. Install the necessary dependencies:
    ```r
    install.packages(c("dplyr", "ggplot2", "randomForest", "caret", "SMOTE"))
    ```

## Usage

To run the project in RStudio, open the `Employee attriration 01052024.Rmd` script and run the code:
```bash
source("Employee attriration 01052024.Rmd")
```

## Contributing
Feel free to fork this repository, submit pull requests, or open issues for improvements.
