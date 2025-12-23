# Cost-Sensitive Fraud Detection Using Expected Loss

This project implements a fraud detection system that aligns machine learning predictions with real-world business objectives using cost-sensitive decision making.

## Overview
Traditional fraud detection models rely heavily on accuracy, which is insufficient for highly imbalanced data.
This project converts calibrated fraud probabilities into expected monetary loss, enabling risk-based prioritization of transactions.

## Key Features
- Logistic Regression with probability calibration
- Expected loss–based risk scoring
- Lift and cumulative gains analysis
- Cost–benefit evaluation under limited review capacity
- Comparison against random transaction review

## Results
- Fraud risk is highly concentrated in a small fraction of transactions
- Reviewing only the top 1% highest-risk transactions captures most fraud cases
- Expected-loss-based strategy significantly outperforms random review
- The system delivers strong net financial benefit under realistic assumptions

## Files
- `Fraud_Detection_Expected_Loss.ipynb` – complete analysis and results

## Tech Stack
- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib

## Conclusion
This project demonstrates that probability calibration and expected-loss-based prioritization can substantially improve both the effectiveness and economic viability of fraud detection systems.
