# Inshorts-NLP
Analysed syntax and Semantics of Corpus of Text Documents Retrived from Web Scraping of News articles from Inshorts and followed the Standard NLP Workflow of the CRISP-DM model.


# - How it works
It collects live news from <a href="https://www.inshorts.com/en/read/national">Inshorts.com</a> and runs two pre-trained deep learning LSTM models on each article. First model classifies if the article is related to the COVID-19 pandemic and the second runs a sentiment analysis. The article is displayed only if it is predicted to be positive.

The models stored in the backend are trained on labelled Inshorts news data starting from 01 March, 2020. The data has 4000+ data points and was extracted from Inshorts' website using BS4 and Selenium. It was then labelled on the basis of the topic as well as the sentiment. The dataset has been uploaded on Kaggle for further NLP research (<a href="https://www.kaggle.com/hkapoor/covid19-india-news-headlines-for-nlp">Link</a>).

# - Accuracy
The combined accuracy of the two models is 80% approximately.
