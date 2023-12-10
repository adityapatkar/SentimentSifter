# SentimentSifter

## Overview

SentimentSifter is a project focused on the sentiment analysis of tweets using the Sentiment140 dataset, as part of the MSML651 class. This repository demonstrates the application of both classical machine learning and deep learning techniques to analyze sentiments expressed in tweets.

## Installation

- Clone the repository.
- Install the required dependencies listed in `requirements.txt`.
- Download the Sentiment140 dataset from [here](https://www.kaggle.com/kazanova/sentiment140) and place it in the `data` folder.
- Export following environment variables:
  - `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` for connecting to S3.
  - `WANDB_API_KEY` is required to log the results to Weights and Biases.
  - `HUGGINGFACE_KEY` is required to save the models to HuggingFace.
  - `JAVA_HOME` is required to run the spark code.

## Usage

- Check out the `Project_EDA.ipynb` notebook for a detailed analysis of the dataset.
- Navigate to the `classical_ml` or `deep_learning` folders to explore different approaches.
- Follow the Jupyter notebooks for step-by-step instructions.

## Contributing

Contributions to improve the project are welcome.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
