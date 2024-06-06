# HomePrice.io Project

Welcome to the HomePrice.io project! This project aims to provide a seamless solution for predicting real estate prices based on various parameters such as square footage, number of bedrooms, and other features. By combining data science techniques with web development, I have created an interactive website where users can input property details and receive accurate price predictions.

## Overview

The HomePrice.io project consists of three main components:

1. **Data Science Model**: We leverage the Banglore home prices dataset from Kaggle to build a predictive model using Python and Scikit-learn. The model is trained using linear regression and incorporates various data science concepts such as data cleaning, outlier detection, feature engineering, dimensionality reduction, hyperparameter tuning using GridSearchCV, and k-fold cross-validation.

2. **Python Flask Server**: A Flask server is implemented to serve HTTP requests and provide access to the trained machine learning model. This server acts as the intermediary between the frontend website and the backend machine learning model. It exposes endpoints that the website can call to retrieve predictions based on user input.

3. **Frontend Website**: The frontend of the project is developed using HTML, CSS, and JavaScript. It provides a user-friendly interface where users can input property details such as square footage and number of bedrooms. Upon submission, the website communicates with the Flask server to fetch predictions and displays them to the user.

## Technologies Used

- **Python**: Programming language used for data cleaning, model building, and server-side code.
- **NumPy and Pandas**: Libraries used for data manipulation and cleaning.
- **Matplotlib**: Library used for data visualization.
- **Scikit-learn**: Library used for building machine learning models.
- **Jupyter Notebook, Visual Studio Code, and PyCharm**: Integrated Development Environments (IDEs) used for coding and development.
- **Python Flask**: Micro web framework used for building the HTTP server.
- **HTML/CSS/JavaScript**: Technologies used for building the frontend user interface.

## Usage

To use the HomePrice.io project, follow these steps:

1. **Clone the Repository**: Clone the project repository from [GitHub](https://github.com/ishpreetkaurkhalsa/HomePrice.io.git).

2. **Set up Environment**: Ensure you have Python installed on your system along with required libraries (NumPy, Pandas, Matplotlib, Scikit-learn, Flask).

3. **Run Flask Server**: Open the project in PyCharm and run the Flask server code. This will start the server and make the machine learning model accessible via HTTP endpoints.

4. **Run the Website**: Open the `index.html` file located in the `frontend` directory in your preferred web browser. This will load the frontend interface where you can input property details and get price predictions.

5. **Interact with the Website**: Input property details such as square footage, number of bedrooms, etc., and submit the form. The website will communicate with the Flask server to retrieve predictions and display them to the user.
