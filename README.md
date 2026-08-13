# Twitter Sentiment Analysis

## Project Overview
This project performs sentiment analysis on Twitter text data using Natural Language Processing (NLP). The analysis classifies tweets into positive, negative, and neutral sentiments and compares the original labels with VADER-based sentiment predictions.

## Dataset
The dataset contains Twitter text data with sentiment labels.

- Original Records: 691,248
- Final Records: 670,422
- Records Removed: 20,826
- Final Columns: 5

The large CSV dataset files are excluded from this repository because of GitHub's file-size limitations. The analysis notebook contains the complete processing workflow.

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- VADER Sentiment Analyzer
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Preprocessing

The project includes:

1. Missing value handling
2. Duplicate removal
3. Text cleaning
4. Text normalization
5. Sentiment analysis using VADER
6. Sentiment classification
7. Model evaluation
8. Data visualization

## Sentiment Categories

- Positive
- Negative
- Neutral

## Results

### Sentiment Distribution

| Sentiment | Count |
|---|---:|
| Negative | 238,863 |
| Positive | 238,008 |
| Neutral | 193,551 |

### VADER Performance

VADER Accuracy: **58.83%**

## Output Dataset

The final processed dataset contains:

- Original Text
- Cleaned Text
- Original Label
- VADER Score
- VADER Sentiment

Final dataset size: **670,422 records**

## Project Structure

```text
Task4-SentimentAnalysis/
│
├── Sentiment_Analysis.ipynb
├── .gitignore
└── README.md
