# House Price Prediction Web Application

This repository contains a Flask web application for predicting house prices based on a dataset sourced from Kaggle. The application utilizes machine learning algorithms to analyze various features of houses in Indian cities and provide an estimated price.

## Dataset

The dataset used in this project is sourced from Kaggle and consists of information about houses in Indian cities. It includes various features such as the area of the house, number of bedrooms, location, and other relevant attributes. The dataset has been preprocessed and cleaned to ensure accurate predictions.

## Requirements

To run the web application locally, you need to have the following installed:

- Python 3.x
- Flask
- Pandas
- Scikit-learn

You can install the required Python packages by running the following command:


## Usage

To use the web application, follow these steps:

1. Clone this repository to your local machine.
2. Download the dataset from Kaggle and place it in the project directory.
3. Open a terminal or command prompt and navigate to the project directory.
4. Install the required packages by running `pip install -r requirements.txt`.
5. Start the Flask development server by executing the command `python app.py`.
6. Once the server is running, open your web browser and go to `http://localhost:5000`.
7. You will be presented with a web interface where you can enter the details of the house.
8. Fill in the necessary information and click the "Predict" button.
9. The application will process the input and provide an estimated price for the house based on the trained machine learning model.

## Flask Application Structure

The Flask application consists of the following main files and directories:

- `app.py`: The entry point of the Flask application.
- `templates/`: This directory contains the HTML templates used for rendering the web pages.
- `static/`: This directory contains static files such as CSS stylesheets and client-side JavaScript.
- `model/`: This directory contains the trained machine learning model for house price prediction.
- `utils.py`: This file contains utility functions used in the application.
- `preprocessing.py`: This file includes functions for preprocessing the dataset.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


## Acknowledgments

We would like to acknowledge the contributors of the original dataset from Kaggle. Their efforts in collecting and preparing the data have made this project possible.
