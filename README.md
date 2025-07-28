<p align="center">
  <img src="https://img.icons8.com/emoji/96/robot-emoji.png" width="80" alt="AI Icon"/>
</p>

<h1 align="center">📩 SMS Spam Classifier</h1>

<p align="center">
  Machine Learning model to classify text messages as <b>Spam</b> or <b>Ham</b> using <code>Python</code> and <code>Scikit-learn</code>.
</p>

---

## 🔍 Overview

In today's digital world, spam messages clutter inboxes and pose security risks. This project uses a **Naive Bayes Machine Learning model** to detect spam messages based on their content. The project involves:
- Text preprocessing & feature extraction with **TF-IDF**
- Building & training a model with **scikit-learn**
- Evaluating model performance with metrics like **accuracy**, **precision**, **recall**, and **F1-score**
- (Optional) UI deployment using **Streamlit** for real-time classification

---

## 🧠 Features

- 📥 Input any SMS message and predict whether it's spam or not
- ✂️ Preprocessing includes stop word removal, punctuation stripping, and tokenization
- 🤖 Trained with **Multinomial Naive Bayes** for fast and effective classification
- 📊 Performance evaluated with confusion matrix & classification report
- 🧪 Built using real-world SMS spam dataset (UCI Machine Learning Repository)

---

## 🧰 Tools & Technologies

| Category         | Tools / Libraries              |
|------------------|-------------------------------|
| Language         | Python 🐍                     |
| ML Libraries     | Scikit-learn, Pandas, NumPy   |
| Text Processing  | NLTK, re                      |
| Visualization    | Matplotlib, Seaborn 📊        |
| Deployment (optional) | Streamlit 🖥️               |

---

## 📂 Folder Structure

```bash
sms-spam-classifier/
├── data/                   # Dataset (CSV)
├── notebooks/              # Jupyter notebooks
├── spam_classifier.py      # Core model code
├── streamlit_app.py        # (Optional) UI app
├── requirements.txt        # Dependencies
└── README.md               # You’re here!
