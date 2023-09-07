# FraudF
credit card fraud detection model
# Overview
FraudF is a powerful fraud detection model developed to analyze large volumes of transactional data and flag potential credit card fraud activities. Leveraging the Random Forest and Gradient Boosting algorithms in Python, FraudF aims to accurately detect fraudulent transactions with an impressive 95% accuracy rate.

# Table of Contents
- [Features](#Features)
- [Installation](#Installation)
- [Usage](#Usage)
- [Data Preparation](#Data-Preparation)
- [Training the Model](#Training-the-Model)
- [Evaluation](#Evaluation)
- [Contributing](#Contributing)
- [License](#License)

# Features
FraudF utilizes the power of Random Forest and Gradient Boosting algorithms to effectively detect fraudulent transactions.

An ETL pipeline is provided to clean and preprocess transaction data, making it ready for model training.

The model has been trained on a large dataset and boasts an accuracy rate of 95% in detecting fraudulent transactions.

# Installation
1. Clone the repository
2. Navigate to the project directory:
   ```bash
    cd FraudF
    ```
3. Recomended to create a virtual environment
  ```bash
    python -m venv venv
  ```
4. Activate virtual environment:
   - On Mac/Linux
      ```bash
      source venv/bin/activate
      ```
   - On Windows
      ```bash
      venv\Scripts\activate
      ``` 
    
5. Install the required dependencies:
 ```bash
    pip install -r requirements.txt
  ```

# Usage
# Data Preparation
Before using FraudF, you need to prepare your transaction data. Follow these steps:

Place your transaction data file (e.g., transactions.csv) in the data directory.

Run the ETL pipeline to clean and preprocess the data:

  ```bash
    python etl_pipeline.py
  ```

# Training the Model
To train the FraudF model, execute the following command:
  ```bash
    python train_model.py
  ```
This will train the model on the preprocessed data and save the trained model to the models directory.

# Evaluation
You can evaluate the performance of the model using this:
  ```bash
    python evaluate_model.py
  ```
This will provide metrics such as accuracy, precision, recall, and F1-score for fraud detection.

# Contributing
Contributions to enhance FraudF is welcomed!! If you'd like to contribute, please follow our Contribution Guidelines.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
