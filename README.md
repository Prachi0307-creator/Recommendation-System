# 📰 News Recommendation System

## 📌 Overview

The **News Recommendation System** is designed to deliver personalized article suggestions by analyzing the content of news headlines. It utilizes **Natural Language Processing (NLP)** techniques and **Machine Learning** algorithms to compute semantic similarity between different news items and recommend relevant content tailored to user interests.

This project enhances user experience by:
- Identifying underlying meanings of news headlines
- Recommending articles based on content similarity
- Personalizing reading suggestions for individual users

---

## 📁 Dataset

- **Source**: `News_Category_Dataset_v2.json`
- **Description**: Contains news headlines and their corresponding categories from HuffPost, covering multiple sections like politics, tech, entertainment, etc.

---

## 🧰 Technologies & Libraries Used

- **Language**: Python 3
- **Libraries**:
  - `pandas`, `numpy`
  - `nltk` (tokenization, lemmatization, stopwords)
  - `scikit-learn` (`TfidfVectorizer`, `cosine_similarity`, `pairwise_distances`)
  - `matplotlib`, `seaborn` (for data visualization)

---

## 🔍 Core Functionalities

- **Text Preprocessing**:
  - Tokenization
  - Stopword Removal
  - Lemmatization

- **Feature Extraction**:
  - TF-IDF Vectorization

- **Similarity Computation**:
  - Cosine Similarity between news vectors
  - Content-based filtering using distance metrics

- **Recommendation Output**:
  - Given a news headline, returns top-N similar news articles.

---

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Make sure you have the required libraries installed:
   ```bash
   pip install numpy pandas nltk scikit-learn matplotlib seaborn
3.Download necessary NLTK resources:
   ```bash
     import nltk
     nltk.download('punkt')
     nltk.download('wordnet')
     nltk.download('stopwords')
```
---

## 👨‍💻 Author

Prachi 
For collaboration or queries, feel free to connect!
