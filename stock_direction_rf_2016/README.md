# Predicting the Direction of Stock Market Prices using Random Forest (2016)

**Paper**: Khaidem, Luckyson, Snehanshu Saha, and Sudeepa Roy Dey.  
*"Predicting the direction of stock market prices using random forest."*  
arXiv:1605.00003 (2016) → [https://arxiv.org/abs/1605.00003](https://arxiv.org/abs/1605.00003)

**Original Reproduction**: José Martínez Heras  
**Adapted & verified by**: S33mi (during PhD studies)

## Goal
Reproduce the high accuracy (~92% on AAPL) reported in the paper and investigate whether the results suffer from **data leakage** caused by shuffling a time-series dataset.

## Key Finding
- Proper chronological train/test split → ~58% accuracy
- Shuffled (leaked) train/test split → ~87% accuracy (close to the paper’s 92%)

This strongly suggests the original paper’s results were inflated by data leakage.

## How to run
```bash
pip install yfinance pandas scikit-learn matplotlib
jupyter notebook stock_direction_rf_2016.ipynb
