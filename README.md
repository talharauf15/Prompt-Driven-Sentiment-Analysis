# Prompt-Driven Sentiment Analysis

This repository explores the use of lightweight NLP models such as DistilBERT, GPT-2, and TinyLlama, with a focus on **prompt engineering** to restrict their functionality to sentiment analysis tasks. By leveraging efficient architectures and carefully designed prompts, the project demonstrates practical and resource-conscious sentiment analysis applications.

---

## Notebooks Overview

### 1. **DistillBert.ipynb**
   - Implements sentiment analysis using the DistilBERT model.
   - Fine-tuned on sentiment-specific datasets to ensure precise results.

### 2. **DistillBert_sst2_eng.ipynb**
   - Sentiment analysis using DistilBERT with the **SST-2 dataset** (Stanford Sentiment Treebank v2).
   - Evaluates model performance with tailored prompts.

### 3. **GPT2.ipynb**
   - Uses GPT-2 with prompt engineering to limit its capabilities to sentiment analysis tasks.
   - Explores zero-shot and few-shot learning for sentiment classification.

### 4. **TinyLlama.ipynb**
   - Custom, lightweight LLaMA-like implementation fine-tuned for sentiment analysis.
   - Demonstrates model performance in constrained environments.

---

## Features
- **Lightweight NLP Models**: Focus on compact, efficient architectures suitable for real-world applications.
- **Prompt Engineering**: Guides general-purpose models to perform sentiment analysis without extensive fine-tuning.
- **Sentiment-Specific Datasets**: Includes datasets like SST-2 to benchmark model performance.

---

## Getting Started

### Prerequisites
- Python 3.8 or later
- Jupyter Notebook
- Libraries like `transformers`, `torch`, `scikit-learn`, etc. (exact requirements listed in `requirements.txt`)

### Installation
Clone  the repository:
```bash
git clone https://github.com/talharauf15/Prompt-Driven-Sentiment-Analysis.git
cd Prompt-Driven-Sentiment-Analysis
```

Install dependencies:

```bash
pip install -r requirements.txt
```
