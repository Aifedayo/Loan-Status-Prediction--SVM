# Loan Status Prediction System: Support Vector Machine (SVM)

## Overview
This project builds a loan status prediction system using a Support Vector Machine (SVM) model to classify loan applications as **approved** or **rejected**. By analyzing applicant information and financial data, the model provides insights for financial institutions to make data-driven loan approval decisions.

## Dataset
- **Source**: Contains features such as applicant income, loan amount, credit history, and other demographics.
- **Target**: Binary classification indicating **approved** or **rejected** loan status.

## Project Structure
- **Data Preprocessing**: Includes handling missing values, encoding categorical features, and scaling numerical features.
- **Model Training**: An SVM model is trained on preprocessed data to optimize classification accuracy.
- **Evaluation**: Model performance is evaluated with accuracy, precision, recall, and F1 score metrics.

## Requirements
- Python libraries: `pandas`, `scikit-learn`, `numpy`, `matplotlib`

Install dependencies with:
```bash
pip install -r requirements.txt
```

## How to Run
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Aifedayo/Loan-Status-Prediction--SVM.git
   ```
2. **Run the Notebook**:
   Open and run the Jupyter notebook to see data preprocessing, model training, and evaluation steps.

## Results
- The model achieves an accuracy of 79% on the test data, providing reliable predictions for loan status.
