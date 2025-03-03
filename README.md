# 📌 NLP Sentiment Analysis on Yelp Reviews

## 📝 Project Overview
This project performs **Natural Language Processing (NLP)** techniques to analyze sentiment in Yelp reviews. Using machine learning models, the goal is to classify reviews based on their sentiment and extract meaningful insights.

---

## 📂 Repository Structure

- **`NLP-Project.ipynb`** – Jupyter Notebook containing data preprocessing, exploratory data analysis (EDA), and sentiment classification models.
- **`yelp.csv`** – Dataset containing Yelp reviews with corresponding ratings.

---

## 🚀 Features
- **Text Cleaning & Preprocessing**: Tokenization, stopword removal, stemming/lemmatization.
- **Exploratory Data Analysis (EDA)**: Word clouds, distribution of ratings, and sentiment visualization.
- **Feature Engineering**: TF-IDF, CountVectorizer, Word Embeddings.
- **Machine Learning Models**: Logistic Regression, Naïve Bayes.

---

## 📊 Dataset Description
The `yelp.csv` file contains:
- **text**: Review text
- **stars**: Rating (1-5)
- **useful, funny, cool**: User reactions to reviews

---

## ⚙️ Installation & Dependencies
### Prerequisites:
- Python 3.x
- Jupyter Notebook
- Required Libraries: 
  ```bash
  pip install pandas numpy matplotlib seaborn nltk scikit-learn wordcloud
  ```
## 📈 How to Run

   - Clone the Repository
  ```bash
  git clone https://github.com/yourusername/NLP-Yelp-Sentiment.git
  cd NLP-Yelp-Sentiment
   ```
   - Open NLP-Project.ipynb in Jupyter Notebook.
- Run each cell step by step.

## 🔍 Future Scope

- Implementing Transformer-based NLP models like BERT or GPT for better sentiment classification.
- Expanding the dataset with more reviews for better generalization.
- Deploying the model as a REST API for real-time sentiment analysis.
   
