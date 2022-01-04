# Sentiment analysis of Tweets using Natural Language Processing and Naive-Bayes Classification
Twitter is a social-media platform used to publish short pieces of information (max 240 characters). Since it is one of the most actively used social media platform it is a warehouse for storing tons of data. 

Twitter contains most of its data in the form of text (tweets). Since most tweets are opinion pieces or news updates, they carry a sentiment within them (positive or negative). 
Thus, in this project, I aim to analyse and classify tweets as positive or negative in nature using Natural Language Processing techniques. 

### Dataset: [twitter.csv](https://github.com/jaynilp24/Sentiment-Analysis-using-NLP/files/7806393/twitter.csv)
You may use the above dataset to build your own classifier.

### Flow: 
    1. Importing standard libraries and the dataset. 
    2. Exploring the dataset. This includes finding average length of tweets, visualizing the same using histogram. 
    3. Plotting the WordCloud. 
    4. Data Cleaning:
        4.1. Removing punctuation. 
        4.2. Eliminating stopwords. 
        4.3. Performing Count Vectorization. 
    5. Classification using Naive-Bayes classifier. 
    6. Assessing performance of the model. 

![image](https://user-images.githubusercontent.com/53313023/148033637-1965f633-23f6-4fdd-93be-e7d951c2d3ec.png)

### What is a WordCloud? 
Word clouds are basically a visualization of textual datapoints. Think of them as tags which convey the overall topic/highlight of a text. In the context of this project, we use Word Clouds to check the recurring positive/negative words. This is a very intuitive way of checking the dominance of words which would help us in predicting sentiments. 

#### In the following image, notice the words like 'thankful', 'friend', 'smile', etc... forming the word cloud. 
![image](https://user-images.githubusercontent.com/53313023/148034125-70f98109-3e01-4471-9a31-4e83c8bc2bd8.png)
#### While in the image below, we see words such as 'hate', 'racist', 'Trump', etc... forming the negative word cloud. 
![image](https://user-images.githubusercontent.com/53313023/148034434-dd54bab9-ef3f-40fa-8e64-03fc5de66319.png)

### Naive-Bayes Classification and Assessing the performance of the model. 
Naive-Bayes Classification uses the concept of prior probabilities and the Bayes Theorem to calculate the probability of a future event. When we present our data as the future event, the Naive-Bayes performs classification for that particular datapoint. 
![image](https://user-images.githubusercontent.com/53313023/148034819-fd831c55-0423-4e6b-9a9d-600d07d9cf93.png)
![image](https://user-images.githubusercontent.com/53313023/148034860-e15926c9-8de1-42ed-8b41-767333ee1248.png)

#### We assess the model performance using a confusion matrix. 
![image](https://user-images.githubusercontent.com/53313023/148034964-69101aed-2707-4f85-bd26-d85d38097e67.png)

### Many thanks to Ali Toosi (https://www.kaggle.com/arkhoshghalb/twitter-sentiment-analysis-hatred-speech) for sharing this problem and dataset!
