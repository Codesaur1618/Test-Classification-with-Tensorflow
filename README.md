# README - Sentiment Analysis using TensorFlow and TensorFlow Hub

This repository contains a Python script that demonstrates sentiment analysis using TensorFlow and TensorFlow Hub. The script uses the IMDb reviews dataset and a pre-trained word embedding model to build a sentiment analysis model.

## Prerequisites

- Python (>= 3.x)
- TensorFlow (>= 2.x)
- TensorFlow Hub (>= 0.12)
- TensorFlow Datasets (>= 4.4)

## Installation

1. Make sure you have Python installed. You can download it from the official Python website (https://www.python.org/downloads/).
2. Install TensorFlow, TensorFlow Hub, and TensorFlow Datasets using pip:
pip install tensorflow tensorflow-hub tensorflow-datasets

## Usage

1. Run the Python script in your terminal or IDE.
2. The script will load the IMDb reviews dataset and split it into training, validation, and test sets.
3. A pre-trained word embedding model from TensorFlow Hub is used to convert the reviews into numerical representations.
4. The sentiment analysis model is constructed using a TensorFlow Sequential model with a dense layer.
5. The model is trained using the training set and validated using the validation set for 25 epochs.
6. Finally, the model's performance is evaluated on the test set, providing the accuracy and loss values.

## Contributing

If you wish to contribute to this project, feel free to fork the repository, make improvements, and create a pull request.

## License

This project is licensed under the MIT License. Feel free to use and distribute it according to the terms of the license.

## Note

Ensure you have the required dependencies installed before running the script. The sentiment analysis model's accuracy can be seen by evaluating the test set. The provided code serves as a starting point for further exploration and enhancements in sentiment analysis tasks.