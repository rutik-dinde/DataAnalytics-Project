# Rutik Ganesh Dinde - Data Analytics Project

## Project Title
**Insurance Claims Data Analytics & Fraud Detection**

## Project Description
This project analyzes insurance claim data using Python. It performs data cleaning, exploratory data analysis, visualization, business-metric calculation, correlation analysis, and baseline machine learning for fraud-investigation flag prediction.

## Student
**Rutik Ganesh Dinde**

## Technologies Used
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- CSV/Excel

## Dataset
The notebook expects a CSV file named `insurance_claims.csv`.

**Dataset link:** Add the exact public dataset URL supplied by your college/course before final submission. The link should point to the exact dataset used in the notebook.

Typical fields include:
- `AGE`
- `GENDER`
- `POLICY_TYPE`
- `CLAIM_AMOUNT`
- `CLAIM_HISTORY`
- `EXCESSIVE_CLAIM_AMOUNT`
- `FLAG_FOR_FRAUD_INV`

## Workflow
1. Import libraries
2. Load the dataset
3. Inspect shape, types, missing values and statistics
4. Clean duplicate records and standardize column names
5. Calculate key business metrics
6. Perform exploratory data analysis
7. Create visualizations and a correlation heatmap
8. Prepare data for machine learning
9. Train a Random Forest classifier
10. Evaluate the model
11. Summarize findings

## Setup / Run Instructions

### Install dependencies
```bash
pip install -r requirements.txt
```

### Add dataset
Put `insurance_claims.csv` in the same folder as the notebook.

### Start Jupyter
```bash
jupyter notebook
```

Open `Rutik_Ganesh_Dinde_DataAnalytics.ipynb` and run all cells from top to bottom.

## Expected Output
- Dataset summary
- Missing-value report
- Descriptive statistics
- Claim amount distribution
- Policy-type analysis
- Fraud-investigation rate analysis
- Correlation heatmap
- Random Forest classification results
- Confusion matrix and classification report

## Project Files
- `Rutik_Ganesh_Dinde_DataAnalytics.ipynb` - complete project code
- `requirements.txt` - required Python libraries
- `Rutik_Ganesh_Dinde_ProjectReport.docx` - project documentation
- `README.md` - project overview and setup instructions

## Important Note
The fraud-investigation flag is a classification target. A model prediction is not proof of fraud. Real-world decisions require appropriate investigation and human review.
