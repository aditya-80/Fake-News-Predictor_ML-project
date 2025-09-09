# 📰 Fake News Predictor (Machine Learning Project)

## 📌 Project Overview  
This project focuses on building a **Fake News Prediction Model** using **Machine Learning** techniques.  
The goal is to classify whether a given news article is **Real** or **Fake** based on its textual content.  
The project uses **Natural Language Processing (NLP)** for text preprocessing and feature extraction, followed by machine learning models for classification.

---

## 📂 Dataset  
- The dataset contains **news articles** labeled as **real** or **fake**.  
- Key features:  
  - `title` → Title of the news  
  - `text` → Main content of the news  
  - `label` → Target variable (0 = Real, 1 = Fake)  

*(Dataset source: Kaggle / other open-source datasets)*

---

## 🔎 Exploratory Data Analysis (EDA)  
Performed EDA to understand dataset patterns:  
- Checked for missing values and data imbalance.  
- Analyzed **word frequency** in real vs fake news.  
- Visualized word clouds for Fake and Real news articles.  
- Distribution of text lengths and title lengths.  

---

## 🛠️ Preprocessing Steps  
- Removal of **punctuation, stopwords, and special characters**  
- Text **tokenization & lemmatization**  
- Conversion to lowercase  
- Feature extraction using:  
  - **Bag of Words (BoW)**  
  - **TF-IDF Vectorization**  

---

## 🤖 Machine Learning Models  
Implemented and compared the performance of different models:  
- Logistic Regression  
- Naïve Bayes  
- Random Forest  
- Support Vector Machine (SVM)  

📊 Evaluated models using:  
- Accuracy  
- Precision, Recall, F1-Score  
- Confusion Matrix  

---

## 🚀 Results  
- Best performing model: **(Fill your best model here, e.g., Logistic Regression or Random Forest)**  
- Achieved an accuracy of **XX%** on the test dataset.  

---

## 📊 Visualizations  
- Word clouds for Fake vs Real news  
- Most frequent words in Fake and Real articles  
- Model performance comparison (Accuracy, Precision, Recall, F1-score)  

---

## 📌 How to Run the Project  
1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/Fake-News-Predictor.git
   cd Fake-News-Predictor
2. Install dependencies
   ```bash
   pip install -r requirements.txt
3. Run the Jupyter Notebook
   ```bash
   jupyter notebook Fake\ News\ Predictor_A.ipynb

## 📌 Future Improvements
Use Deep Learning models (LSTM, BERT) for better accuracy.
Deploy the model using Flask/Django or as a Streamlit web app.
Add a real-time news verification system via API.

