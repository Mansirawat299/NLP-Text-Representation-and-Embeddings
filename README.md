# Natural Language Processing Laboratory Assignment2
## Text Representation and Word Embeddings

This repository contains the solution for the **Natural Language Processing (NLP)** assignment based on **Unit 2: Text Representation**. The notebook implements various traditional and modern text representation techniques, including word embeddings and visualization.

---

## 📘 Assignment Overview

### **Task 1: Text Representation using Traditional Methods**

**Objective:**  
Understand and implement different vectorization techniques for text data.

**Techniques Implemented:**  
- **Count Vectorization (Bag of Words)**
- **TF-IDF (Term Frequency – Inverse Document Frequency)**
- **N-grams (Bi-grams / Tri-grams)**

**Workflow:**
1. A small text dataset (e.g., news headlines or reviews) is used.
2. Text is preprocessed and vectorized using the above techniques.
3. Shapes and sample features of the resulting vectors are displayed.
4. A comparison of the vectorization methods and their impact on feature space is discussed.

---

### **Task 2: Word Embeddings and Visualization**

**Objective:**  
Explore semantic relationships between words using pretrained embeddings.

**Steps:**
1. Load a **pre-trained word embedding model** (Word2Vec / GloVe).
2. Select a set of words (e.g., *king*, *queen*, *man*, *woman*, *apple*, *banana*).
3. Calculate cosine similarity to find the most similar words.
4. Visualize embeddings using **t-SNE** / **PCA** in 2D space.
5. Interpret semantic clustering patterns.

---

## 🛠️ Libraries Used

- `scikit-learn` (CountVectorizer, TfidfVectorizer)
- `gensim` (Word2Vec embeddings)
- `spaCy` (optional, for GloVe embeddings)
- `matplotlib`, `seaborn` (visualization)
- `numpy`, `pandas`
- `sklearn.manifold` or `sklearn.decomposition` (t-SNE/PCA)

---

## 💡 Output Highlights

- Comparison of vector dimensions across techniques
- Top similar words based on cosine similarity
- 2D scatter plot of word embeddings
- Semantic clustering insights

---

## 📂 Repository Structure

