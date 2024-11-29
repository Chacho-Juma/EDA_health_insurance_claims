# Exploratory Data Analysis and Insights on Insurance Data

## Project Overview

This repository contains an exploratory data analysis (EDA) project focused on a dataset of insurance claims. 
The goal is to understand the data, identify trends, and prepare it for advanced modeling or business insights.

### Files in the Repository

1. **Exploratory_Data_Analysis_(EDA).ipynb**  
   A Jupyter notebook performing exploratory data analysis, including data cleaning, visualization, and preliminary observations.

2. **insurance_data.csv**  
  The dataset can be accessed from [Kaggle](https://www.kaggle.com/datasets/thedevastator/insurance-claim-analysis-demographic-and-health/), including features such as age, gender, BMI, blood pressure, smoking status, and claim amounts.

### Dataset Description

| Column Name     | Description                              | Data Type |
|------------------|------------------------------------------|-----------|
| `index`         | Index of the record                      | int       |
| `PatientID`     | Unique ID for each patient               | int       |
| `age`           | Age of the patient                       | float     |
| `gender`        | Gender of the patient                    | object    |
| `bmi`           | Body Mass Index                         | float     |
| `bloodpressure` | Blood pressure level                     | int       |
| `diabetic`      | Diabetic status (Yes/No)                 | object    |
| `children`      | Number of dependent children             | int       |
| `smoker`        | Smoking status (Yes/No)                  | object    |
| `region`        | Region where the patient resides         | object    |
| `claim`         | Insurance claim amount                   | float     |

### Project Objectives

- **Understand** the distribution and relationships between variables.
- **Identify** any missing values and handle them appropriately.
- **Visualize** data to uncover trends and anomalies.
- **Prepare** the data for predictive modeling and insights.

## Next Steps After EDA

Based on the dataset and EDA results, the next step involves figuring out how these features impact the Claim value.

## Contributing
Contributions are welcome! 

