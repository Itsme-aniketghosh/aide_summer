# AIDE Summer Machine Learning and Python Programming Bootcamp 2025

This repository contains comprehensive materials for the AIDE Summer Machine Learning and Python Programming Sessions, designed to provide hands-on experience with Python programming, machine learning concepts, and ethical AI considerations.

## Course Overview

A multi-session intensive bootcamp covering Python fundamentals through advanced machine learning concepts, culminating in modern LLM use cases and interface design. Each lab includes pre-lab learning materials, structured lectures, and hands-on exercises with both local Jupyter notebooks and Google Colab integration.

## Course Structure

### [Lab 01: Intro to Programming and Python](Lab01-intro-programming-python/)
**Duration:** 120 minutes | **Pre-Lab:** 2 hr 20 minutes

**Key Topics:**
- Python fundamentals: variables, strings, data structures
- Control flow and loops
- File operations and data parsing
- **Main Exercise:** [Python_Fundamentals_Complete.ipynb](Lab01-intro-programming-python/exercises/Python_Fundamentals_Complete.ipynb) - Comprehensive notebook with mini-project

### [Lab 02: Classification and Working with Data](Lab02-classification-data/)
**Duration:** 120 minutes | **Pre-Lab:** 1 hr 30 minutes

**Key Topics:**
- Data manipulation with Pandas
- Linear and logistic regression
- Decision trees and classification
- **Exercises:** 6 focused notebooks covering data loading, selection, and ML algorithms

### [Lab 03: ML Fairness and Bias](Lab03-ml-fairness/)
**Duration:** 120 minutes | **Pre-Lab:** Reading assignments

**Key Topics:**
- Algorithmic fairness and bias detection
- COMPAS dataset analysis
- What-If Tool exploration
- Ethical considerations in ML

### [Lab 04: Advanced Trees and Fairness Tools](Lab04-advanced-trees/)
**Duration:** 120 minutes

**Key Topics:**
- Advanced decision tree techniques
- FairLearn library integration
- Bias mitigation strategies
- **Exercises:** COMPAS analysis with solutions

### [Lab 05: Differential Privacy](Lab05-differential-privacy/)
**Duration:** 120 minutes | **Pre-Lab:** Programming Differential Privacy Ch. 1

**Key Topics:**
- Privacy-preserving machine learning
- De-identification attacks
- Differential privacy implementation
- **Exercises:** Census and sleep data privacy analysis

### [Lab 06: Neural Networks and LLM Concepts](Lab06-nn-transformers/)
**Duration:** 120 minutes | **Pre-Lab:** 2 hr 45 minutes

**Key Topics:**
- Perceptron and neural network fundamentals
- Transformer architecture by hand
- Attention mechanisms
- Mathematical foundations of modern AI

### [Lab 07: Discovering What LLMs Can Do – 10 Core Capabilities](Lab07-LLMs_capabilities/)
**Duration:** 120 minutes | **Pre-Lab:** 30 minutes

