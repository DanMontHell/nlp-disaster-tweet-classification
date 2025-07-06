# 🧠 Tweet Disaster Classifier

A Natural Language Processing project that classifies tweets as disaster-related or not. Built using classic ML models and evaluated with performance metrics, this project explores how text preprocessing and model tuning impact predictive accuracy.

---

## 📦 Dataset

The dataset is from a [Kaggle competition](https://www.kaggle.com/competitions/nlp-getting-started/overview) and contains:

- `text`: raw tweets
- `target`: 1 if the tweet is about a real disaster, 0 if not

---

## 🎯 Objective

To predict whether a tweet is about a real disaster using traditional ML techniques and a custom preprocessing pipeline.

---

## 🔍 Project Tasks

- Data exploration and class balance check
- Text preprocessing (cleaning, lemmatization, stopword removal)
- Feature extraction using TF-IDF
- Model training with:
  - Logistic Regression
  - Naive Bayes
  - Random Forest
  - XGBoost
- Hyperparameter tuning via GridSearchCV
- Evaluation using precision, recall, F1-score
- Visualisation of top tokens and model performance

---

## 🚀 How to Use

1. Clone the repo  
   ```bash
   git clone https://github.com/yourusername/tweet-disaster-classifier.git
   cd tweet-disaster-classifier

2. Install dependencies
   ```bash
   pip install -r requirements.txt
   
3. Launch the notebook
   ```bash
   jupyter notebook
   
4. Run notebookv2.ipynb to explore the full workflow.

---

## 📊 Results and Insights

![F1 Scores Class 1](https://github.com/DanMontHell/nlp-disaster-tweet-classification/blob/main/f1score2.png)

- All models performed similarly, with Logistic Regression and Random Forest (tuned) outperforming others on class 1 (disaster tweets).

- Preprocessing greatly impacted class separability — removing words like "u", "amp", and "via" improved clarity.

- Class 1 tweets remained harder to classify, likely due to subtler language and context.

---

## 📌 Conclusion

This project showcases the power of preprocessing and model tuning in improving tweet classification. It serves as a strong baseline for future improvements using deep learning or contextual embeddings (e.g., BERT).

---

## 🛣️ Next Steps

- Implement more advanced NLP techniques (e.g. BERT, RoBERTa)
- Use word embeddings (Word2Vec, GloVe)
- Perform error analysis to explore ambiguous tweets

----

## 📬 Contact
For insights, discussions, or collaboration opportunities, connect on:  
[LinkedIn](https://www.linkedin.com/in/danhellmuth/) or  
[GitHub](https://github.com/DanMontHell)  
hellmuthd08@gmail.com  
