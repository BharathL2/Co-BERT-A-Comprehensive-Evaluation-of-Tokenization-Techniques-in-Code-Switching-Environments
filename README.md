# Co-BERT: A Comprehensive Evaluation of Tokenization Techniques in Code-Switching Environments

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository presents the implementation and findings from our research on tokenization techniques for code-mixed Indian languages. We evaluate three tokenization approaches—**Byte Pair Encoding (BPE)**, **WordPiece**, and **SentencePiece**—across three popular code-mixed language pairs: **Tanglish**, **Kanglish**, and **Hinglish**.

---

## 📄 Abstract

Code-mixed languages, which blend two or more languages in a single utterance, introduce unique challenges to NLP systems. Tokenization, a fundamental step in NLP pipelines, must adapt to handle such hybrid linguistic data effectively.

In this study, we conduct a comprehensive evaluation of three tokenization strategies across Tanglish, Kanglish, and Hinglish. Using YouTube transcripts transliterated via **AI4Bharat's Bhashini**, we identify the most effective tokenizer for each language based on validation loss. Our findings provide meaningful insights for improving multilingual NLP applications in code-switched environments.

---

## 📦 Requirements

- Python 3.8+
- PyTorch 1.8+
- Transformers 4.10+
- Pandas
- NumPy
- Matplotlib
- tqdm

Install dependencies:

pip install -r requirements.txt

## 📁 Repository Structure




Clone the repository
git clone [https://github.com/BharathL2/Co-BERT-A-Comprehensive-Evaluation-of-Tokenization-Techniques-in-Code-Switching-Environments]
cd Co-BERT

## 📊 Results Overview

| Tokenizer      | Tanglish | Kanglish | Hinglish |
|----------------|----------|----------|----------|
| **BPE**        | **7.20** | **7.32** | 7.18     |
| **WordPiece**  | 7.43     | 7.42     | **7.06** |
| **SentencePiece** | 7.73  | 7.73     | 7.56     |

**Key Insights:**

- ✅ **WordPiece** performs best for Hinglish.
- ✅ **BPE** achieves the lowest loss for Tanglish and Kanglish.
- ⚠️ **SentencePiece** underperforms consistently across all three languages.

## Contributors
Bharath L

Gopal

Gnanesh A R

Madhan S



