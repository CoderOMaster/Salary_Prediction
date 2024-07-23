
# Bank Loan Prediction

This project predicts whether a loan will be approved based on various applicant details.

## Overview

The Bank Loan Prediction project is designed to help banks and financial institutions predict the approval of loan applications using machine learning models. This helps in automating the loan approval process and reducing manual effort.

## Model

- **model.py**: This script is responsible for training the model and saving it to disk.
- **model.pkl**: This is the saved machine learning model in pickle format.

## Application

- **app.py**: This Flask application handles the API endpoints for making predictions. It loads the trained model and provides an interface for inputting applicant details and receiving predictions.

## Setup and Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/CoderOMaster/Bank_Loan_Prediction.git
    cd Bank_Loan_Prediction
    ```

2. Install the required packages:
    ```bash
    pip install -r requirement.txt
    ```

3. Run the application:
    ```bash
    python app.py
    ```

4. Access the application at `http://localhost:5000`.

## Usage

1. Open the command prompt and navigate to the project directory.
2. Run the Flask application.
3. Use a tool like Postman or a web browser to interact with the API.
4. Submit applicant details to the `/predict` endpoint to get the prediction.

## Files

- **static/**: Contains CSS files.
- **templates/**: Contains HTML files.
- **app.py**: Main Flask application file.
- **model.pkl**: Trained model file.
- **model.py**: Script to train and save the model.
- **request.py**: Script to make prediction requests.
- **requirement.txt**: List of dependencies.
- **server.py**: Server script.

