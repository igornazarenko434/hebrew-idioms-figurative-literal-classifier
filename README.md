# Hebrew Figurative vs. Literal Classification

## 📌 Project Overview
This project focuses on **classifying Hebrew idiomatic expressions** as **figurative** or **literal** based on their sentence context.  
We created a balanced dataset of over 1000 manually labeled sentences and fine-tuned multiple **transformer-based NLP models** to evaluate performance.

---

## 🗂 Dataset
- **Language:** Hebrew  
- **Expressions:** 41 idiomatic phrases, each in literal and figurative contexts  
- **Samples:** 15 sentences per label per expression (balanced)  
- **Source:** Manually curated and annotated for research purposes

---

## ⚙️ Models & Methods
- **Transformers:** XLM-RoBERTa,AlephBERT, AlephBERTGimmel, mBERT, DictaBERT
- Fine-tuning using Hugging Face Transformers  
- Train/validation/test split with stratification  
- Evaluation with **accuracy, F1-score, confusion matrices, and embedding visualization (t-SNE)**

---

## 📊 Results (Summary)
- **Best Model:** AlephBERTGimmel  
- **Key Insight:** Hebrew-specific models consistently outperformed multilingual models  
- **Analysis:** Attention visualizations confirmed better contextual handling of idiomatic cues

## 📄 Read the full report
For detailed methodology, experiments, and analysis, see the Final Project Report (pdf) attached as part of the repository.


## 👥 Collaboration
This project was developed in collaboration with
Yuval Amit – co-author of the original implementation and joint contributor to dataset creation, model fine-tuning, and analysis.

Original repository: [(https://github.com/igornazarenko434/hebrew-idioms-figurative-literal-classifier/edit/main/README.md)]


