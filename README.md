# Med.AI Recall 💊🔎  
*Alternate Drug Search Engine for Affordable and Accessible Healthcare*

**Med.AI Recall** is an intelligent, user-friendly information retrieval system designed to help patients and caregivers find suitable and affordable alternative medicines—especially when brand names, generics, or exact spellings are unknown. The project leverages modern NLP techniques and biomedical embeddings to optimize drug search queries and enhance medication accessibility.

---

## 🧠 Motivation

In today’s digital healthcare landscape, many users search online for medicines but face issues with:

- Brand vs. generic name confusion
- Misspelled or partial drug names
- Availability and affordability of medications

**Med.AI Recall** addresses these challenges with semantic search and optimized information retrieval to provide accurate drug alternatives in real-world conditions.

---

## 🚀 Features

- 🔍 **Query Optimization**: Handles spelling errors, medical term variations, and brand/generic differences.
- 💬 **Semantic Search**: Uses **TF-IDF**, **Cosine Similarity**, and **BioWordVec** embeddings for accurate retrieval.
- 🧬 **Biomedical Embeddings**: Understands context via domain-specific vectors from **BioWordVec**.
- 📋 **Ranked Results**: Retrieves alternatives based on embedding similarity with a pre-mapped drug dataset.
- 🖥️ **Interactive UI**: Built with **Streamlit** for a simple and clean user experience—no technical skills needed!

---

## 🛠️ Tech Stack

| Component       | Tools / Libraries                        |
|----------------|-------------------------------------------|
| Frontend UI     | Streamlit                                |
| NLP Pipeline    | TF-IDF, Cosine Similarity, BioWordVec     |
| Embeddings      | Biomedical Word Embeddings (BioWordVec)   |
| Language        | Python                                   |
| Dataset         | Pre-mapped drug name and alternative data|

---

## 📁 Project Structure

