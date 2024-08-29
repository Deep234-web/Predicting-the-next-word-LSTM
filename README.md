# Next Word Prediction with LSTM and Early Stopping

This project demonstrates a web application that predicts the next word in a given sequence of text using an LSTM (Long Short-Term Memory) model. The model is trained on sequences of text data and uses early stopping to avoid overfitting.

## Project Overview

- **Model**: The core of the application is an LSTM model that has been trained to predict the next word in a sequence. The model is designed to understand the context of the provided text and predict the most probable next word.
  
- **Tokenizer**: A tokenizer is used to convert the input text into sequences that the LSTM model can process. This tokenizer was created during the model training phase and is essential for interpreting the input correctly.

- **Streamlit Interface**: The project utilizes Streamlit to create a user-friendly web interface. Users can input a sequence of words, and the application will predict and display the next word in the sequence.

## Features

- **User Input**: Enter a sequence of words, and the app predicts the next word based on the trained LSTM model.
- **Prediction Output**: The predicted word is displayed directly on the interface, allowing users to see the model's output immediately.

## Live Demo

You can try out the live application here: [Next Word Prediction Web App](https://predicting-the-next-word-lstm-tnlvjrz7biplhhmwwcpft2.streamlit.app/)
