# ✍️ Automated Essay Scoring (Bahasa Indonesia) using IndoSBERT

![Banner](assets/banner.png)

This project builds an **automated essay scoring system** for Indonesian language answers using **IndoSBERT** for semantic similarity measurement.  
The model compares student-written answers against reference answers and predicts a score based on semantic closeness.

---

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat&logo=python&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Transformer-IndoSBERT-orange?style=flat&logo=huggingface)
![Language](https://img.shields.io/badge/Language-Bahasa_Indonesia-red?style=flat)
![Model](https://img.shields.io/badge/Task-Automated_Essay_Scoring-purple?style=flat)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat)

---

## 🎯 Objective

- Predict essay scores for Indonesian student answers
- Compare semantic similarity between student answer and reference key
- Use cosine similarity on sentence embeddings from **IndoSBERT**

---

## 🧠 Approach

- Preprocess text: lowercase, remove stopwords (Bahasa), punctuation, numbers
- Generate sentence embeddings using **sentence-transformers** (`indobert-base-p1`)
- Use cosine similarity to score answers
- Evaluate using MAE, RMSE, and correlation metrics

---

## 📂 Project Structure

```
AutomatedEssay_indoSBERTok.ipynb
Data/
├── Data.xlsx  ← Contains "Answer Key", "Student Answer", and "Score"
assets/
├── aes-indosbert-banner.png
```

---

## 🚀 How to Run

1. Run the notebook in **Google Colab**
2. Mount Google Drive and point to the dataset
3. Preprocess the data
4. Run scoring and evaluation cells

---

## 📊 Evaluation Metrics

- **Cosine Similarity**
- **RMSE** (Root Mean Squared Error)
- **MAE** (Mean Absolute Error)
- **Pearson Correlation** with ground truth scores

---

## 👨‍💻 Author

**Indra Eka Mandriana S.Kom**  
_Natural Language Processing & Language Education Tech Researcher_

---

## ⭐ Found it useful? Star this project on GitHub!
