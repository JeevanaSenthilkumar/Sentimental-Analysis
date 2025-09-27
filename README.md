Sentiment Analysis on Twitter Data (Pfizer Vaccine Tweets)
📌 Project Overview

This project applies Sentiment Analysis to classify tweets related to the Pfizer vaccine into Positive, Negative, or Neutral categories. The aim is to leverage Natural Language Processing (NLP) and Machine Learning (ML) techniques to detect public opinion trends, which can support applications like:

Monitoring brand or product reputation

Identifying misinformation and harmful content

Supporting Trust & Safety workflows (spam/abuse detection)

📂 Dataset

Source: Kaggle – Pfizer Vaccine Tweets Dataset

Records: ~11,000 tweets

Format: CSV (comma-separated values)

Features used: Text content of tweets

⚙️ Methodology

Data Collection & Cleaning

Removed URLs, hashtags, punctuations, stop words

Applied lowercasing, stemming, and tokenization

Feature Engineering

Implemented TF-IDF (Term Frequency–Inverse Document Frequency)

Extracted sentiment polarity scores

Model Building

Algorithms used:

Logistic Regression

Support Vector Classifier (SVC)

Applied Hyperparameter Tuning (GridSearchCV)

Visualization

Pie charts, bar graphs for sentiment distribution

Word clouds for positive, neutral, and negative tweets

Heatmap for correlation of features

📊 Results

Logistic Regression Accuracy: 84.64%

Tuned Logistic Regression Accuracy: 85.92%

Support Vector Classifier (SVC) Accuracy: 87.34%

Tuned SVC Accuracy: 87.58% ✅ (Best Performing Model)

🛠️ Tools & Libraries

Python (v3.x)

Pandas, NumPy – Data manipulation

NLTK, TextBlob – NLP preprocessing

scikit-learn – ML model building & evaluation

Matplotlib, Seaborn, WordCloud – Visualization

🚀 How to Run

Clone this repository:

git clone https://github.com/yourusername/sentiment-analysis.git
cd sentiment-analysis


Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook / Python script:

jupyter notebook Sentiment_Analysis.ipynb

🔮 Future Enhancements

Integrate with YouTube/Twitter API for real-time sentiment analysis

Extend to multilingual datasets

Incorporate Deep Learning (LSTMs / Transformers) for improved accuracy

Adapt models for spam/abuse detection in Trust & Safety systems

📌 References

Kaggle Dataset – Pfizer Vaccine Tweets

scikit-learn Documentation

NLTK & TextBlob Libraries

Research on Sentiment Analysis & Opinion Mining
