# application-based-sentiment-project-
used dataset like imdb rotten tomatotes 
# Sentiment-Shift-Analysis

**Sentiment Shift Across Domains: Application of Traditional, Deep Learning, and Transformer Models**

This repository contains code and results for a comparative study of sentiment classification models across multiple Twitter-based domains (political, healthcare, general). The goal is to evaluate model performance in practical application settings and compare traditional machine learning, deep learning, and transformer-based approaches.

---

## Project Overview

Sentiment analysis classifies text as **positive**, **negative**, or **neutral** and is widely used in social media monitoring, customer feedback analysis, healthcare opinion mining, and political trend analysis. This project benchmarks a range of models to see which approaches perform best in real-world scenarios.

**Models included:**
- Logistic Regression (LR)  
- Support Vector Machine (SVM)  
- Random Forest (RF)  
- LSTM  
- BERT  
- DistilBERT  
- RoBERTa

**Datasets:**  
- GOP (political tweets)  
- HCR (healthcare reform tweets)  
- Train (general Twitter dataset)

---

## Key Results

| **Model**               | **Accuracy (%)** | **F1 Score** |
|-------------------------|------------------:|-------------:|
| Logistic Regression (LR)|            88.41  |      —       |
| SVM                     |            88.16  |      —       |
| Random Forest (RF)      |            85.01  |      —       |
| LSTM                    |            86.54  |    86.71    |
| BERT                    |            88.00  |    87.91    |
| DistilBERT              |            88.63  |    88.48    |
| RoBERTa                 |            89.88  |    89.99    |
https://github.com/NitinPandey12465/application-based-sentiment-project-/blob/main/download.png
**Insight:** Transformer models (RoBERTa, DistilBERT, BERT) outperform traditional ML and LSTM on this task. RoBERTa achieves the best balance of accuracy and F1-score.

---

## Quick Start

1. Clone the repo:
```bash
git clone https://github.com/<your-username>/Sentiment-Shift-Analysis.git
cd Sentiment-Shift-Analysis
