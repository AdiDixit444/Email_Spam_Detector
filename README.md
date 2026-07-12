# Email_Spam_Detector

A Machine Learning and Deep Learning project that detects whether an email/message is **Spam** or **Ham (Not Spam)** using **Natural Language Processing (NLP)** and an **LSTM Neural Network**.

---

## 📌 Project Overview

Spam messages are unsolicited or unwanted emails/messages sent in bulk to users. Detecting spam emails automatically helps reduce inbox clutter and improves email security.

This project performs end-to-end spam classification by preprocessing text data, converting it into numerical sequences, training an LSTM model, and evaluating its performance.

---

## 🚀 Features

- Load and explore the email dataset
- Balance the dataset for better model performance
- Perform text preprocessing:
  - Convert text to lowercase
  - Remove punctuation
  - Remove stopwords
  - Apply stemming
- Visualize frequently occurring words using **WordCloud**
- Convert text into numerical sequences using:
  - Tokenization
  - Sequence Padding
- Build an LSTM-based Deep Learning model
- Train the model using:
  - EarlyStopping
  - ReduceLROnPlateau
- Evaluate the model using Test Loss and Test Accuracy

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- NLTK
- Scikit-learn
- WordCloud

---

## 📂 Project Workflow

### 1. Data Loading
- Load the spam email dataset
- Explore the dataset
- Check dataset shape and class distribution
<img width="562" height="203" alt="image" src="https://github.com/user-attachments/assets/e554fcfa-dee2-49f4-8b2c-9d7894d4e245" />

### 2. Data Preprocessing
- Balance the dataset
- Remove punctuation
- Remove stopwords
- Perform stemming
- Prepare clean text for training
- <img width="597" height="435" alt="image" src="https://github.com/user-attachments/assets/c91af6d0-a60f-4d6f-af2c-75a7cc390269" />
<img width="602" height="451" alt="image" src="https://github.com/user-attachments/assets/7b9930d0-b3cd-4646-a094-a6048d85d513" />


### 3. Data Visualization
- Generate WordCloud for spam messages
- Generate WordCloud for ham messages
-<img width="593" height="308" alt="image" src="https://github.com/user-attachments/assets/e2316ae4-bebb-49a0-8aab-6a1c05f2d5e5" />
<img width="612" height="306" alt="image" src="https://github.com/user-attachments/assets/70794c60-94a6-423b-84c0-da16ac65c93e" />


### 4. Text Vectorization
- Tokenize text
- Convert words into integer sequences
- Apply sequence padding

### 5. Model Architecture

The model consists of:

- Embedding Layer
- LSTM Layer
- Dense Output Layer (Sigmoid Activation)
<img width="672" height="385" alt="image" src="https://github.com/user-attachments/assets/54db8e81-8619-4a2c-93a7-2644a9f080cf" />

---

## 📈 Model Training

The model is trained using:

- EarlyStopping (to prevent overfitting)
- ReduceLROnPlateau (to adjust learning rate automatically)

---<img width="1092" height="209" alt="image" src="https://github.com/user-attachments/assets/981a3157-6503-44ca-9a2b-bce8e3432439" />


## 📊 Model Evaluation

Performance metrics include:

- Test Loss
- Test Accuracy
<img width="557" height="60" alt="image" src="https://github.com/user-attachments/assets/703b361a-02e0-4436-904a-67f6d47079d7" />

---

## 📁 Project Structure

```
Spam-Email-Detector/
│
├── dataset/
├── notebooks/
├── models/
├── images/
├── Spam_Email_Detector.ipynb
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🎯 Future Improvements

- Use Bidirectional LSTM
- Experiment with GRU architecture
- Deploy the model using Flask or Streamlit
- Build a web application for real-time spam detection
- Compare performance with traditional Machine Learning models such as Naive Bayes, SVM, and Random Forest

---

## 🤝 Contributions

Contributions, suggestions, and improvements are welcome.

---

## ⭐ If you found this project useful, don't forget to Star the repository!
