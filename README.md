# Prioritizing CRM Leads with PCA: Eigenvectors and SVD

## Project Overview

This project explores how Principal Component Analysis (PCA) can be used to analyze CRM data, reduce dimensionality, and identify patterns in customer information to support lead prioritization.

The project applies and compares two mathematical approaches to PCA:
- **Eigenvalue Decomposition (EVD)** — using eigenvalues and eigenvectors of the covariance matrix.
- **Singular Value Decomposition (SVD)** — using singular value decomposition of the standardized data matrix.

The goal is to understand how both approaches work mathematically and evaluate their results on the same CRM dataset.

## Project Objectives

- Prepare and clean real-world CRM data.
- Perform data preprocessing and feature standardization.
- Implement PCA using Eigenvalue Decomposition.
- Implement PCA using Singular Value Decomposition.
- Compare the results of both approaches.
- Explore patterns in customer data to support lead prioritization.

## Dataset

The project uses a real-world CRM dataset provided by a company, originally containing approximately 2,000 records and 30 numerical features.

The dataset required preprocessing and standardization before applying dimensionality reduction techniques.

**Data Privacy Notice:** The original dataset contains confidential company/customer information and is therefore not included in this public repository.

## Methodology

### 1. Data Preprocessing
- Data cleaning and preparation.
- Handling missing and inconsistent values.
- Feature selection and standardization.

### 2. PCA Using Eigenvalue Decomposition
- Calculate the covariance matrix.
- Compute eigenvalues and eigenvectors.
- Sort principal components by explained variance.
- Project the data into a lower-dimensional space.

### 3. PCA Using SVD
- Apply Singular Value Decomposition to the standardized data matrix.
- Extract principal components from the right singular vectors.
- Calculate explained variance.
- Project the data into a lower-dimensional space.

### 4. Comparison
Compare the two implementations to understand their mathematical foundations and evaluate the consistency of their results.

## Technologies & Tools

- Python
- NumPy
- pandas
- SciPy
- Jupyter Notebook
- Linear Algebra
- Principal Component Analysis (PCA)
- Singular Value Decomposition (SVD)

## Repository Structure

```text
Prioritizing-CRM-Leads-with-PCA-Eigenvectors-and-SVD/
│
├── AI_Project_CRM.ipynb
├── README.md
│
├── data/
│   └── README.md
│
└── results/
    └── (visualizations and analysis results)
```

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/asanovamoldir-09/Prioritizing-CRM-Leads-with-PCA-Eigenvectors-and-SVD.git
   ```

2. Install the required libraries:

   ```bash
   pip install numpy pandas scipy jupyter
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook AI_Project_CRM.ipynb
   ```

4. Run the notebook cells sequentially.

**Note:** The original company dataset is not publicly available. Running the complete analysis may require access to the original dataset.

## Project Context

Academic project developed at Northeastern University as part of the Master of Science in Artificial Intelligence program.
