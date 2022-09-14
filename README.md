# FakeNewsDetection
Hi Guys,
Me and my friend Siddharth Bharal created a model to detect the authenticity of a news text. The data which we used for training were all the news articles from 2016 - 2018. We could achieve the precision of 97% and F1 score was 0.98. The preprocessing and modelling steps are explained below:

>> The two datasets Fake and Real news were combined and the data was shuffled.
>> The text column was lemmatized and tokens were created.
>> The tokens were then vectorized using TF-IDF Vectorizer.
>> The data was split using train test split and model was trained using NaiveBayes classifier().
>> The prediction was done on the test data.

In the next section we have performed a short sentiment analysis using Vadar Sentiment Analyzer.

-Kanika and Siddharth
