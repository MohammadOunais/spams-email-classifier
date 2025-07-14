# Spam Email Classifier 📬📛

This project uses a Multinomial Naive Bayes model to classify SMS messages as spam or not spam (ham).

## 🔍 Dataset
Used the **SMS Spam Collection Dataset** with ~5,500 labeled messages.

## 📊 Model Accuracy
Achieved accuracy of **98.57%** using CountVectorizer + Naive Bayes.

## 📁 Steps:
- Data cleaning (remove punctuation, stopwords)
- Vectorization with `CountVectorizer`
- Model training using `MultinomialNB`
- Evaluation using accuracy, confusion matrix, classification report

## 📷 Output Example
![Model Output](spam_output.png)

## 💬 Sample Predictions:
- "You won a lottery! Call now" → **Spam**
- "Hey, are we meeting today?" → **Not Spam**

---

Built with Python, Scikit-learn, and NLTK
