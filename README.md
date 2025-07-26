# 📦 Amazon Product Review Sentiment Analysis

This project performs sentiment analysis on a sample of Amazon product reviews using Python. It classifies each review as **Positive**, **Negative**, or **Neutral** and visualizes the insights using bar plots and word clouds.

---

## 📁 Dataset

A small synthetic dataset of 10 Amazon product reviews with varied sentiments. You can replace it with a larger real-world dataset from sources like [Kaggle](https://www.kaggle.com/datasets) or [Amazon Customer Reviews Dataset](https://registry.opendata.aws/amazon-reviews/).

---

## 🔍 Key Features

- **Text Preprocessing**: Cleaned and prepared raw review text.
- **Sentiment Analysis**: Used `TextBlob` to extract sentiment polarity and subjectivity.
- **Classification**: Labeled each review as Positive, Negative, or Neutral based on polarity.
- **Visualization**: 
  - Sentiment distribution using Seaborn
  - WordClouds for Positive and Negative reviews

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- TextBlob
- Seaborn & Matplotlib
- WordCloud
- Jupyter Notebook

---

## 📊 Outputs

- **Bar Chart**: Frequency of each sentiment class  
- **Word Clouds**: Highlights of most used words in Positive and Negative reviews  

---

## 📁 Repository Contents
📁 Amazon_Sentiment_Analysis/
├── amazon_reviews_sample.csv # Sample input data
├── Amazon_Sentiment_Analysis.ipynb # Main Jupyter notebook
└── README.md # Project documentation


---

## 🚀 How to Run

1. Clone the repository  
2. Open the notebook in Jupyter  
3. Install dependencies if needed:
   ```bash
   pip install textblob seaborn wordcloud matplotlib


