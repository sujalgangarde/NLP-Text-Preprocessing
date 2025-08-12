# 📝 Text Preprocessing & Analysis Learning

This project is a **hands-on learning resource** for mastering **text preprocessing in NLP (Natural Language Processing)** using Python.  
It is divided into **three Jupyter notebooks** that gradually move from basic text cleaning to advanced feature extraction, while integrating **data analysis and visualization**.

---

## 📂 Files Included

1. **01_Basic_Text_Preprocessing.ipynb**  
   - Introduction to text preprocessing  
   - Lowercasing, punctuation removal, number removal, extra spaces  
   - Tokenization (word & sentence)  
   - Stopword removal  
   - Lemmatization & stemming  
   - Printing results after each step for clear learning  

2. **02_Advanced_Text_Cleaning_Analysis.ipynb**  
   - Removing special characters, emojis, HTML tags, URLs, emails  
   - Spelling correction & contraction handling  
   - Handling negations  
   - Named Entity Recognition (NER)  
   - POS tagging  
   - Data analysis with **pandas** & **numpy**  
   - Visualizations with **matplotlib**, **seaborn**, and **wordcloud**  

3. **03_Feature_Extraction_for_ML.ipynb**  
   - Bag of Words  
   - TF-IDF Vectorization  
   - N-grams  
   - Word embeddings (Word2Vec, GloVe - sample implementation)  
   - Preparing data for machine learning models  

---

## 📦 Libraries Used

- **NLP**: `nltk`, `spacy`, `textblob`, `re`
- **Data Analysis**: `pandas`, `numpy`
- **Visualization**: `matplotlib`, `seaborn`, `wordcloud`
- **Feature Extraction**: `sklearn`, `gensim`

---

## 🚀 How to Use

1. **Install dependencies**:  
   ```bash
   pip install pandas numpy matplotlib seaborn wordcloud nltk spacy textblob scikit-learn gensim
   python -m spacy download en_core_web_sm
