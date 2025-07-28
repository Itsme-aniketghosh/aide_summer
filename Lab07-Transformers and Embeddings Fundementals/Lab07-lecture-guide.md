# Lab 7: Transformers and Embeddings Fundamentals - Lecture Guide

## Table of Contents
1. [Pre-Lab Learning](#pre-lab-learning)
2. [Lab Schedule](#lab-schedule)
3. [Learning Objectives](#learning-objectives)
4. [Key Concepts](#key-concepts)
5. [Quick Links](#quick-links)

## Pre-Lab Learning (2 hr)
### Materials:
1. **Vector Embeddings Foundation** (30 minutes)
   - [Word Embeddings Explained (StatQuest)](https://www.youtube.com/watch?v=viZrOnJclY0) - 11-minute video on word representations
   - [What are Word Embeddings? (IBM)](https://www.ibm.com/think/topics/word-embeddings) - Technical overview (15 min read)

2. **Transformer Architecture** (60 minutes)
   - [Attention Is All You Need (Paper Summary)](https://www.youtube.com/watch?v=iDulhoQ2pro) - 30-minute explanation of the original paper
   - [📁 Deep Dive into Transformers by Hand](./Tutorials/02.Deep%20Dive%20into%20Transformers%20by%20Hand%20✍︎.md) - Detailed mathematical walkthrough (30 min read)

3. **Attention Mechanisms** (30 minutes)
   - [📁 Keys, Queries, Values Explained](./Tutorials/02.Keys_Queries_Values-attention_mechanisms.md) - Core attention concepts (15 min read)

## Lab Schedule

### Intro: Evolution from Neural Networks to Transformers (10 minutes)
- Recap of Lab 6: Basic neural networks 
- Limitations of traditional architectures for sequence data
- Revolution of attention-based models

### Session 1: Vector Embeddings Deep Dive (30 minutes)
**Understanding How Words Become Numbers**
- **Exercise:** [📁 01.Vectors and Embeddings Exercise](./Exercises/01.Vectors%20and%20Embeddings.pdf)
- **Tutorial:** [📁 Deep Dive into Vector Databases by Hand](./Tutorials/01.Deep%20Dive%20into%20Vector%20Databases%20by%20Hand%20✍︎.md)


### Session 2: Self-Attention Mechanism by Hand (40 minutes)
**The Heart of Transformer Architecture**
- **Primary Exercise:** [📁 03.Self-Attention Exercise](./Exercises/03.Self-Attention%20Exercise.pdf)
- **Tutorial:** [📁 Deep Dive into Self-Attention by Hand](./Tutorials/03.Deep%20Dive%20into%20Self-Attention%20by%20Hand✍︎.md)


### Session 3: Complete Transformer Architecture (25 minutes)
**From Attention to Full Model**
- **Exercise:** [📁 02.Transformer Exercise](./Exercises/02.Transformer%20Exercise.pdf)


## Learning Objectives
By the end of this lab, students will be able to:
- **Embedding Mastery:** Understand how words and concepts are represented as vectors
- **Attention Mechanism:** Calculate self-attention by hand and understand its purpose
- **Transformer Architecture:** Comprehend the complete transformer model structure
- **Query-Key-Value System:** Master the fundamental attention computation framework

## Key Concepts

| Concept | Description | Mathematical Foundation |
|---------|-------------|------------------------|
| **Vector Embeddings** | Dense numerical representations of words/concepts | Continuous vector space mapping |
| **Self-Attention** | Mechanism allowing positions to attend to other positions | Scaled dot-product: Attention(Q,K,V) = softmax(QK^T/√d_k)V |
| **Query, Key, Value** | Three matrices that enable attention computation | Linear projections: Q=XW_Q, K=XW_K, V=XW_V |


## Quick Links

### 📚 Exercise Files
| Exercise | Local File | Focus Area |
|----------|------------|------------|
| Vectors and Embeddings | [📁 01.Vectors and Embeddings.pdf](./Exercises/01.Vectors%20and%20Embeddings.pdf) | Word representations, similarity |
| Transformer Exercise | [📁 02.Transformer Exercise.pdf](./Exercises/02.Transformer%20Exercise.pdf) | Complete architecture walkthrough |
| Self-Attention Exercise | [📁 03.Self-Attention Exercise.pdf](./Exercises/03.Self-Attention%20Exercise.pdf) | Attention mechanism by hand |

### 📖 Tutorial Materials
| Resource | Local File | Online Version | Focus |
|----------|------------|----------------|-------|
| Vector Databases by Hand | [📁 01.Deep Dive into Vector Databases by Hand ✍︎.md](./Tutorials/01.Deep%20Dive%20into%20Vector%20Databases%20by%20Hand%20✍︎.md) | - | Embeddings applications |
| Transformers by Hand | [📁 02.Deep Dive into Transformers by Hand ✍︎.md](./Tutorials/02.Deep%20Dive%20into%20Transformers%20by%20Hand%20✍︎.md) | [☁️ Google Doc](https://docs.google.com/document/d/12Y4gtQuzSpXj-pQLKJr6SrANs_oe9uVhBzjJ2mD0zjI/edit?usp=sharing) | Full architecture |
| Keys, Queries, Values | [📁 02.Keys_Queries_Values-attention_mechanisms.md](./Tutorials/02.Keys_Queries_Values-attention_mechanisms.md) | [☁️ Stack Exchange](https://stats.stackexchange.com/questions/421935/what-exactly-are-keys-queries-and-values-in-attention-mechanisms) | Attention fundamentals |
| Self-Attention by Hand | [📁 03.Deep Dive into Self-Attention by Hand✍︎.md](./Tutorials/03.Deep%20Dive%20into%20Self-Attention%20by%20Hand✍︎.md) | [☁️ Google Doc](https://docs.google.com/document/d/1i1XEISzYFbydbixtxZfVpTn8Q0NPoP4lKlz6e8BWEhc/edit?usp=sharing) | Advanced attention |

### 🔗 External Resources
| Resource | Description | Format |
|----------|-------------|---------|
| [Attention Is All You Need](https://arxiv.org/abs/1706.03762) | Original transformer paper | Research Paper |
| [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) | Visual transformer explanation | Blog Post |

### Connection to Lab 8:
This lab prepares you for Lab 8 where you'll use pre-trained transformer models (BERT, GPT, etc.) through Hugging Face for practical NLP applications. You'll apply the theoretical understanding gained here to real-world tasks like text classification, NER, and generation.

## Navigation
**Previous Lab:** [← Lab 6 - Neural Networks Fundamentals](../Lab06-Neural%20Networks%20Fundementals/Lab06-lecture-guide.md)  
**Next Lab:** [Lab 8 - Gentle Hugging Face - Capabilities of LLMs →](../Lab08-Gentle%20Hugging%20Face-Capabilities%20of%20LLMs/Lab08-lecture-guide.md)