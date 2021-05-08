*Tags: Python, Machine Learning, Data Engineering, Text Mining*

**Description**: This Python project can pull tweets from Twitter given a keyword, save and retrieve them from CSV or JSON files, detect languages and clear non-english texts, clean spams and similar content texts, extract word frequency and summarize a document, recognize entities in a document, build topics model for a document, predict sentiment from texts, extract live stock quotes and compare the stock movement with the related tweets semtiment.

**Limitation**: For instant run, you can only get tweets from the last 7 days (Twitter limitation). If want more data, you can run the program in auto mode for an extended time.

**Note**: The data pipline for this project starts from Tweets, but you can use many parts of this project for any other kind of text, such as News.

**Notebooks:**
- Get Tweets with a keyword and save to CSV or JSON files
    - *twitter.Api, pandas, json*
- Procress semistructured data (json) to structured data (csv)
    - *pandas, json*
- Detect languages of documents and clear non-english documents
    - *langdetect.detect*
- Clear spam messages with a supervised machine learning model 
    - *sklearn, re, numpy, scipy.sparse*
- Compute similarity score of any 2 documents 
    - *nltk*
- Remove similar documents using Locality Sensitive Hashing (LSH)
    - *binascii, random*
- Extract word frequency & summarize text
    - *spacy, nltk, sklearn.feature_extraction, gensim.summarization*
- Recognize entities 
    - *spacy*
- Build topics model from text
    - *sklearn.feature_extraction.text.CountVectorizer, gensim.matutils.Sparse2Corpus, gensim.models.ldamodel*
- Test different sentiment predict models
    - *nltk.sentiment.vader, sklearn* 
- Predict sentiment from text with the best-scored supervised machine learning model 
    - *sklearn*
- Extract live stock quotes and visualize their movement 
    - *yfinance, matplotlib*
- Compare Tweets Sentiment with stock price changes
    - *pandas, datetime, matplotlib*