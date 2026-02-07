# 🎬 Movie Review Sentiment Analysis

This project performs **Sentiment Analysis** on movie reviews using the **IMDB 50K Movie Reviews Dataset**.  
The goal is to classify a given movie review as **Positive** or **Negative** using classical Natural Language Processing (NLP) techniques and Naive Bayes models.

---

## 📂 Dataset

- **Name:** IMDB Dataset of 50K Movie Reviews  
- **Source:** Kaggle  
- **Total Samples:** 50,000  
- **Classes:** Positive, Negative (Balanced Dataset)

### Features
- `review` → Textual movie review  
- `sentiment` → Target label (positive / negative)

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied to clean and prepare the text data:

- Removal of HTML tags  
- Conversion of text to lowercase  
- Removal of special characters and punctuation  
- Stopword removal using **NLTK**  
- Stemming using **Porter Stemmer**  
- Text vectorization using **CountVectorizer**

---

## 🧠 Models Used

The following **Naive Bayes classifiers** were implemented:

- **Multinomial Naive Bayes**
- **Bernoulli Naive Bayes**

These models are well-suited for text classification problems and perform efficiently on large datasets.

---

## 📊 Model Evaluation

Model performance was evaluated using:

- **Accuracy Score**
- Comparison between different Naive Bayes variants

The evaluation helps identify the best-performing model on unseen test data.

---

## 🚀 Results

- Both Naive Bayes models achieved good accuracy
- Multinomial Naive Bayes performed slightly better for text-based features
- The project demonstrates the effectiveness of classical ML techniques for NLP tasks

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- NLTK  
- Scikit-learn  
- Kaggle Notebook  

---

## 📌 Conclusion

This project shows how proper text preprocessing combined with traditional machine learning models can effectively solve sentiment analysis problems.  
Naive Bayes serves as a strong baseline model for NLP and text classification tasks.

---

⭐ If you find this project useful, feel free to star the repository!

