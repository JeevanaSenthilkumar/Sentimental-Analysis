**Sentiment Analysis on Twitter Data**
**📌 Overview**

This project performs Sentiment Analysis on Pfizer vaccine tweets, classifying them as Positive, Negative, or Neutral. It demonstrates the use of NLP and Machine Learning for opinion mining and content moderation tasks.

**📂 Dataset**

Source: [Kaggle – Pfizer Vaccine Tweets]

Size: ~11,000 tweets (CSV format)

Target: Sentiment classification

**⚙️ Methodology**

Preprocessing: Cleaning, stemming, stopword removal, tokenization

Feature Extraction: TF-IDF, sentiment polarity scores

Models: Logistic Regression, Support Vector Classifier (SVC) with hyperparameter tuning

Visualization: Bar charts, pie charts, word clouds, heatmap

**📊 Results**

Logistic Regression: 84.64%

Tuned Logistic Regression: 85.92%

SVC: 87.34%

Tuned SVC: 87.58% ✅ Best

🛠️ Tech Stack

Python (Pandas, NumPy, scikit-learn, NLTK, TextBlob)

Matplotlib, Seaborn, WordCloud

Jupyter Notebook

**🚀 Run Instructions**
git clone https://github.com/yourusername/sentiment-analysis.git
cd sentiment-analysis
pip install -r requirements.txt
jupyter notebook Sentiment_Analysis.ipynb

**🔮 Future Work**

Real-time analysis using Twitter/YouTube APIs

Multilingual sentiment detection

Deep learning models (LSTM, Transformers)
