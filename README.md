# 📝 Paraphrase Mining using Sentence Transformers

## 📌 Overview

This project demonstrates **Paraphrase Mining** using **Sentence Transformers**, a powerful NLP framework for generating semantic sentence embeddings. The notebook identifies sentences that convey similar meanings, computes semantic similarity scores, and detects outlier sentences within a corpus using cosine similarity.

The project showcases how transformer-based embeddings can be used for semantic text comparison, duplicate detection, clustering, and information retrieval tasks.

---

## 🚀 Features

* Generate sentence embeddings using pre-trained Sentence Transformer models.
* Calculate semantic similarity using cosine similarity.
* Perform paraphrase mining to identify semantically similar sentence pairs.
* Detect outlier sentences based on average similarity scores.
* Compare different Sentence Transformer models for semantic understanding.
* Demonstrates multilingual embedding support.

---

## 🛠️ Technologies Used

* Python
* Sentence Transformers
* Hugging Face Transformers
* PyTorch
* NumPy

---

## 📚 Models Used

* **all-MiniLM-L6-v2**

  * Lightweight and fast.
  * Suitable for semantic similarity and paraphrase detection.

* **distiluse-base-multilingual-cased-v1**

  * Supports multiple languages.
  * Generates multilingual sentence embeddings.

---

## 📂 Project Workflow

1. Install required libraries.
2. Load a pre-trained Sentence Transformer model.
3. Encode sentences into dense vector embeddings.
4. Compute cosine similarity between sentence embeddings.
5. Perform paraphrase mining to identify similar sentence pairs.
6. Detect outlier sentences based on semantic similarity scores.
7. Analyze and interpret the results.

---

## 📈 Applications

* Duplicate Question Detection
* Semantic Search
* Text Clustering
* Document Similarity
* Chatbots & Virtual Assistants
* Recommendation Systems
* Information Retrieval
* Plagiarism Detection

---

## 📦 Installation

```bash
pip install sentence-transformers
pip install torch
```

---

## ▶️ Usage

1. Clone this repository.

```bash
git clone https://github.com/your-username/paraphrase-mining.git
```

2. Open the Jupyter Notebook.

```bash
jupyter notebook
```

3. Run all cells to:

   * Generate sentence embeddings
   * Compute similarity scores
   * Mine paraphrases
   * Detect outlier sentences

---

## 📊 Sample Output

* Similar sentence pairs with cosine similarity scores.
* Ranked paraphrase candidates.
* Identification of semantically unrelated (outlier) sentences.

---

## 🎯 Learning Outcomes

This project demonstrates how modern transformer-based language models can capture semantic meaning beyond keyword matching. It provides practical experience with sentence embeddings, cosine similarity, and paraphrase mining—fundamental techniques in Natural Language Processing (NLP).

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is intended for educational and learning purposes.
