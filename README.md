# Multilabel-News-Article-Classification-Entity-Aware-Summarisation-Engine
An end-to-end News Intelligence Engine utilizing Deep Learning for multilabel classification and entity-aware summarization. Features a custom misinformation risk-scoring heuristic, spaCy-driven NER visualization, and a production-ready Streamlit dashboard. Built with HuggingFace Transformers (RoBERTa, BART) and deployed via secure Ngrok tunnels.

# 📰 News Intelligence Engine
**An End-to-End Deep Learning Pipeline for Article Classification, Risk Analysis, and Summarization.**

## 🚀 Project Overview
The News Intelligence Engine is a sophisticated NLP platform designed to process raw news data into actionable insights. It combines state-of-the-art transformer models with custom linguistic heuristics to classify topics, extract key entities, detect misinformation risks, and generate concise summaries.

## ✨ Key Features
- **Multilabel Classification:** Uses fine-tuned **RoBERTa** models to categorize news into 10 distinct sectors (Politics, Tech, Sports, etc.).
- **Abstractive Summarization:** Employs **BART-base** to generate grammatically correct, entity-aware 3-sentence summaries.
- **Misinformation Risk Engine:** A custom heuristic engine that calculates factual risk, emotional density, and quote-missing metrics.
- **NER Mapping:** Real-time extraction and color-coded visualization of Organizations, Persons, and Locations using **spaCy**.
- **Cloud Deployment:** Integrated with **Streamlit** and **Ngrok** for a live, interactive web-based dashboard.

## 🛠️ Tech Stack
- **Languages:** Python
- **DL Frameworks:** PyTorch, HuggingFace Transformers
- **NLP Libraries:** spaCy, NLTK, Regular Expressions
- **Interface:** Streamlit
- **Infrastructure:** Google Colab, Ngrok, Google Drive (Artifact Storage)

## 📁 Repository Structure
- `app/app.py`: Main Streamlit application script.
- `notebooks/`: Research and training notebooks (Classification, Summarization).
- `artifacts/`: Model checkpoints and weight configurations.
- `requirements.txt`: Necessary libraries for deployment.

## 👷 Author
**Ganesh Kanagaraj**
- LinkedIn: [www.linkedin.com/in/ganesan-kanagaraj-b36759171]

