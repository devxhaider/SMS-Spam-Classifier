# SMS-Spam-Classifier
NLP Text Classification Pipeline of SMS messages as spam or ham using TF-IDF vectorization and Naive Bayes.

## What it does
- Loads the UCI SMS Spam dataset (~5500 messages)
- Converts raw text to numerical features using TF-IDF
- Trains a Multinomial Naive Bayes model
- Achieves ~97-98% accuracy on test set

## Stack
- Python 3.11
- pandas, scikit-learn, matplotlib, seaborn

## How to run
```bash
pip install pandas scikit-learn matplotlib seaborn
```
Open `spam_classifier.ipynb` and run all cells.

## Dataset
[UCI SMS Spam Collection](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection)

## Notes
Built as a beginner NLP project while learning Python and ML fundamentals.
