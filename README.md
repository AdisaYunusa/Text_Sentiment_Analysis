# Text_Sentiment_Analysis
This research mainly aims to develop model capable of determining the sentiment expressed within personal development reviews (PDR) and leavers’ reviews to help understand leadership trends and areas for improvement.

Dataset Link: https://www.kaggle.com/datasets/tariqsays/sentiment-dataset-with-1-million-tweets

Methodolody includes:
1. Data cleaning and preprocessing
2. Data balancing
3. Model development: To develop the models, two distinct approaches were implemented. The first approach entailed developing a model using the LSTM architecture. The Other approach involved fine-tuning DistilBERT, RoBERTa, and ALBERT pre-trained models. 
4. Hyperparameter tunning.
5. Sentiment analysis tools (Vader and TextBlob) comparism with developed models.
6. Evaluation metrics.


This research effectively trained and developed models (LSTM, DistilBERT, RoBERTa and ALBERT) a Twitter dataset labelled with sentiment and compared these developed models’ performances in addition to that of sentiment analysis tools (VADER and TextBlob) applied to the same dataset. Employing the confusion matrix and its derived evaluation metrics such as accuracy, precision, recall and f1-score, the LSTM model was chosen as the best performed model over the ALBERT model despite the ALBERT model’s high accuracy, precision, recall and f1-score. This is so because of the possible occurrence of overfitting in the ALBERT model, its lesser amount of training time & epochs and lesser steep loss-accuracy curves.
