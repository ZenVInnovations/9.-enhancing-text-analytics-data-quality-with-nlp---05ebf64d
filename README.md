# 📊 NLP Text Analytics Web App

A simple Streamlit app to analyze text by extracting named entities and determining sentiment. Built using Python NLP libraries like spaCy, NLTK, and TextBlob.

## 🚀 Features

- Clean and tokenize user input
- Named Entity Recognition (NER) using spaCy
- Sentiment analysis (Positive, Negative, Neutral) using TextBlob
- Add new entries and display them in an interactive table


## 🛠️ Local Installation

To run this project locally:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
pip install -r requirements.txt
python -m nltk.downloader punkt stopwords
python -m textblob.download_corpora
python -m spacy download en_core_web_sm
streamlit run file.py

## Deploy on Streamlit Cloud
Push to GitHub → Visit https://share.streamlit.io → Select file.py

