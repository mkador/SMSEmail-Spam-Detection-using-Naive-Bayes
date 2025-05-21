# 📧 SMS and Email Spam Detection using Naive Bayes

This project implements a **Spam Detection System** using the **Multinomial Naive Bayes** algorithm. The goal is to accurately classify messages (SMS or Emails) as either **spam** or **ham (not spam)** based on their textual content.

---

## 🚀 Features

- ✅ Classifies text messages as **Spam** or **Ham**
- ✅ Implements **Bag of Words** vectorization using `CountVectorizer`
- ✅ Trains a **Multinomial Naive Bayes** classifier
- ✅ Easy-to-understand and beginner-friendly NLP project
- ✅ Clean and well-commented code in Jupyter Notebook

---

## 🧠 Algorithm Used

- **Naive Bayes (MultinomialNB)**:
  - A simple yet effective probabilistic classifier based on Bayes' Theorem.
  - Assumes word features are conditionally independent (a good fit for text classification).
  
- **Bag of Words**:
  - Converts raw text into a matrix of word frequency counts.

---

## 🧾 Dataset

- The dataset contains a mix of **SMS and Email messages**.
- Each message is labeled as:
  - `spam`: Unwanted/advertisement messages
  - `ham`: Normal messages

📂 *Dataset is preloaded within the Jupyter Notebook.*

---

## 📁 Folder Structure

```
SMS_Email_Spam_Detection/
│
├── SMS_Email_Spam_Detection_with_naive_Bayse.ipynb  # Jupyter notebook with full implementation
├── README.md                                         # Project overview and documentation
└── requirements.txt                                  # (Optional) List of Python dependencies
```

---

## ⚙️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mkador/SMS_Email_Spam_Detection.git
   cd SMS_Email_Spam_Detection
   ```

2. **Install required libraries:**
   *(create and activate a virtual environment if needed)*
   ```bash
   pip install -r requirements.txt
   ```

   Or manually:
   ```bash
   pip install pandas scikit-learn numpy
   ```

3. **Run the notebook:**
   ```bash
   jupyter notebook SMS_Email_Spam_Detection_with_naive_Bayse.ipynb
   ```

---

## 📊 Sample Output

The notebook walks through:

- Preprocessing raw messages
- Vectorizing using `CountVectorizer`
- Training the Naive Bayes model
- Predicting and evaluating accuracy
- Printing predictions

---

## 📈 Future Improvements

- Use **TF-IDF Vectorizer** instead of simple Bag of Words
- Add **performance metrics** like confusion matrix, F1-score
- Deploy as a **Flask app** or **Streamlit web app**
- Integrate with real-time SMS/Email inbox using APIs

---

## 🤝 Contributions

Contributions are welcome! If you find any issues or improvements, feel free to open a pull request or issue.

---

## 🧑‍💻 Author

- **Your Name Md. Musa Kalimulla**
   
– [GitHub](https://github.com/mkador) | [LinkedIn](https://www.linkedin.com/in/md-musa-kalimulla169/)

---


