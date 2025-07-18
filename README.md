# Bitcoin Closing Value Prediction with Online Learning

A machine learning project that predicts Bitcoin closing prices using online learning algorithms and real-time data streaming.

## 📊 Dataset

This project uses the [Bitcoin Historical Data](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data) from Kaggle. Places its .csv next to the notebook.

**Features (4 financial indicators):**
- `Open` - Opening price of Bitcoin
- `High` - Highest price during the time period
- `Low` - Lowest price during the time period
- `Volume` - Trading volume

**Target:** Bitcoin closing price (USD)

## Model Architecture

- **Algorithm:** Online Linear Regression
- **Preprocessing:** StandardScaler for feature normalization
- **Learning Type:** Incremental learning (one sample at a time)
- **Drift Detection:** ADWIN (Adaptive Windowing) for concept drift detection

## Technologies Used

- **Python 3.x**
- **River** - Online machine learning framework
- **Pandas** - Data manipulation
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Scikit-learn** - Metrics and preprocessing