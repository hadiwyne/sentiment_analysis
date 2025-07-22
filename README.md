# EPUB Text Analysis in Google Colab

This notebook allows you to upload an EPUB file and automatically perform **text extraction**, **cleaning**, **visualization**, **sentiment analysis**, **summarization**, and **classification** — all in one place using Google Colab.

---

## Features

- Parse EPUB Files using `ebooklib` and `BeautifulSoup`  
- Generate Word Clouds of the most frequent words  
- Sentiment Analysis (VADER-based sentence-level scoring)  
- Pie Charts to visualize positive, negative, and neutral sentiment distribution  
- Train ML Models (Logistic Regression, Random Forest, Naive Bayes) on sentence sentiments  
- Extractive Summarization using `spaCy`  
- LLM-Based Summarization using OpenRouter’s free models (like GPT-3.5)  
- Fully executable in **Google Colab** with minimal setup  

---

## How to Use

### Open in Google Colab  
Upload the notebook and run each cell step-by-step.

### Install Dependencies  
The notebook requires the following packages:

```
ebooklib
bs4
nltk
wordcloud
spacy
scikit-learn
seaborn
````

### Upload an EPUB File

A simple upload widget lets you load your own book for analysis.

### View Outputs

* Word Cloud image
* Sentiment distribution pie chart
* Summaries (LLM and Extractive)
* Accuracy, confusion matrix, and classification reports for 3 ML models

---

## OpenRouter API Key

To use LLM-based summarization, you'll need a **free API key** from [OpenRouter](https://openrouter.ai/).
Replace the placeholder string in the notebook:

```
api_key = ""
```

---

## Tech Stack

* Python
* Google Colab
* Natural Language Toolkit (NLTK)
* spaCy
* scikit-learn
* Matplotlib / Seaborn
* WordCloud
* OpenRouter LLM API

---
