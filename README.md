# Medical Cost Prediction Using Machine Learning

## Project Overview

Medical expenses can vary from person to person depending on several factors, such as age, BMI, smoking habits and other personal characteristics.

This project focuses on predicting individual medical insurance costs using Machine Learning. It uses personal and health-related information to understand the factors that influence medical expenses and estimate insurance costs.

The project demonstrates the application of Data Science techniques to solve a real-world prediction problem.

## Project Objectives

- Analyze the factors that influence medical insurance costs.
- Perform data cleaning and exploratory data analysis (EDA).
- Understand relationships between different features and insurance charges.
- Apply Machine Learning techniques to predict medical expenses.
- Evaluate the performance of the prediction model.

## Dataset Information

The project uses the `Insurance.csv` dataset.

The dataset contains information about individuals, including:

| Feature  | Description                       |
| -------- | --------------------------------- |
| Age      | Age of the individual             |
| Sex      | Gender of the individual          |
| BMI      | Body Mass Index                   |
| Children | Number of dependent children      |
| Smoker   | Smoking status                    |
| Region   | Residential region                |
| Charges  | Individual medical insurance cost |

**Target Variable:** `charges`

## Technologies Used

- **Programming Language:** Python
- **Development Environment:** Google Colab / Jupyter Notebook
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn and Scikit-learn&#x20;
- **Machine Learning:** Regression-based prediction techniques

## Project Workflow

1. Data Collection – Loading the insurance dataset.
2. Data Understanding – Exploring the dataset and understanding its features.
3. Data Cleaning – Checking and handling missing or inconsistent values.
4. Exploratory Data Analysis – Identifying patterns and relationships through visualizations.
5. Data Preprocessing – Preparing the data for Machine Learning.
6. Model Training – Training the prediction model.
7. Model Evaluation – Checking the performance of the model.
8. Prediction – Estimating medical insurance costs using the trained model.

## Project Structure

```text
Medical-Cost-Prediction/
│
├── Medical_Cost_Prediction.ipynb
├── Insurance.csv
└── README.md
```

## How to Run the Project

**Step 1:** Clone or download this repository.

**Step 2:** Install Python and the required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

**Step 3:** Open `Medical_Cost_Prediction.ipynb` using Jupyter Notebook, VS Code or Google Colab.

**Step 4:** Make sure `Insurance.csv` is available in the same project directory.

**Step 5:** Run the notebook cells in sequence to perform the analysis, train the model and generate predictions.

## Key Learning Outcomes

- Understanding the complete Machine Learning workflow.
- Working with structured datasets using Python.
- Performing Exploratory Data Analysis.
- Understanding regression-based prediction.
- Interpreting data patterns and model results.

## Project Information

- **Project Name:** Medical Cost Prediction
- **Domain:** Data Science and Machine Learning
- **Project Type:** Academic Project
- **Author:** Swayam Gajare
