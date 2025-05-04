
# 🇨🇳 Political Discourse on China in US Presidential Speeches: Topic Modeling and Sentiment Analysis

This repository contains code and analysis for a project that investigates how US presidents have discussed China across time, using a combination of topic modeling and sentiment analysis techniques. The project leverages traditional NLP tools, deep learning models, and large language models (LLMs) to extract and compare themes and emotional tones in presidential speeches.

## 🔍 Project Overview

**Objectives:**
- Identify dominant topics in US presidential discourse on China.
- Compare topic evolution across different presidencies.
- Analyze emotional tone using both lexicon-based and transformer-based sentiment analysis.
- Enhance interpretability with LLM-generated labels and summaries.

## 📁 Project Structure

| File | Description |
|------|-------------|
| `Data Preprocessing and BERTopic Modeling.ipynb` | Preprocesses speech data and applies BERTopic for unsupervised topic modeling with visualization. |
| `Topic Modeling-LDA.ipynb` | Implements traditional LDA modeling for baseline comparison. |
| `Sentiment analysis(NRC Dictionary and Bert).ipynb` | Performs sentiment analysis using NRC lexicon and BERT classifier, comparing results. |
| `LLM-Enhanced Topic-Modeling and Sentiment Analysis.ipynb` | Integrates LLMs to refine topic labeling, summarize cluster meanings, and analyze subtle emotional tones. |

## 🧪 Methods Used

- **Topic Modeling**:
  - BERTopic (Transformer embeddings + K-Means)
  - Latent Dirichlet Allocation (LDA)
- **Sentiment Analysis**:
  - NRC Emotion Lexicon (anger, fear, trust, etc.)
  - Pretrained BERT classifier
- **LLM Enhancements**:
  - Qwen Plus for naming topics, classify emotions, and generating insight-rich explanations

## 📊 Visualizations

- Topic frequency distributions
- Topic evolution over presidents
- Sentiment trends by topic and time
- Co-occurrence networks (LLM-enhanced)

## 🔧 Dependencies

Make sure to install the required packages:
```bash
pip install pandas matplotlib seaborn scikit-learn sentence-transformers bertopic openai
```

Optional:
```bash
pip install transformers torch wordcloud umap-learn
```

## 📎 Data Source

- [Miller Center Presidential Speeches](https://millercenter.org/the-presidency/presidential-speeches)

## ✍️ Citation (if used for research)

> If you use this repository in your research or publication, please cite appropriately or credit the author.
