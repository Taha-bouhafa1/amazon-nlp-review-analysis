# Amazon NLP Review Analysis

This repository contains a Natural Language Processing (NLP) pipeline applied to the Amazon Fine Food Reviews dataset. It covers various advanced text analysis tasks including sentiment classification, topic modeling, named entity recognition (NER), and text summarization using traditional and transformer-based methods.

## 📁 Project Structure

* nlp\_task.ipynb – Main Jupyter notebook containing all code and analysis
* README.md – Project overview and instructions
* requirements.txt – Python dependencies for running the notebook

## 🧠 Tasks Performed

1. 🧾 Sentiment Analysis
   Classified reviews as positive, neutral, or negative using logistic regression and evaluated using precision, recall, and F1-score.

2. 📚 Topic Modeling
   Used Latent Dirichlet Allocation (LDA) to uncover key themes and topics from the review corpus.

3. 🏷️ Named Entity Recognition (NER)
   Applied spaCy to extract product names, locations, and organizations from the text. Visualized entities using spaCy’s displaCy tool.

4. 📝 Text Summarization

   * Extractive summarization using NLTK and Gensim.
   * Abstractive summarization using the BART transformer model from Hugging Face 🤗.

## 📊 Dataset

We used the Amazon Fine Food Reviews dataset, which contains 568,454 food product reviews collected over a 10+ year span.
Each review includes metadata such as product/user ID, rating, review text, and a human-written summary.

📎 Dataset source:
🔗 [https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)

## 🛠️ Installation & Usage

To run this notebook on your machine:

1. Clone this repository:

```bash
git clone https://github.com/Taha-bouhafa1/amazon-nlp-review-analysis.git
cd amazon-nlp-review-analysis
```

2. Install dependencies:
   It’s recommended to use a virtual environment:

```bash
pip install -r requirements.txt
```

3. Launch the Jupyter notebook:

```bash
jupyter notebook
```

Then open nlp\_task.ipynb in your browser.

## 📌 Requirements

Main libraries used:

* pandas
* numpy
* matplotlib, seaborn
* scikit-learn
* nltk
* gensim
* spacy
* transformers (Hugging Face 🤗)
* pyLDAvis

Full list is in requirements.txt.

## ✍️ Author

* Taha Bouhafa

