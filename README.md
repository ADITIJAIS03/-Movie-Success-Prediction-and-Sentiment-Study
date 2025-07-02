# 🎬 Movie Success Prediction & Sentiment Study

This project analyzes user reviews of movies to:
- Perform sentiment analysis using VADER (from NLTK)
- Analyze genre-wise sentiment trends
- Predict box office success using a regression model

---

## 📁 Dataset

The dataset contains 10,000 synthetic movie reviews with the following columns:
- `movie_title`
- `genre`
- `rating`
- `budget`
- `gross_earning`
- `review_tweet`
- `sentiment` (labeled)
- `vader_score` (computed)
- `vader_sentiment` (classified)

---

## 🛠️ Tools Used

- Python 🐍
- Pandas, Seaborn, Matplotlib 📊
- Scikit-learn (Linear Regression)
- VADER (NLTK sentiment analyzer)

---

## 📈 Outputs

- **Bar Chart** of average sentiment by genre
- **Scatter Plot** of predicted vs. actual gross earnings

---

## 🚀 How to Run

1. Install requirements:
```bash
pip install pandas matplotlib seaborn scikit-learn vaderSentiment openpyxl
