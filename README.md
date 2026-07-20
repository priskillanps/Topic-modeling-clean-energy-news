# Topic Modeling for Clean Energy News using Latent Dirichlet Allocation (LDA)

## Project Overview

This project was developed as my undergraduate thesis at Universitas Gadjah Mada. It aims to analyze large-scale clean energy news articles using Natural Language Processing (NLP) and topic modeling techniques to identify dominant themes and emerging trends in the clean energy sector.

To improve topic quality and interpretability, this project compares two text representation approaches—TF-IDF and KeyBERT—before applying Latent Dirichlet Allocation (LDA).

---

## Objectives

- Identify hidden topics from large-scale clean energy news articles.
- Compare TF-IDF and KeyBERT as feature representation methods for LDA.
- Evaluate topic quality using topic coherence and topic diversity.
- Discover major trends in clean energy discussions.

---

## Dataset

- **Dataset:** Cleantech Media Dataset
- **Source:** Kaggle
- **Language:** English
- **Total Articles:** 20,111
- **Publication Period:** 2022–2024

---

## Technologies Used

- Python
- Pandas
- NLTK
- Gensim
- KeyBERT
- Scikit-learn
- pyLDAvis
- Matplotlib

---

## Methodology

The workflow consists of:

1. Data preprocessing
   - Lowercasing
   - Tokenization
   - Stopword removal
   - Lemmatization

2. Feature representation
   - TF-IDF
   - KeyBERT

3. Topic Modeling
   - Latent Dirichlet Allocation (LDA)

4. Model Evaluation
   - Coherence Score (C_v)
   - Topic Diversity

5. Topic Interpretation and Visualization
   - pyLDAvis
   - Topic keyword analysis

---

## Key Findings

- Successfully analyzed **20,111** clean energy news articles using topic modeling.
- Compared statistical (TF-IDF) and semantic (KeyBERT) feature representations before LDA modeling.
- The KeyBERT-based representation produces the best topic quality at K=6, with a coherence C_v score of 0.6558 and a topic diversity score of 0.9333. Meanwhile, the best TF-IDF-based model is obtained at K=40, with a coherence C_v score of 0.6043 and a topic diversity score of 0.7050. 
- The KeyBERT-based model produced more semantically meaningful and interpretable topics, making it more suitable for thematic analysis despite a lower coherence score.
- The final analysis identified six major clean energy themes:
  - Biofuels and Hydrogen Production
  - Electric Vehicles and Battery Technology
  - Sustainable Industrial Manufacturing
  - Solar Energy Infrastructure
  - Geothermal Energy
  - Solar Cell Technology
