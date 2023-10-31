# Future Sales Prediction

## Introduction
This repository contains code for predicting future sales based on advertising expenditures in different media channels: TV, Radio, and Newspaper. The prediction is made using a machine learning model trained on a dataset comprising historical data of advertising budgets and corresponding sales.

## Dataset
The dataset used for this prediction task contains the following columns:
- **TV**: Amount of advertising budget spent on television media (in thousands of dollars).
- **Radio**: Amount of advertising budget spent on radio media (in thousands of dollars).
- **Newspaper**: Amount of advertising budget spent in newspapers or print media (in thousands of dollars).
- **Sales**: Product or service sales data (in the same period as advertising expenditure on TV, Radio, and Newspaper).

### Dataset Source
The dataset was sourced from [https://www.kaggle.com/datasets/chakradharmattapalli/future-sales-prediction/data].

## Dependencies
Ensure you have the following dependencies installed before running the code:
- Python 3.x
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Plotly
- Seaborn
- Jupyter Notebook (optional, for running the provided Jupyter notebook)

## Running the Code
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/future-sales-prediction.git
   cd future-sales-prediction

2. **Install dependencies:**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn plotly jupyter

4. **Run the prediction code:**
   ```bash
   python predict_sales.py

This command will execute the prediction code and display the results.
Note: If you are using the provided Jupyter notebook, you can run the cells inside the notebook for the same result.
   
## Usage Instructions
- The predict_sales.py file contains the code for loading the dataset, training the machine learning model, and making predictions.
- Modify the code as needed to experiment with different machine learning algorithms, hyperparameters, or feature engineering techniques.
- Feel free to explore the Jupyter notebook for a step-by-step walkthrough of the prediction process.
