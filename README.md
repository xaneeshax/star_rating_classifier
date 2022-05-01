# Star Rating Classifier

PROJECT LINK:
https://colab.research.google.com/drive/1XOUxBUA8pviGfE-4V_SyEFuC66f_L9J-?usp=sharing

# Abstract

I worked on classifying the rating of user reviews on Amazon that collected user reviews regarding food on the website over the last decade. Using visualization libraries including matplotlib, seaborn, plotly, and word clouds I displayed some of the common text, words, and review length in the dataset. I used a word encoder, word embeddings, and data preprocessing in order to prepare the data for deep learning. I used Naive Bayes for a baseline accuracy and then utilized RNNs with different varieties of LSTM layers, Bidirectional Layers, and Dropout Layers in order to find the model that yielded the best results for this dataset. Overall, I found that the model that employed LSTMs with a few dropout layers performed really well on the testing dataset with an 80% accuracy and at classifying unseen reviews.

# Dataset
https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews 
