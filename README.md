<h1 align="center">
  Sentiment Analyzer
</h1>
  
<hr>

## 📝Description

The Sentiment Analyzer project aims to address the issue of harmful and hateful content on social media platforms like Twitter by analyzing the sentiments of the user who posts such content online. This can effectively condition the algorithm to find and clear such content before it causes societal harm. The project utilizes natural language processing and basic machine learning techniques for sentiment analysis, which is the automated process of identifying and classifying subjective information in text data.

The project dataset comprises around 32,000 tweets from SemEval2014, SemEval2016, and SemEval2017 development data, with a vocabulary of 10,000 words. The dataset is preprocessed by converting all letters to lowercase, removing some special characters and emoticons, and tagging URLs.

The project utilizes word embedding models such as Word2Vec and GloVe, with normalization techniques to create sentence vectors that are used to form a unique vector. The project employs various neural network configurations based on CNN and LSTM networks, such as Single 3-Layer CNN and LSTM Networks, Multiple CNNs and LSTM Networks, Single 3-Layer CNN and Bidirectional LSTM Network, and Multiple CNNs and Bidirectional LSTM Network.

The project's performance results demonstrate that utilizing the GloVe system increased the performance of almost all configurations by 5%-7%. Using multiple CNNs with LSTM networks instead of simple configurations increased the performance of the system, independently of the word embedding system, by 3%-6%. Separating the text input into regions in most cases did not improve the performance of a configuration. Use of bidirectional LSTM networks instead of simple LSTM networks did not present any real advantage.

The Sentiment Analyzer project is an effective solution for real-time filtering and analysis of comments, which can help control and compose harmful and hateful content online. The project's methodology can be used as a reference for future studies in sentiment analysis tasks.

## 📝Working

The sentiment analyzer uses Natural Language Processing (NLP) techniques to extract features from the text of Twitter tweets, such as the presence of specific words or phrases that are indicative of positive or negative sentiment. Here are the steps involved:

1. Data Collection: The first step is to collect a large number of tweets from Twitter. This can be done using the Twitter API, which allows developers to access a real-time stream of tweets. The tweets can be filtered based on keywords, hashtags, or user accounts to ensure that they are relevant to the topic of interest.

2. Preprocessing: Once the tweets are collected, they need to be preprocessed to remove any noise and irrelevant information. This involves removing stop words (common words such as "the" and "and"), punctuation, URLs, and user mentions. The tweets are also converted to lowercase to ensure consistency.

3. Feature Extraction: The next step is to extract features from the preprocessed tweets. One common method is to use bag-of-words (BoW) representation, where each tweet is represented as a vector of word frequencies. Another method is to use term frequency-inverse document frequency (TF-IDF), which weights the frequency of each word based on how often it appears in the entire dataset.

4. Training: After feature extraction, the sentiment analyzer is trained on a labeled dataset of tweets. The labeled dataset consists of tweets that have been manually annotated as positive, negative, or neutral. The sentiment analyzer learns to associate the features extracted from the tweets with their corresponding sentiment labels.

5. Testing: Once the sentiment analyzer is trained, it can be tested on a separate set of tweets to evaluate its performance. The test dataset consists of tweets that the sentiment analyzer has not seen before. The sentiment analyzer predicts the sentiment label for each tweet in the test dataset, and the accuracy of the predictions is evaluated.

6. Deployment: After testing, the sentiment analyzer can be deployed to analyze new tweets in real-time. The sentiment analyzer takes in new tweets as input, preprocesses them, extracts features, and predicts their sentiment label.

Overall, the sentiment analyzer is a combination of various NLP techniques and machine learning algorithms that work together to classify the sentiment of Twitter tweets.

## 🤖Tech-Stack

Python
- Pandas
- Scikit
- Tensorflow


## 👨‍💻Team Members
- Pranav Shukla
- Adesh Sawant
- Subodh Dalvi


## 🔮Future Scope

The future scope of a Sentiment Analyzer project is vast and diverse. Here are a few potential areas for future development:

1. Integration with more social media platforms: Currently, the project is focused on analyzing tweets from Twitter. However, sentiment analysis can be applied to a variety of other social media platforms like Facebook, Instagram, Reddit, and more. Integrating the Sentiment Analyzer with these platforms can provide a more comprehensive analysis of social media content.

2. Multilingual sentiment analysis: The current project is designed to analyze English language tweets. However, the tool can be enhanced to analyze tweets in other languages. This can help businesses and governments monitor sentiment in a global market or in countries where English is not the primary language.

3. Real-time analysis: The current project analyzes tweets in batches. However, real-time analysis can be achieved by integrating the Sentiment Analyzer with social media platforms' APIs. This will allow businesses to monitor sentiment in real-time and quickly respond to negative sentiment.

4. Sentiment analysis for different domains: Sentiment analysis can be applied to different domains such as politics, finance, entertainment, and more. By training the model on data from these domains, the Sentiment Analyzer can provide a more domain-specific analysis.

5. Advanced deep learning techniques: The current project uses basic deep learning techniques such as CNNs and LSTMs. However, there are several advanced deep learning techniques such as Attention Mechanisms, Transformer Networks, and BERT that can be applied to enhance the performance of the Sentiment Analyzer.

6. Sentiment analysis for non-textual content: Sentiment analysis can be applied to non-textual content like images and videos. This can help businesses and governments monitor sentiment in content like ads, news, and more.

7. Human-in-the-loop analysis: Sentiment analysis tools are not perfect, and there is always a chance of misclassification. Human-in-the-loop analysis can be integrated into the project to ensure the accuracy of the Sentiment Analyzer.

## 💸Applications

There are several potential applications of a project like sentiment analysis:

1. Customer feedback analysis: Sentiment analysis can be used to analyze customer feedback and determine their overall satisfaction with a product or service. This can help businesses identify areas for improvement and make informed decisions about product development.

2. Social media monitoring: Sentiment analysis can be used to monitor social media platforms and track the sentiment of discussions around a brand, product, or topic. This can help businesses understand public perception and respond to customer concerns in a timely manner.

3. Brand reputation management: Sentiment analysis can be used to monitor brand reputation and identify potential negative sentiment before it becomes a larger issue. This can help businesses respond to negative sentiment and manage their online reputation.

4. Political analysis: Sentiment analysis can be used to analyze public opinion around political candidates, policies, and events. This can help political campaigns and policymakers understand public sentiment and make informed decisions.

5. Market research: Sentiment analysis can be used to analyze market trends and understand consumer preferences. This can help businesses identify opportunities for new products or services and make data-driven decisions.

Overall, sentiment analysis has a wide range of potential applications across industries and can provide valuable insights for businesses and organizations.