**Key Topics:**
- 10 fundamental LLM capabilities: classification, NER, zero-shot, QA, summarization, similarity, generation, translation, chat, text-to-image
- Using Hugging Face pipelines for each capability
- Building a research assistant by combining capabilities
- **Main Exercise:** [Lab 7 Colab: LLM Capabilities](https://colab.research.google.com/drive/1qHTo8fC5L4895GQsZr4itCR7KHHHxEX0?usp=sharing)

### [Lab 08: LLMs with API](Lab08-LLMs_with_APIs/)
**Duration:** 120 minutes | **Pre-Lab:** 45 minutes

**Key Topics:**
- Using LLM APIs for scalable NLP (HuggingFace, OpenRouter)
- API authentication and security in Colab
- Prompt engineering and model comparison
- Batch processing and real data upload
- **Main Exercise:** [Lab 8 Notebook](Lab08-LLMs_with_APIs/Exercises/Lab08_LLMwAPIs.ipynb)

### [Lab 09: LLMs with RAG, Vector Databases, and Knowledge Graphs](Lab09-RAGged-LLMs/)
**Duration:** 120 minutes | **Pre-Lab:** 45 minutes

**Key Topics:**
- Retrieval-Augmented Generation (RAG)
- Vector databases and context injection
- Knowledge graphs and GraphRAG
- Model selection and fallback
- Fill-in-the-blank, student-friendly coding
- **Main Exercise:** [Lab 9 Colab Notebook](https://colab.research.google.com/drive/1Vf3h65H5BwOwkd8cdXW6QtdBGI_TbJ_h?usp=sharing)

### [Lab 10: LLM Showcase - Interface](Lab10-llm-showcase/)
**Duration:** 120 minutes | **Pre-Lab:** TBD

**Key Topics:**
- Interface design for LLM applications
- Demo and presentation of LLM projects
- Integration and end-to-end solutions
- **Main Exercise:** (To be added)

## Quick Navigation

| Lab | Topic | Duration | Main Exercises |
|-----|-------|----------|----------------|
| [Lab 01](Lab01-intro-programming-python/) | Python Fundamentals | 120 min | Python_Fundamentals_Complete.ipynb |
| [Lab 02](Lab02-classification-data/) | Classification & Data | 120 min | 6 focused ML notebooks |
| [Lab 03](Lab03-ml-fairness/) | ML Fairness & Bias | 120 min | What-If Tool exploration |
| [Lab 04](Lab04-advanced-trees/) | Advanced Trees | 120 min | COMPAS exercises & solutions |
| [Lab 05](Lab05-differential-privacy/) | Differential Privacy | 120 min | Census & sleep data analysis |
| [Lab 06](Lab06-nn-transformers/) | Neural Networks & LLMs | 120 min | Hand calculations & theory |
| [Lab 07](Lab07-LLMs_capabilities/) | 10 LLM Capabilities & Huggingface | 120 min | [LLM Capabilities Colab notebook](https://colab.research.google.com/drive/1qHTo8fC5L4895GQsZr4itCR7KHHHxEX0?usp=sharing) |
| [Lab 08](Lab08-LLMs_with_APIs/) | LLMs with API | 120 min | [Lab 8 Notebook](Lab08-LLMs_with_APIs/Exercises/Lab08_LLMwAPIs.ipynb) |
| [Lab 09](Lab09-RAGged-LLMs/) | LLMs with RAG, Vector DBs, GraphRAG | 120 min | [Lab 9 Colab Notebook](https://colab.research.google.com/drive/1Vf3h65H5BwOwkd8cdXW6QtdBGI_TbJ_h?usp=sharing) |
| [Lab 10](Lab10-llm-showcase/) | LLM Showcase - Interface | 120 min | (To be added) |

## Repository Structure

Each lab folder contains:
- **`Lab##-lecture-guide.md`** – Comprehensive instructor guides with navigation, schedules, and resources
- **`exercises/`** – Hands-on coding exercises in Jupyter notebook format (where applicable)
- **`tutorials/`** – Guides, worksheets, and additional materials

### Key Features
- **🔗 Consistent Navigation:** All lecture guides include course breadcrumbs and cross-references
- **📚 Quick Links Tables:** Easy access to both local files and Google Colab versions
- **🎯 Learning Objectives:** Clear outcomes defined for each session
- **📋 Key Concepts Tables:** Structured reference materials
- **⏱️ Time Management:** Detailed scheduling with pre-lab learning requirements

## Getting Started

### For Local Use:
1. **Clone the repository:**
   ```bash
   git clone [repository-url]
   cd aide_summer
   ```

2. **Choose your preferred environment:**
   - **Local:** Open `.ipynb` files in Jupyter Lab/Notebook
   - **Cloud:** Use Google Colab links provided in each lecture guide

3. **Follow the sequence:**
   - Each `Lab##-lecture-guide.md` contains detailed session plans
   - Complete pre-lab materials (listed in each lecture guide)
   - Attend sessions
   - Work through exercises
   - Apply concepts in the final showcase

## Technical Requirements
- **Python 3.7+** with standard data science libraries (pandas, numpy, scikit-learn)
- **Jupyter Lab/Notebook** for local development
- **Google Account** for Colab access
- **Hugging Face Account** (Lab 07+)

## External Resources and Links

All external links have been verified and updated, including:
- Google Colab integration for all major exercises
- Current Hugging Face and ML platform references

## Quick Links: External Resources

- [FAISS: Facebook AI Similarity Search (Official)](https://faiss.ai/) — Official site and docs for FAISS
- [What is FAISS? (Pinecone Blog)](https://www.pinecone.io/learn/faiss/) — Beginner-friendly intro to FAISS
- [NetworkX: Network Analysis in Python (Official)](https://networkx.org/) — Official docs and tutorials for NetworkX
- [NetworkX Tutorial (DataCamp)](https://www.datacamp.com/tutorial/networkx-python-graph-tutorial) — Step-by-step beginner tutorial
- [Beginner's Guide to Vector Databases (byhand.ai)](https://www.byhand.ai/p/beginners-guide-to-vector-databases) — Practical guide
- [Pinecone: What is a Vector Database?](https://www.pinecone.io/learn/vector-database/) — Industry overview
- [What is a Knowledge Graph? (Stanford)](https://ai.stanford.edu/blog/introduction-to-knowledge-graphs/) — Intro to knowledge graphs
- [GraphRAG: Enhancing Retrieval Augmented Generation with Knowledge Graphs (Medium)](https://medium.com/@divyanshbhatiajm19/graphrag-enhancing-retrieval-augmented-generation-with-knowledge-graphs-fc15c3901414) — Intro to GraphRAG
- [The GraphRAG Process by Microsoft](https://microsoft.github.io/graphrag/) — GraphRAG applications
- [RAG Explained (YouTube)](https://www.youtube.com/watch?v=PrYuqtT43BE) — RAG intro
- [What is a Knowledge Graph? (YouTube, 6 min)](https://www.youtube.com/watch?v=y7sXDpffzQQ) — Visual intro to knowledge graphs
- [RAG vs. GraphRAG (YouTube, 5 min)](https://www.youtube.com/watch?v=Aw7iQjKAX2k) — Quick intro to RAG comparisons


