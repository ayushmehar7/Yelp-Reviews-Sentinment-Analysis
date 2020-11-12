# Yelp-Reviews-Sentinment-Analysis
Sentiment Analysis of over 1000 Yelp restaurants reviews using LSTM model in PyTorch and predicting the sentiments of unknown reviews simultaneously

![Sentiment](https://raw.githubusercontent.com/ayushmehar7/Yelp-Reviews-Sentinment-Analysis/main/1-1-1.png)

## Requirements
- python >= 3.6
- numpy
- pandas
- matplotlib
- seaborn
- ntlk
- pytorch 1.1.0
- torchvision 0.2.2

I have trained the model on my gpu device through CUDA, in case you don't have a gpu you can used CPU by removing .cuda() from the notebooks

[DataSet Link](https://archive.ics.uci.edu/ml/datasets/Sentiment+Labelled+Sentences)

In the dataset folder there are Amazon, Yelp and Imdb Reviews. I have used Yelp Reviews.

The train GPU Model is also provided in the repo
