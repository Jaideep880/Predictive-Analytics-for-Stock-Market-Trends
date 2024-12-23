# Predictive Analytics for Stock Market Trends

## Description
This repository provides code and implementation for predicting stock market trends using Predictive Analytics techniques. By combining Natural Language Processing (NLP) and Time-Series Analysis, this project leverages various machine learning models to forecast market movements.

Models implemented in this project:
- **Stacked LSTM**
- **Logistic Regression**
- **Random Forest**
- **Naïve Bayes**
- **Linear Support Vector Machine (SVM)**
- **Non-Linear Support Vector Machine (SVM)**

## Methodology

### NLP with Historical News Data
We use NLP techniques to analyze historical news data for sentiment and its impact on stock trends. The following algorithms are implemented for sentiment analysis:
- Logistic Regression
- Random Forest
- Naïve Bayes
- Linear Support Vector Machines
- Non-Linear Support Vector Machines

### Time-Series Analysis with Stock Data
For time-series analysis, we implement the **Stacked LSTM** model to predict future trends based on historical stock data, focusing on sequential dependencies.

## Requirements
To run this project, ensure the following are installed:

### Software
- **Python** (Anaconda recommended)

### Libraries
Install the necessary libraries using pip or conda:
- `TensorFlow` (v2)
- `Keras`
- `pandas`
- `NumPy`
- `Scikit-learn`
- `DateTime`
- `Matplotlib`
- `Seaborn`

### API Accounts
- **Tiingo API**: Register at [Tiingo](https://www.tiingo.com) to obtain an API key for stock data.
- **The Guardian API**: Register at [The Guardian API](https://open-platform.theguardian.com) for news data.

## Data Sources
- **Historical News Data**: News headlines and articles are obtained using The Guardian API for NLP-based sentiment analysis.
- **Recent/Historical Stock Data**: Stock market data, including attributes like open, close, high, low, and volume, is fetched using the Tiingo API.

## How to Run the Code

### Clone the Repository
Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/Predictive-Analytics-for-Stock-Market-Trends.git
