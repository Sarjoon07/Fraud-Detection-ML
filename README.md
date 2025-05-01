# Fraud-Detection-ML
# 💳 Financial Fraud Detection System

## 🔍 Project Overview
A machine learning model that detects fraudulent financial transactions with **99% recall**, representing a **16,167% improvement** over existing rule-based systems. Built using XGBoost and optimized for real-time fraud alerts.

## 🚀 Key Features
```python
# Core Components
1. Data Processing:
   - Cleaned 6.3M transactions
   - Handled missing merchant balances
   - Filtered extreme values (top 0.1%)

2. Feature Engineering:
   - isTransfer (customer-to-customer)
   - isLargeTransfer (>200k threshold)  
   - balance_change_orig (sender balance delta)
   - hour (transaction timestamp)

3. Model Architecture:
   - XGBoost classifier
   - SMOTE for class imbalance
   - Threshold tuning for optimal recall
