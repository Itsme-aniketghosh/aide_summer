# Lab 10: Context Engineering - (Graph)RAGged LLMs - Lecture Guide

**This lab explores RAG, knowledge graphs, and GraphRAG for philosophy research using a hands-on, fill-in-the-blank notebook.**

## 🚀 Quick Access
- **[Lab10_(Graph)RAGged_LLMs.ipynb](Scripts/Lab10_(Graph)RAGged_LLMs.ipynb)** ← _Local notebook_
- **[☁️ Google Colab Version](https://colab.research.google.com/drive/1fsHOrJtxJhk_3iaYObLFCEiodwHosluZ?usp=sharing)** ← _Run in browser_

## Table of Contents
1. [Pre-Lab Learning](#pre-lab-learning)
2. [Lab Schedule](#lab-schedule)
3. [Learning Objectives](#learning-objectives)
4. [Key Concepts](#key-concepts)
5. [Quick Links](#quick-links)

---

## 🧠 Lab 10 Notebook Summary

This lab is a hands-on, student-friendly exploration of Retrieval-Augmented Generation (RAG) and knowledge graphs for philosophy research. You will:
- Compare three approaches: **Plain LLM**, **RAG**, and **GraphRAG**
- Use a real dataset of 3,776 philosophy papers
- Work in a **fill-in-the-blank** coding style (minimal typing)
- See how different approaches yield different answers to the same philosophical question
- Build and explore a simple knowledge graph
- Learn about model selection and fallback mechanisms

---

## Pre-Lab Learning (30 minutes)
### Materials:
1. **Vector Databases Foundation** (15 minutes)
   - [What is a Vector Database? (Pinecone)](https://www.pinecone.io/learn/vector-database/) - Industry overview (10 min read)
   - [What is a Knowledge Graph? (YouTube)](https://www.youtube.com/watch?v=y7sXDpffzQQ) - Visual intro (6 min)

2. **RAG Concepts** (15 minutes)
   - [RAG vs. GraphRAG (YouTube)](https://www.youtube.com/watch?v=Aw7iQjKAX2k) - Quick comparison (5 min)
   - [📁 Preview the Lab Notebook](https://colab.research.google.com/drive/1fsHOrJtxJhk_3iaYObLFCEiodwHosluZ?usp=sharing) - Skim the workflow (10 min)

## Lab Schedule (115 minutes)

| Section | Time | Focus |
|---------|------|-------|
| Setup | 5-8 min | Install packages, API setup ([Colab Link](https://colab.research.google.com/drive/1fsHOrJtxJhk_3iaYObLFCEiodwHosluZ?usp=sharing)) |
| Dataset Loading | 8-10 min | Explore philosophy papers |
| Plain LLM | 8-12 min | Simple API calls, model comparison |
| RAG System | 15-20 min | Vector search, context injection |
| Knowledge Graphs | 12-15 min | Triplets, graph building |
| GraphRAG | 10-15 min | Combined graph + retrieval |
| Three-way Comparison | 15-20 min | See all approaches on same question |
| Reflection & Discussion | 8-10 min | Decision frameworks, next steps |

_Note: The notebook uses a fill-in-the-blank coding style and requires only minimal Python knowledge._

## Learning Objectives
- Understand the difference between Plain LLM, RAG, and GraphRAG approaches
- Learn how vector databases enable semantic search
- Build and interpret simple knowledge graphs
- Practice model selection and fallback for robust AI research
- Compare and reflect on the strengths of each approach for philosophical research

## Key Concepts
| Concept | Description | Application |
|---------|-------------|-------------|
| **RAG** | Retrieval-Augmented Generation | Enhanced LLMs with external data |
| **Vector Database** | Storing embeddings for retrieval | Fast document search |
| **Context Injection** | Supplying relevant info to LLMs | Improved answers |
| **Knowledge Graph** | Network of facts/triplets | Discovering relationships |
| **GraphRAG** | RAG + Knowledge Graph | Broader, more connected answers |
| **Model Fallback** | Try multiple models if one fails | Robust, reliable results |

## Quick Links

### 📚 Lab Materials
| Resource | Description | Format |
|----------|-------------|---------|
| [Lab10_(Graph)RAGged_LLMs.ipynb](Scripts/Lab10_(Graph)RAGged_LLMs.ipynb) | **Main lab notebook** | Jupyter Notebook |
| [☁️ Google Colab Version](https://colab.research.google.com/drive/1fsHOrJtxJhk_3iaYObLFCEiodwHosluZ?usp=sharing) | **Run notebook in browser** | Google Colab |

### 🔗 Key Resources
| Resource | Description | Format |
|----------|-------------|---------|
| [What is a Vector Database? (Pinecone)](https://www.pinecone.io/learn/vector-database/) | Vector database fundamentals | Article |
| [What is a Knowledge Graph? (Stanford)](https://ai.stanford.edu/blog/introduction-to-knowledge-graphs/) | Knowledge graph introduction | Article |
| [What is FAISS? (Pinecone Blog)](https://www.pinecone.io/learn/faiss/) | Vector similarity search tool | Article |
| [Vector Database by Hand Exercise](https://www.byhand.ai/p/vector-database-spreadsheet?utm_source=profile&utm_medium=reader2) | Hands-on practice | Interactive | 

### Connection to Previous Labs:
This final lab integrates knowledge from:
- **Lab 7**: Transformer architecture and embeddings foundation
- **Lab 8**: Hugging Face model usage and capabilities
- **Lab 9**: API integration and prompt engineering
- **Lab 10**: Advanced context engineering with RAG and knowledge graphs

## Navigation
**Previous Lab:** [← Lab 9 - Prompt Engineering - LLMs with APIs](../Lab09-Prompt%20Engineering-LLMs_with_APIs/Lab09-lecture-guide.md)  
**Course Overview:** [← Back to Main Course](../README.md) 