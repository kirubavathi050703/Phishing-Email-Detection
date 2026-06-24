# Phishing-Email-Detection
![Uploading image.png…]()
# 📧 Phishing Email Detection Model

## 📌 Project Overview

The **Phishing Email Detection Model** is a Machine Learning-based cybersecurity project that classifies emails as **Phishing** or **Safe** using Natural Language Processing (NLP) techniques. The model analyzes the email text and predicts whether the email is malicious or legitimate.

---

## 🎯 Objective

To develop a machine learning model that can accurately detect phishing emails and help users identify potentially harmful messages.

---

## 🚀 Features

* Detects phishing and safe emails.
* Uses **TF-IDF Vectorization** for feature extraction.
* Classifies emails using **Logistic Regression**.
* Displays model accuracy.
* Displays confusion matrix.
* Interactive web interface using Flask.

---

## 🛠️ Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* Flask
* Joblib
* HTML

---

## 📂 Project Structure

```
Phishing-Email-Detection/
│
├── dataset/
│   └── Phishing_Email.csv
│
├── model/
│   ├── phishing_model.pkl
│   └── vectorizer.pkl
│
├── templates/
│   └── index.html
│
├── screenshots/
│
├── app.py
├── train_model.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/Phishing-Email-Detection.git
```

2. Navigate to the project folder

```bash
cd Phishing-Email-Detection
```

3. Create a virtual environment

```bash
python -m venv .venv
```

4. Activate the virtual environment

Windows

```bash
.venv\Scripts\activate
```

5. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Train the Model

```bash
python train_model.py
```

---

## ▶️ Run the Application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## 📊 Model Output

* Email Classification

  * ✅ Safe Email
  * ⚠️ Phishing Email

* Accuracy Score

* Confusion Matrix

---

## 🧪 Sample Test

### Safe Email

```
Hello,

Your interview has been scheduled for tomorrow at 10 AM.

Regards,
HR Team
```

Prediction:

```
✅ Safe Email
```

---

### Phishing Email

```
URGENT!

Click this link immediately to verify your account.

http://bit.ly/free-money

Win ₹50,000 today.
```

Prediction:

```
⚠️ Phishing Email
```

---

## 📸 Screenshots

Add the following screenshots:

* Home Page
* Safe Email Prediction
* Phishing Email Prediction
* Model Accuracy
* Confusion Matrix

---

## 🔮 Future Enhancements

* URL feature extraction
* Sender email analysis
* Deep Learning (LSTM/BERT)
* Email attachment scanning
* Real-time phishing detection
* Deploy using Render or Streamlit Cloud

---

## 👩‍💻 Author

**Kirubavathi**

B.E. Computer Science and Engineering (IoT, Cybersecurity & Blockchain)

SNS College of Engineering

Interested in Cybersecurity, Networking, and Ethical Hacking.
