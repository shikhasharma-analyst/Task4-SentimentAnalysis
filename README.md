
# Twitter Sentiment Analysis

## 📌 Project Overview

This project performs sentiment analysis on Twitter text data using Natural Language Processing (NLP).

The project cleans and preprocesses Twitter text, performs sentiment analysis using the VADER Sentiment Analyzer, classifies tweets into Positive, Negative, and Neutral categories, and evaluates the sentiment predictions against the original labels.

---

## 🎯 Project Objectives

- Clean and preprocess Twitter text data
- Handle missing and duplicate records
- Perform text normalization
- Analyze sentiment using VADER
- Classify tweets into Positive, Negative, and Neutral sentiments
- Compare original sentiment labels with VADER predictions
- Evaluate sentiment classification performance
- Visualize sentiment distribution and results

---

## 📊 Dataset

The original dataset contains **691,248 records**.

After data cleaning and preprocessing:

- **Original Records:** 691,248
- **Final Records:** 670,422
- **Records Removed:** 20,826
- **Final Columns:** 5

The large CSV datasets are not included in this GitHub repository because of GitHub's file-size limitations. The complete analysis workflow is available in the Jupyter Notebook.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- VADER Sentiment Analyzer
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git & GitHub

---

## 🧹 Data Preprocessing

The project includes the following preprocessing steps:

1. Missing value handling
2. Duplicate detection and removal
3. Text cleaning
4. Text normalization
5. Sentiment scoring
6. Sentiment classification
7. Data validation
8. Performance evaluation
9. Visualization

---

## 😊 Sentiment Categories

The tweets are classified into three sentiment categories:

| Sentiment | Description |
|---|---|
| Positive | Positive or favorable opinion |
| Negative | Negative or unfavorable opinion |
| Neutral | Neither clearly positive nor negative |

---

## 📈 Sentiment Distribution

| Sentiment | Records |
|---|---:|
| Negative | 238,863 |
| Positive | 238,008 |
| Neutral | 193,551 |

---

## 🤖 VADER Sentiment Analysis

VADER (Valence Aware Dictionary and sEntiment Reasoner) was used to calculate sentiment scores for the cleaned Twitter text.

### Performance

**VADER Accuracy: 58.83%**

The project also compares the original dataset labels with the sentiment predicted by VADER.

---

## 📁 Final Dataset

The processed dataset contains the following columns:

- `Text`
- `Clean_Text`
- `Label`
- `VADER_Score`
- `VADER_Sentiment`

Final dataset size:

**670,422 records × 5 columns**

---

## 📂 Project Structure

```text
Task4-SentimentAnalysis/
│
├── Sentiment_Analysis.ipynb
├── README.md
└── .gitignore
