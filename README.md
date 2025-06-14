
# 🧠 IntelliSummarizer: Context-Aware Multi-Domain Text Summarization using NLP + Transformers

> A production-ready NLP project combining extractive and abstractive summarization with state-of-the-art transformers (BART, T5) — built for real-world document understanding.

---

## 📌 Project Overview

**IntelliSummarizer** is a robust, intelligent text summarization system designed to condense long documents into coherent, context-preserving summaries. It supports domain-specific customization (news, legal, blogs, etc.), summary length control, and multiple summarization strategies.

> This project was developed as part of my Master's application portfolio for **AI and Data Science**, showcasing my skills in NLP, transformer models, and full ML pipeline development.

---

## 🚀 Demo

🔗 [Try the Streamlit Web App (if deployed)](https://your-streamlit-link)

📓 Or run the notebooks in [Google Colab](https://colab.research.google.com/)

---

## 🔍 Features

✅ Abstractive summarization using **BART / T5**  
✅ Extractive summarization using **TextRank / BertSum**  
✅ Hybrid summarization mode (combine both types)  
✅ Support for **custom summary lengths**  
✅ Built-in **evaluation metrics**: ROUGE, BERTScore  
✅ Easy-to-use **Streamlit interface** for web demo  
✅ Modular codebase — ready for deployment or research

---

## 🧱 Project Structure

```
intelli-summarizer/
├── data/                         # Sample input files
├── notebooks/                   # Development notebooks (EDA, models, evaluation)
├── utils/                       # Reusable preprocessing and evaluation functions
├── models/                      # Saved fine-tuned models (if any)
├── app/                         # Streamlit UI
├── requirements.txt             # All Python dependencies
├── README.md                    # This file
└── main.py                      # CLI entry point
```

---

## 📊 Technologies Used

| Area              | Tool/Library                     |
|-------------------|----------------------------------|
| Language Models   | `transformers` (BART, T5)        |
| Preprocessing     | `NLTK`, `spaCy`, `re`            |
| Evaluation        | `ROUGE`, `BLEU`, `BERTScore`     |
| Interface         | `Streamlit`                      |
| Dataset Support   | `CNN/DM`, `XSum`, Custom .txt    |
| Dev Environment   | `Google Colab`, `GitHub`         |

---

## 📓 Notebooks

| Notebook                         | Purpose                                 |
|----------------------------------|-----------------------------------------|
| `1_EDA_and_Cleanup.ipynb`        | Clean and analyze raw text              |
| `2_Extractive_Summarization.ipynb` | Implement TextRank-style summarizer   |
| `3_Abstractive_Summarization.ipynb` | Fine-tune or use pre-trained BART/T5 |
| `4_Model_Evaluation.ipynb`       | Compute ROUGE, BERTScore, BLEU          |
| `5_App_Integration_Streamlit.ipynb` | Preview Streamlit interface setup     |

---

## 📈 Evaluation Metrics

- **ROUGE-1, ROUGE-2, ROUGE-L**
- **BERTScore**: Semantic similarity of generated summaries
- **BLEU**: Precision of n-gram overlap

All scores are automatically reported and visualized.

---

## 📥 How to Run

### 🔧 Local Setup (Python 3.8+)

```bash
git clone https://github.com/nrjunejo/intelli-summarizer.git
cd intelli-summarizer
pip install -r requirements.txt
python app/streamlit_app.py
```

### 📓 Google Colab

- Open `notebooks/` directory
- Run step-by-step in Colab (no GPU needed for extractive, GPU suggested for abstractive)

---

## 🧪 Sample Output

**Input:**  
> "The government of Canada announced a new policy to curb emissions in the automotive sector..."

**Generated Summary:**  
> "Canada introduced new environmental regulations aimed at reducing car emissions."

---

## 📚 Use Cases

- News summarization
- Legal document condensation
- Scientific abstract generation
- Blog and content compression
- Assistive AI for reading-disabled users

---

## 🎓 Academic Note

This project is part of my **Master’s admission portfolio** for AI & Data Science. It demonstrates:
- Deep understanding of NLP pipelines
- Practical use of transformer architectures
- Evaluation, optimization, and deployment of NLP systems
- Full-stack data science ability from data prep to UI delivery

---

## 🤝 Acknowledgements

- HuggingFace Transformers
- ROUGE/BERTScore teams
- Streamlit community

---

## 📬 Contact

> Built by **Noorullah Junejo**  
> 🎓 CSIT Graduate 
> 📧 noorullah.data@gmail.com  
> 🔗 [LinkedIn](https://linkedin.com/in/nrjunejo) | [GitHub](https://github.com/nrjunejo)

---

⭐ If you found this project useful, give it a star!
