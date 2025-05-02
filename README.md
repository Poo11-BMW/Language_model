# 🌍 Language Identification from Text using BERT and Machine Learning Models

This project explores the development of robust models for automatic language identification using traditional and deep learning approaches, culminating in a state-of-the-art fine-tuned **BERT model** that achieved **99.92% accuracy**.

## 🧠 Authors

- **Poojashree Chandrashekar**  
  Dept. of Mathematical Sciences, Stevens Institute of Technology  
  ✉️ poojash@stevens.edu

Published in:  
📘 *International Journal of Progressive Research in Engineering Management and Science (IJPREMS)*  
📅 February 2025 | 🧾 Vol. 05, Issue 02 | 📈 Impact Factor: 7.001  
🔗 [Europarl Dataset on Kaggle](https://www.kaggle.com/datasets/dionafegnem/europarl-parallel-corpus-10962106)

---

## 📄 Abstract

This study presents a comparative analysis of four models—Naive Bayes, Bi-LSTM, CNN, and BERT—on multilingual text data. It demonstrates the superiority of BERT in identifying languages accurately, even in the presence of phonetically similar or code-mixed text. The goal is to support language-aware NLP systems such as translation engines, chatbots, and content filters.

---

## 🧪 Dataset

- **Source**: Europarl Parallel Corpus (Kaggle)
- **Languages**: English, Spanish, Bulgarian, Italian
- **Format**: 19 CSV files of sentence pairs
- **Processing**:
  - Lowercasing and regex cleaning
  - TF-IDF vectorization (top 1000 features for classical models)
  - Length filtering for meaningful inputs

---

## 🔬 Models Compared

| Model      | Accuracy | Precision | Recall | F1-Score |
|------------|----------|-----------|--------|----------|
| Naive Bayes | 56%      | 0.76      | 0.55   | 0.45     |
| Bi-LSTM     | 99.81%   | 0.99      | 0.99   | 0.99     |
| CNN         | 96.50%   | 0.97      | 0.96   | 0.96     |
| **BERT**    | **99.92%** | **0.99** | **0.99** | **0.99** |

> ✅ BERT emerged as the best-performing model due to its multilingual pretraining and self-attention capabilities.

---

## 🧱 BERT Model Highlights

- **Transformer Encoder** with self-attention
- **Multilingual Pre-training** on 100+ languages
- **Fine-Tuned** specifically for language classification task
- Handles **code-mixed** and **short text** sequences with high precision

---

## 🔍 Applications

- Social media language routing
- Multilingual chatbots
- Machine translation pre-processing
- Content moderation

---

## 📝 Citation

```bibtex
@article{poojashree2025languageid,
  author    = {Poojashree Chandrashekar},
  title     = {Language Identification from Text},
  journal   = {International Journal of Progressive Research in Engineering Management and Science (IJPREMS)},
  volume    = {05},
  number    = {02},
  year      = {2025},
  pages     = {460--462},
  doi       = {10.1109/DOCS63458.2024.10704434}
}
