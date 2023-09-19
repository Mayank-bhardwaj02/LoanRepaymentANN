# Loan Repayment Prediction using ANN

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project is a comprehensive analysis and prediction model aimed at predicting loan repayment capabilities of individuals using Artificial Neural Networks (ANN). The dataset is sourced from LendingClub and includes various features like credit score, annual income, purpose of the loan, and many others.

### Objective

The primary goal is to build a reliable model that can accurately predict whether a borrower will be able to repay a loan. This is a classification problem where the outcome is binary.

### Dataset

The dataset consists of several numerical and categorical variables that describe the loan status, borrower information, and other attributes related to the loan. The dataset is cleaned and preprocessed for the model.

## Features

- Data Import: Load the data into a Pandas DataFrame for analysis.
- Exploratory Data Analysis (EDA): Comprehensive analysis of the dataset to understand the distribution, correlation, and trend of the data.
- Data Preprocessing: Handling missing values, encoding categorical variables, and scaling features.
- Model Building: Building an ANN model using TensorFlow/Keras.
- Evaluation: Evaluating the model using various metrics to understand its performance.

## Installation

1. Clone this GitHub repository.
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
  
2. Navigate to the project directory and install the required Python packages.
    ```bash
    cd your-repo-name
    pip install -r requirements.txt
    ```
  
3. Download the LendingClub dataset and place it in the appropriate directory.

## Usage

1. Open the Jupyter Notebook `LoanRepaymentANN.ipynb` in a Jupyter environment.
2. Run all the cells to execute the code.
3. The notebook includes comments and markdown to explain the steps involved.

## Technologies Used

- **Python**: The core programming language used for this project.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization.
- **scikit-learn**: For data preprocessing and performance metrics.
- **TensorFlow/Keras**: For building the Artificial Neural Network.

## Contributing

Contributions are welcome! Please read the [Contributing Guidelines](CONTRIBUTING.md) before making any changes.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/YourFeature`)
3. Commit your Changes (`git commit -m 'Add some YourFeature'`)
4. Push to the Branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
