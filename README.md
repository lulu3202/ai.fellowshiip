# ai.fellowshiip
Code challenge for ai.fellowship

 ## Movie Review Sentiment Analysis

This project demonstrates a sentiment analysis model for movie reviews using an LSTM (Long Short-Term Memory) neural network.

### Project Overview
The project covers the following steps:
1.  **Data Loading and Preprocessing:** Reads a CSV dataset, performs one-hot encoding of sentiment labels, and prepares the data for model training.
2.  **Data Splitting and Tokenization:** Splits the data into training and testing sets and uses tokenization and padding to prepare the text data for the LSTM model.
3.  **Model Building and Training:** Builds a sequential LSTM model using Keras, compiles it, and trains it on the prepared data.
4.  **Model Evaluation and Saving:** Evaluates the trained model on the test data and saves the trained model and tokenizer.
5.  **Inference:** Provides a function to predict the sentiment of new movie reviews.

## Requirements
The key libraries used in this project are:
*   pandas
*   numpy
*   scikit-learn
*   tensorflow
