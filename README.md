# Sentiment-Analysis-of-Amazon-Reviews

## General info
The project concerns the classification of positive and negative reviews of Amazon users. Dataset contains 4 million reviews with same number of positive and negative examples. <br> 
For this task I implemented two models, where each of them are using word embeddings (downloaded and my own):
* MLP average vector model - words embedding vectors are averaged across the review and then fed to MLP network.
* LSTM model - contains embedding layer, 1 layer of LSTM and 2 Dense layers.

LSTM model achived 94.5% accuracy on the test set.

## Technologies
* Python version: 3.6.8
* Keras version: 2.2.4
* Cuda version: 10.0.130
* Sklearn version: 0.20.2
* Pandas version: 0.23.4
* Seaborn version: 0.9.0

## Setup
Download Glove Word Embeddings, Amazon Reviews from Kaggle (both are linked in notebook). To start training, first create preprocessed data files from downloaded word embeddings or custom. Run 'Sentiment Analysis.ipynb' with compatible versions of libraries above.