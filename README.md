# 🧠 Emotion Detection & Learning Support Engine

An AI-powered web application that analyzes a student's study-related text to detect their emotional state and provides personalized learning guidance using Machine Learning and Generative AI.

Built with **Python**, **Streamlit**, **BiLSTM**, **BERT**, **Google Gemini API**, and **SQLite**.

---

## 📌 Overview

The Emotion Detection & Learning Support Engine helps identify a student's emotional state from text describing academic challenges. Based on the detected emotion, the system generates personalized learning suggestions and motivational support to improve the student's learning experience.

The application combines a lightweight BiLSTM model for fast inference with a Transformer-based BERT model for better contextual understanding.

---

## 🚀 Features

- 🎯 Emotion detection from student text
- 🤖 Dual-model prediction using BiLSTM and BERT
- 💡 Personalized learning recommendations
- ✨ AI-generated guidance using Google Gemini
- 📊 Interactive Streamlit dashboard
- 💾 Stores prediction history in SQLite
- 📈 Emotion analytics and visualization
- ⚡ Fast and user-friendly interface

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Frontend | Streamlit |
| Programming Language | Python |
| Machine Learning | TensorFlow, Keras |
| NLP | Hugging Face Transformers, BERT |
| AI | Google Gemini API |
| Database | SQLite |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Plotly |

---

## 📂 Project Structure

```
Emotion-Detection/
│
├── app.py
├── requirements.txt
├── .env
├── database/
├── data/
├── models/
│   ├── bilstm/
│   └── bert/
├── notebooks/
├── src/
│   ├── preprocessing.py
│   ├── predict.py
│   ├── model.py
│   └── bert_model.py
├── assets/
├── screenshots/
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Emotion-Detection.git

cd Emotion-Detection
```

---

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate it

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Configure Environment Variables

Create a `.env` file in the project root.

```env
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```

---

### 5. Run the Application

```bash
streamlit run app.py
```

The application will start at

```
http://localhost:8501
```

---

## 🧠 Emotion Classes

The model predicts the following student emotions:

- 😊 Confident
- 🤔 Curious
- 😕 Confused
- 😫 Frustrated
- 😴 Bored

---

## 📊 Workflow

```
Student Input
       │
       ▼
Text Preprocessing
       │
       ▼
BiLSTM Prediction
       │
       ▼
BERT Prediction
       │
       ▼
Emotion Classification
       │
       ▼
Gemini AI Recommendation
       │
       ▼
Store Results in SQLite
       │
       ▼
Display Analytics Dashboard
```

---

## 📸 Screenshots

Add screenshots of your application here.

```
screenshots/
├── home.png
├── prediction.png
├── analytics.png
```

---

## 📈 Future Improvements

- Voice emotion analysis
- Speech-to-text support
- Multi-language support
- Student progress tracking
- Teacher dashboard
- Authentication system
- Cloud deployment

---

## 👨‍💻 Author

**Mohit Jain**

B.Tech CSE (AI & ML)

---

## ⭐ If you found this project useful

Give this repository a ⭐ on GitHub.
