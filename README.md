
# Deep Learning Image Classification Project

## Overview
This project demonstrates a simple image classification application using deep learning. It includes a convolutional neural network (CNN) model built with TensorFlow and Keras, a Flask API to serve predictions, and a basic HTML frontend for user interaction.

## Requirements
- Python 3.6 or later
- TensorFlow 2.x
- Flask
- PIL (Python Imaging Library)
- NumPy

## Project Structure
- `deep_learning_image_classification.ipynb`: Jupyter Notebook for model training and evaluation.
- `flask_api_for_image_classification.py`: Python script for the Flask API.
- `image_classification_frontend.html`: HTML file for the frontend interface.
- `image_classification_model.h5`: Saved model file (generated after training).

## Setup and Running the Application
1. **Model Training**
   - Run the Jupyter Notebook (`deep_learning_image_classification.ipynb`) to train the model. 
   - The model will be saved as `image_classification_model.h5`.

2. **API Setup**
   - Ensure the saved model is in the same directory as the Flask script.
   - Run `flask_api_for_image_classification.py` to start the Flask server.

3. **Frontend Interface**
   - Open `image_classification_frontend.html` in a web browser.
   - Upload an image to get the classification result.

## Usage
- The Flask server must be running to serve predictions.
- Through the HTML interface, upload an image and click 'Upload and Classify' to get the classification result.

## Note
- This project is for demonstration purposes and uses a basic CNN model. For more complex tasks, consider using more advanced models and techniques.
