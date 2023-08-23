# Sentiment Analysis with Convolutional Neural Networks (CNN) - PyTorch

This project aims to build a sentiment analysis model using Convolutional Neural Networks (CNNs) for analyzing Twitter text data. The model utilizes the power of CNNs to extract meaningful features from text and make predictions about the sentiment expressed in the tweets.

## Project Structure

The project has the following structure:

- `Dataset`: This directory contains the dataset files used for training and evaluation.
- `preprocess.py`: Contains preprocessing functions for text data, including tokenization, removal of stopwords, and lemmatization.
- `features.py`: Contains functions for extracting features from preprocessed text data using the bag-of-words approach.
- `model.py`: Implements the CNN model for sentiment analysis using the Conv1DLayer and other necessary layers.

## Dependencies

The project requires the following dependencies:

- Python 3.9 or higher
- numpy
- pandas
- scikit-learn
- tensorflow
- keras
- torch

Ensure that you have the necessary dependencies installed before running the project.

You may install the above dependencies simply by using:

    pip install -r requirements.txt

## Contributing

Contributions to this project are heavily encouraged! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Any kind of contribution will be appreciated.

## License

This project is licensed under the [MIT License](LICENSE).
