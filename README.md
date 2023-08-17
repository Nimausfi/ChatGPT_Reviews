# **ChatGPT App Reviews - Sentiment Analysis**

## **Dataset**

Dataset can be accessed and downloaded from Kaggle platfrom: [ChatGPT App Reviews](https://www.kaggle.com/datasets/saloni1712/chatgpt-app-reviews)

The ChatGPT App Reviews dataset is a comprehensive collection of user reviews from the ChatGPT mobile app on iOS, capturing valuable insights and sentiments. The dataset enables the understanding of user satisfaction, evaluation of app performance, and identification of emerging patterns.

Preprocessing steps were used to clean the text data, such as converting words to lowercase, deleting punctuation and emojis, removing stop words, and performing lemmatization to reduce words to their base form.

Word clouds are also generated to visualize the most common words associated with positive, neutral, and negative sentiments. These word clouds demonstrate a fast overview of the frequently expressed sentiments in the reviews.

Random oversampling was used in order to tackle the issue of imbalanced data, this approach involves randomly duplicating examples from the minority class and adding them to the training dataset.

## **Models**

In this project, the following series of models/architectures will be applied, we'll then compare the results of each model and see which one performed best:

<br />

- Model 0: Naive Bayes (Baseline)
- Model 1: Feed-Forward Neural Network (Dense Model)
- Model 2: LSTM Model
- Model 3: GRU Model
- Model 4: Bidirectional-LSTM Model
- Model 5: 1D Convolutional Neural Network
- Model 6: TensorFlow Hub Pretrained Feature Extractor

<br />

## **Performance Evaluation**

[Picture]




