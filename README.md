# 🧠 Simple AI-Powered Text Classifier

## 📝 Objective
This is a beginner-level project that demonstrates how to build a simple **text sentiment classifier** using basic NLP techniques in Python. The classifier can categorize user input as:
- ✅ Positive  
- ❌ Negative  
- 😐 Neutral

---

## ✅ Features

- Classifies real-time user input via the console
- Uses a small custom dataset of labeled examples
- Implements sentiment classification using **TextBlob**
- Clean and beginner-friendly Python code

---

## ⚙️ Tools & Libraries Used

- Python 3.x
- [TextBlob](https://textblob.readthedocs.io/en/dev/) (for sentiment polarity)
- Optional: `nltk` (for TextBlob to work correctly)

---

## 📥 How It Works

### 1. User enters a sentence via `input()`
### 2. The program analyzes sentiment using **TextBlob**
### 3. Classifies as:
- Positive: polarity > 0.1
- Negative: polarity < -0.1
- Neutral: -0.1 ≤ polarity ≤ 0.1

### 4. Displays the sentiment result
### 5. (Optional) Appends the result to a `.txt` file
### 6. (Optional) Counts total number of Positive, Negative, and Neutral inputs during a session


