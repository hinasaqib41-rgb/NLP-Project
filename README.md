# NLP Project: Spam Email / SMS Detection

This project aims to build a machine learning model to classify SMS messages as **Spam** or **Ham** (not spam).  
The project uses the **SMS Spam Collection dataset** and applies NLP techniques such as text preprocessing, Bag of Words, and model training using Naive Bayes and Logistic Regression.

---

## 📌 Dataset

**SMS Spam Collection**

- Contains 5572 SMS messages
- Labels: `ham` (not spam) and `spam`

---

## 🧠 Steps Followed

### 1. Data Loading
- Load dataset from the UCI repository.
- The dataset is tab-separated with two columns: `label` and `message`.

### 2. Data Preprocessing
- Convert text to lowercase
- Remove punctuation
- Remove numbers
- Remove extra spaces

### 3. Feature Extraction
- Convert text to numeric features using **Bag of Words (CountVectorizer)**

### 4. Model Training
Two models are trained:

- **Multinomial Naive Bayes**
- **Logistic Regression**

### 5. Model Evaluation
Evaluation metrics include:
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score

---

## 📈 Results

| Model | Accuracy | Spam Recall | Spam Precision | F1-score |
|------|----------|-------------|----------------|----------|
| Naive Bayes | 98.83% | 0.91 | 1.00 | 0.95 |
| Logistic Regression | 98.39% | 0.89 | 0.99 | 0.94 |

✅ **Best Model:** Naive Bayes

---

## 🧾 How to Run

1. Clone the repository:

```bash
git clone https://github.com/hinasaqib41-rgb/NLP-Project
