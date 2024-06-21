# Loan_status_prediction
This model predicts the loan status of applier using Support vector machin model(SVM)

# Loan Status Prediction Using Support Vector Machines

## Overview
This repository contains a project aimed at predicting the loan status using Support Vector Machines (SVM). The dataset used for this project is sourced from Kaggle. The goal is to build a machine learning model that can accurately predict whether a loan will be approved or rejected based on various features.

## Dataset
The dataset used for this project is from Kaggle and contains various features related to the applicants' information. These features include:
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status (Target variable)

You can download the dataset from [Kaggle](https://www.kaggle.com/).

## Installation
To run the code in this repository, you'll need to have Python installed along with several Python packages. The easiest way to install the required packages is to use `pip` and a virtual environment.

### Step-by-Step Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/loan-status-prediction.git
    cd loan-status-prediction
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```




## Usage
Once the environment is set up, you can run the Jupyter notebook to explore the data, preprocess it, and build the SVM model.

### Running the Jupyter Notebook
1. **Start Jupyter Notebook**:
    ```bash
    jupyter notebook
    ```
2. **Open `loan_status_prediction.ipynb`**: Navigate to the `loan_status_prediction.ipynb` file in the Jupyter Notebook interface and run the cells to see the analysis and model training steps.

## Project Structure
The repository is structured as follows:


## Key Steps in the Notebook
1. **Data Loading**: Load the dataset and perform initial exploration.
2. **Data Preprocessing**: Handle missing values, encode categorical variables, and scale numerical features.
3. **Model Training**: Split the data into training and testing sets, train an SVM model, and evaluate its performance.
4. **Evaluation**: Assess the model's accuracy, precision, recall, and F1-score.

## Results
The SVM model achieved the following results:
- **Training Accuracy**: 79.6%
- **Testing Accuracy**: 83.33%

These scores indicate that the model performs well on the training data and generalizes effectively to unseen test data.



## Acknowledgements
- Kaggle for providing the dataset.
- The open-source community for their invaluable tools and resources.

---


