# Voting Regressor Model - Predicting Salary Based on Age and Experience

This project demonstrates the use of the **Voting Regressor** algorithm to predict salary based on age and experience. The model combines multiple regression techniques (Linear Regression, Decision Tree Regressor, and Support Vector Regressor) to create a robust prediction model.

## Dataset

The dataset used in this project contains 300 samples with the following features:
- `Age`: The age of the individual.
- `Experience`: The years of experience.
- `Salary`: The corresponding salary of the individual.

### Dataset Structure
| Age | Experience | Salary   |
|-----|------------|----------|
| 29  | 9          | 57000    |
| 45  | 25         | 108000   |
| ... | ...        | ...      |

The dataset is saved in the file `age_experience_salary_data.csv`.

## Project Structure

- **Dataset**: A CSV file containing the age, experience, and salary data.
- **Modeling**: We use `Linear Regression`, `Decision Tree Regressor`, `Support Vector Regressor (SVR)`, and finally combine them in a `Voting Regressor`.
- **Visualization**: Scatter plots are used to visualize relationships between the variables.

## Screenshots

![Screenshot (144)](https://github.com/user-attachments/assets/a1f20841-7294-44c4-b286-810183ada5d3)


## Steps to Run the Project

### 1. Install Dependencies
Ensure you have the required libraries installed:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
