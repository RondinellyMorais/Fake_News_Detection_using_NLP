# Fake News Detection Using NLP Techniques
![nlp](https://github.com/RondinellyMorais/Fake_News_Detection_using_NLP/blob/master/nlp.jpg)

The objective of this work is to build a model to detect fake news using NLP techniques to handle the text.

Natural Language Processing (NLP) uses algorithms to understand and manipulate human language. This technique is one of the most largely applied areas of machine learning. The NLP technique let handler no unstrutured data like speech or text in different formats. Since unstructured data is the majority of data worldwide and will represent over 80% of all data by the 2025. NLP use the state-of-the-art machine learning and deep learning techniques to handler no unstrurured data. With all the broad tools of NLP we can extract a lot of insights from the data. 

Some of most common applications in NLP are the sentiment analysis, create tools to translate languages, summarize text, and even build chatbots. The areas covered range from  prediction of diseases based on electronic health records to  financial traders. 

This notebook we let's focus on building a predictive fake news model using NPL techniques to handle the data. We can cite, for didactic purposes, an excellent article where we can learn the fundamental concepts of NLP using the Spacy library: [INTRODUCTION TO SPACY 3](http://spacy.pythonhumanities.com/intro.html).

![REN](https://github.com/RondinellyMorais/Fake_News_Detection_using_NLP/blob/master/REN.gif)

Every day we consume a large amount of information in different formats and from different sources. But sometimes it becomes difficult to decide which information is fake and which one is authentic. Of course, false news can't just affect our personal decisions, but also broader decisions such as financial market decisions. Developing models capable of detecting false news in the middle of full of information represents a very powerful tool. Usaremos como base de dados dois datasets, um contendo texto com as noticias verdadiras e outro com as noticias. We will use two datasets as a database, one containing text with the true news and the other with the news. The database source is at the following link [fake-and-real-news-dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset).

Briefly, let's visualize the data and join the two databases in a single dataframe. We will do the removal of stopwords and lemmatization of texts. We'll get the N-grams and a word cloud of text words. To make de fake news prediction we will use two classification machine learning models. The validation metrics used of models will be the precision, accuracy, f1-score, recall and ROC-AUC. 

**The notebook with the code can be found here:** [FAKE AND REAL NEWS DETECTION USING NATURAL LANGUAGE PROCESSING (NLP)](
https://github.com/RondinellyMorais/Fake_News_Detection_using_NLP/blob/master/FakeNews_Detection_Using_NLP.ipynb)
