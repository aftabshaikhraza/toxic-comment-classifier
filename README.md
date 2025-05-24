# Toxic Comment Classifier

A multi-label NLP model trained on the Jigsaw dataset to detect various types of toxic language in online comments.

## Labels:
- toxic
- severe_toxic
- obscene
- threat
- insult
- identity_hate

##  How to Use
1. Download `train.csv` from [Kaggle](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge)
2. Upload `train.csv` to Colab
3. Open and run `toxic_comment_classifier.ipynb`

## Model
- Vectorization: TF-IDF
- Classifier: One-vs-Rest Logistic Regression
- Evaluation: Precision, Recall, F1-Score

## Requirements
Install dependencies from `requirements.txt` using:
```bash
pip install -r requirements.txt
