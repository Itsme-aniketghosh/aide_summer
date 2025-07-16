# Lab 9: LLMs with RAG - Lecture Guide

## 🚀 Quick Access
- **[Lab 9 Colab Notebook](https://colab.research.google.com/drive/1Vf3h65H5BwOwkd8cdXW6QtdBGI_TbJ_h?usp=sharing)**  ← _Open this for all in-class work_

## Table of Contents
1. [Pre-Lab Learning](#pre-lab-learning)
2. [Lab Schedule](#lab-schedule)
3. [Learning Objectives](#learning-objectives)
4. [Key Concepts](#key-concepts)
5. [Quick Links](#quick-links)

---

## 🧠 Lab 9 Notebook Summary

This lab is a hands-on, student-friendly exploration of Retrieval-Augmented Generation (RAG) and knowledge graphs for philosophy research. You will:
- Compare three approaches: **Plain LLM**, **RAG**, and **GraphRAG**
- Use a real dataset of 3,776 philosophy papers
- Work in a **fill-in-the-blank** coding style (minimal typing)
- See how different approaches yield different answers to the same philosophical question
- Build and explore a simple knowledge graph
- Learn about model selection and fallback mechanisms

### Notebook Structure & Time Guide
| Section | Time | Focus |
|---------|------|-------|
| Setup | 5-8 min | Install packages, API setup |
| Dataset Loading | 8-10 min | Explore philosophy papers |
| Plain LLM | 8-12 min | Simple API calls, model comparison |
| RAG System | 15-20 min | Vector search, context injection |
| Knowledge Graphs | 12-15 min | Triplets, graph building |
| GraphRAG | 10-15 min | Combined graph + retrieval |
| Three-way Comparison | 15-20 min | See all approaches on same question |
| Reflection & Discussion | 8-10 min | Decision frameworks, next steps |

---

## Pre-Lab Learning (45 minutes)
### Required Materials:
1. **Reading:**
   - [Pinecone: What is a Vector Database?](https://www.pinecone.io/learn/vector-database/)  
     *Why:* Industry perspective, concise and clear.
2. **Video:** 
   - [YouTube: RAG Explained, 45 mins](https://www.youtube.com/watch?v=PrYuqtT43BE)  
     *Why:* Short, accessible video to introduce the RAG concept.
3. **Hands-on:**
   - [Vector Database Spreadsheet (Excel)](https://www.byhand.ai/p/vector-database-spreadsheet?utm_source=profile&utm_medium=reader2)  
     *Why:* In-lab or homework exercise to reinforce how vector search works.

## In-Lab Exploration
- [Deep Dive into Vector Databases by Hand (TDS)](https://towardsdatascience.com/deep-dive-into-vector-databases-by-hand-e9ab71f54f80/)
  *Note:* We will explore this resource together in lab, working through the concepts and visuals as a group.
- [Walkthrough: Vector Databases by Hand](https://www.byhand.ai/p/14-can-you-calculate-a-vector-database)  
     *Why:* for self-check after the exercise.

## Lab Schedule
- (To be added)

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
| Resource | Description | Format |
|----------|-------------|---------|
| [Lab 9 Colab Notebook](https://colab.research.google.com/drive/1Vf3h65H5BwOwkd8cdXW6QtdBGI_TbJ_h?usp=sharing) | **Main lab notebook** | Google Colab |
| [Deep Dive into Vector Databases by Hand (TDS)](https://towardsdatascience.com/deep-dive-into-vector-databases-by-hand-e9ab71f54f80/) | Conceptual intro | Article |
| [Beginner's Guide to Vector Databases (byhand.ai)](https://www.byhand.ai/p/beginners-guide-to-vector-databases) | Practical guide | Article |
| [Pinecone: What is a Vector Database?](https://www.pinecone.io/learn/vector-database/) | Industry overview | Article |
| [RAG Explained (YouTube)](https://www.youtube.com/watch?v=PrYuqtT43BE) | RAG intro | Video |
| [Vector Database Spreadsheet (Excel)](https://www.byhand.ai/p/vector-database-spreadsheet?utm_source=profile&utm_medium=reader2) | Hands-on | Spreadsheet |
| [Solutions: Can You Calculate a Vector Database?](https://www.byhand.ai/p/14-can-you-calculate-a-vector-database) | Exercise solution | Article |

## Navigation
**Previous Lab:** [← Lab 8 - LLMs with API](../lab8-commercial-LLMs/lab8-lecture-guide.md)  
**Next Lab:** [Lab 10 - LLM Showcase - Interface →](../lab10-llm-showcase/lab10-lecture-guide.md) 