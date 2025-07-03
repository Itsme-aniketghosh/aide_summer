# Lab 7: Discovering What LLMs Can Do – 10 Core Capabilities

## Table of Contents
1. [Pre-Lab Learning](#pre-lab-learning)
2. [Lab Schedule](#lab-schedule)
3. [Learning Objectives](#learning-objectives)
4. [Quick Reference: 10 LLM Capabilities](#quick-reference-10-llm-capabilities)
5. [Key Concepts](#key-concepts)
6. [Quick Links](#quick-links)

## Pre-Lab Learning (30 minutes)
### Required Materials:
1. **Create a Hugging Face Account** (10 min):
   - [Hugging Face](https://huggingface.co/) - Sign up for a free account
2. **Reading:**
   - [IBM: What are Word Embeddings?](https://www.ibm.com/think/topics/word-embeddings)  
     *Why:* Gives students foundational understanding of how LLMs represent language, which is crucial before using APIs.
3. **Explore/Reference:**
   - [Hugging Face Model Hub](https://huggingface.co/models)
   - [Transformers Documentation](https://huggingface.co/docs/transformers)
   - [Free Philosophy Texts](https://www.gutenberg.org/browse/categories/5)
   *Note:* These resources are for exploration and reference before and during the lab.
4. **Watch** (10 min):
   - [Hugging Face in 15 Minutes](https://www.youtube.com/watch?v=QEaBAZQCtwE)
5. **Preview the Colab Notebook** (10 min):
   - [Lab 7 Colab: LLM Capabilities](https://colab.research.google.com/drive/1qHTo8fC5L4895GQsZr4itCR7KHHHxEX0?usp=sharing) – Skim to get familiar with the workflow

## Lab Schedule

### Session 1: Setup & Introduction (10 minutes)
- Overview of LLMs and Hugging Face
- Setting up Colab and required libraries
- What is a pipeline?

### Session 2: Category A – Understanding Text (30 minutes)
- A1. Text Classification
- A2. Named Entity Recognition (NER)
- A3. Zero-Shot Classification
- Synthesis: Combine classification and NER

### Session 3: Category B – Working with Knowledge (30 minutes)
- B1. Question Answering
- B2. Summarization
- B3. Feature Extraction (Similarity)
- Synthesis: Build a knowledge extraction pipeline

### Session 4: Category C – Creating and Connecting (30 minutes)
- C1. Text Generation
- C2. Translation
- C3. Chat Models
- C4. Text-to-Image (conceptual)
- Synthesis: Creative philosophy exploration tool

### Integration & Showcase (15 minutes)
- Final Project: Build your own research assistant
- Capability combination matrix
- Q&A and troubleshooting

## Learning Objectives
By the end of this lab, students will be able to:
- Use 10 fundamental LLM capabilities through Hugging Face
- Select appropriate models for different tasks
- Combine capabilities for research applications
- Build a simple research assistant using LLM pipelines

## Quick Reference: 10 LLM Capabilities
| ID | Capability | Task | Recommended Model | Example Use |
|----|------------|------|------------------|-------------|
| A1 | Text Classification | Categorize text | distilbert-base-uncased | Sort papers by topic |
| A2 | NER | Find entities | dslim/bert-base-NER | Extract philosopher names |
| A3 | Zero-Shot | Flexible categories | facebook/bart-large-mnli | Custom classifications |
| B1 | Question Answering | Extract info | distilbert-base-cased-distilled-squad | Find specific claims |
| B2 | Summarization | Condense text | sshleifer/distilbart-cnn-12-6 | Abstract papers |
| B3 | Feature Extraction | Text similarity | sentence-transformers/all-MiniLM-L6-v2 | Find related concepts |
| C1 | Text Generation | Create text | gpt2 | Brainstorm ideas |
| C2 | Translation | Convert languages | Helsinki-NLP/opus-mt-en-de | Access global philosophy |
| C3 | Chat Models | Dialogue | microsoft/DialoGPT-small | Interactive exploration |
| C4 | Text-to-Image* | Visualize | runwayml/stable-diffusion-v1-5 | Concept visualization |
*Text-to-Image requires significant resources – demonstrated conceptually in lab

## Key Concepts
| Concept | Description | Application |
|---------|-------------|-------------|
| **LLM** | Large Language Model | Text generation, analysis |
| **Pipeline** | Simple interface for ML tasks | Quick prototyping |
| **NER** | Named Entity Recognition | Extracting people, places, etc. |
| **Zero-Shot** | Classify with custom labels | Flexible categorization |
| **Summarization** | Condense long texts | Research digests |
| **Feature Extraction** | Semantic similarity | Find related ideas |
| **Text Generation** | AI writing partner | Brainstorming, dialogue |
| **Translation** | Multilingual access | Global research |
| **Text-to-Image** | Visualize concepts | Creative exploration |

## Quick Links
| Resource | Description | Format |
|----------|-------------|---------|
| [Lab 7 Colab: LLM Capabilities](https://colab.research.google.com/drive/1qHTo8fC5L4895GQsZr4itCR7KHHHxEX0?usp=sharing) | **Main lab notebook** | Google Colab |
| [Hugging Face](https://huggingface.co/) | Model repository and deployment | Web Platform |
| [Transformers Docs](https://huggingface.co/docs/transformers/) | Hugging Face documentation | Documentation |

## Navigation
**Previous Lab:** [← Lab 6 – Neural Networks and Transformers](../Lab06-nn-transformers/Lab06-lecture-guide.md)  
**Next Lab:** [Lab 8 – LLMs with API →](../Lab08-commercial-LLMs/Lab08-lecture-guide.md)


