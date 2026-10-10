# Credit Default Risk & Early Warning System

## Overview
A machine learning and financial analytics project that estimates credit-card default risk, segments borrowers into risk bands, and investigates repayment-related warning signals.

## Business Problem
Identify borrowers whose repayment behaviour indicates rising default risk, and explain which warning signals deserve attention.

## Dataset
**UCI Default of Credit Card Clients**

Source: https://archive.ics.uci.edu/dataset/350/default+credit+card+clients

## Tools
Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn

## Methodology
- Exploratory data analysis
- Repayment-delay and credit-utilization analysis
- Comparison of Logistic Regression, Decision Tree, Random Forest and Gradient Boosting
- Evaluation using precision, recall, F1-score, ROC-AUC, PR-AUC and Brier score
- Threshold evaluation and borrower risk segmentation
- Permutation feature importance

## Key Findings
- Repeated repayment delays were associated with higher observed default rates.
- Recent repayment status was an important warning signal.
- Credit utilization provided additional, less consistent information.
- Risk bands summarized differences in observed default rates across predicted-risk groups.

## Limitations
- The dataset is historical and may not represent current borrowers.
- Observed associations do not establish causality.
- Model probabilities and risk thresholds require further validation.
- The project is an educational prototype, not a production lending system.

## How to Run
1. Download the notebook.
2. Open https://colab.research.google.com/
3. Select **File → Upload notebook** and upload the `.ipynb` file.
4. Install any required packages and run the notebook cells in order.

## Disclaimer
For educational and portfolio demonstration purposes only. Not intended for actual lending decisions.
