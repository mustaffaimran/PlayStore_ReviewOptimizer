# Preprocessing and Sentiment Analysis of Mobile App Reviews
This project is a Python script that performs preprocessing and sentiment analysis on mobile app reviews using various NLP libraries.

# Dependencies
The following Python packages are required to run this script:

- Pandas
- NumPy
- nltk
- textblob
- vaderSentiment
- sklearn
- num2words
In addition, you will need to download the following NLTK resources:

- stopwords
- wordnet
- omw-1.4

## Usage
To use this script, simply run it using a Python interpreter:

```
python preprocessing_sentiment_analysis.py
```

This script assumes that you have a directory called "4312Project" containing CSV files of app reviews, with each file named after the app's package name.

After running the script, it will preprocess the reviews and output a new CSV file for each app, with the preprocessed reviews. It will then perform sentiment analysis on each review using both TextBlob and VADER libraries, and output a CSV file with the app package name, review, and sentiment polarity for each review.

Lastly, it will perform topic modeling on the reviews using Latent Dirichlet Allocation (LDA) and output the top 10 topics with the top 10 words associated with each topic.
