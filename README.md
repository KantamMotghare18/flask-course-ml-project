## Flask Course - Project

Flight Price Prediction App
The Flight Price Prediction App is a machine learning-based solution designed to estimate airfare costs based on historical flight data. Built using Flask, the application provides a user-friendly interface for inputting travel details and utilizes a trained model to predict ticket prices. The app is deployed on Render, making it accessible for real-time predictions.

How It Works:
Data Processing: The application processes user inputs, encoding categorical features (airline, source, destination) and formatting datetime variables for efficient model inference.

Model Prediction: A pre-trained regression model, loaded using joblib, predicts flight prices based on input features such as departure time, duration, and number of stops.

Deployment: The app is hosted using Flask for backend processing and Render for cloud-based deployment, ensuring seamless accessibility.

Key Features:
Machine Learning-Based Predictions: Estimates airfare dynamically rather than relying on static pricing charts.

Flask Web Interface: Enables interactive user input and real-time price estimation.

Deployment on Render: Ensures easy access to the app without requiring local setup.

This application serves as a practical tool for analyzing flight price trends and making informed booking decisions.

