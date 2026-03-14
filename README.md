# Sentiment Analysis Web App

A **Sentiment Analysis Web Application** built using **Flask, Machine Learning, and Natural Language Processing (NLP)**.
The app allows users to enter a text comment and predicts whether the sentiment is **Positive or Negative**.

---

## 🚀 Project Overview

This project demonstrates how a trained machine learning model can be deployed as a **web application**.
Users can enter any movie review or comment, and the model predicts its sentiment using **TF-IDF vectorization and Logistic Regression**.

---

## 🧠 Technologies Used

* Python
* Flask
* Scikit-learn
* NLTK
* HTML
* Bootstrap

---

## ⚙️ How It Works

1. User enters a comment in the web interface.
2. The text is **preprocessed** using NLP techniques:

   * Lowercasing
   * Removing HTML tags
   * Removing stopwords
   * Stemming
3. The cleaned text is converted into numerical features using **TF-IDF Vectorization**.
4. The trained **Logistic Regression model** predicts the sentiment.
5. The result is displayed on the webpage.

---

## 📂 Project Structure

```
sentiment-analysis-flask
│
├── app.py                 # Flask backend
├── clf.pkl                # Trained sentiment classification model
├── tfidf.pkl              # TF-IDF vectorizer
├── requirements.txt       # Python dependencies
│
├── templates
│     └── index.html       # Frontend webpage
│
└── README.md              # Project documentation
```

---

## ▶️ Running the Project

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/sentiment-analysis-flask.git
cd sentiment-analysis-flask
```

### 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Download NLTK stopwords

```
import nltk
nltk.download('stopwords')
```

### 4️⃣ Run the Flask app

```
python app.py
```

### 5️⃣ Open in browser

```
http://127.0.0.1:5000
```

---

## 💡 Example

Input:

```
This movie was fantastic and very entertaining!
```

Output:

```
Positive Comment
```

---

## 📸 Screenshot



---

## 📈 Future Improvements

* Add sentiment confidence score
* Support neutral sentiment
* Deploy the app online
* Improve UI with modern styling

---

## 👨‍💻 Author

Vaibhav Batta
B.Tech Final Year Student
Interested in **Machine Learning, NLP, and Web Development**

---

⭐ If you like this project, consider giving it a star on GitHub!
