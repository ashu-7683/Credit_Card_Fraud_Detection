# Credit Card Fraud Detection

This project is an initial exploration of the Credit Card Fraud Detection dataset from Kaggle.

## Steps

1. Install the required packages (including kaggle API).
2. Set up the kaggle API key (you need to have a kaggle account and download the kaggle.json file).
3. Download the dataset and unzip it.
4. Load the dataset and perform initial exploration.

## How to run

1. Clone this repository.
2. Install the requirements: `pip install -r requirements.txt`
3. Set up kaggle API key: 
   - Place your kaggle.json file in the ~/.kaggle/ directory.
   - Ensure the file has the correct permissions: `chmod 600 ~/.kaggle/kaggle.json`
4. Run the Jupyter notebook `creditcard.ipynb`.

Note: The notebook includes the steps to download the dataset, so you don't need to do it separately.

## Dataset

The dataset is from Kaggle: [Credit Card Fraud Detection](https://www.kaggle.com/mig-ulb/creditcardfraud)

## Code

The code is provided in the Jupyter notebook `creditcard.ipynb`.

## Note

This notebook was developed in a Windows environment with a Unix-like shell (like Git Bash). The shell commands (like `mv`, `chmod`) are for Unix. If you are on Windows without a Unix-like shell, you may need to adjust the shell commands.
