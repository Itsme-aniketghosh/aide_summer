# Lab 9: Prompt Engineering - LLMs with APIs - Lecture Guide

## Table of Contents
1. [Pre-Lab Learning](#pre-lab-learning)
2. [Lab Schedule](#lab-schedule)
3. [Learning Objectives](#learning-objectives)
4. [Key Concepts](#key-concepts)
5. [Quick Links](#quick-links)

## Pre-Lab Learning (45 minutes)
### Required Materials:
1. **Reading:**
   - [What is an API? (freeCodeCamp)](https://www.freecodecamp.org/news/what-is-an-api-in-english-please-b880a3214a82/)  
     *Why:* Simple intro to APIs for all backgrounds.
   - [OpenAI API Quickstart Guide](https://platform.openai.com/docs/quickstart)  
     *Why:* Skim for structure and API workflow.
2. **Video:**
   - [How to Use the OpenAI API (YouTube, 8 min)](https://www.youtube.com/watch?v=TEziqYyRr1w)  
     *Why:* Visual walkthrough of API usage.
3. **Hands-on:**
   - Sign up for a free API key (OpenAI, Cohere, or Hugging Face Inference API)
   - Test a simple API call using [curl](https://curl.se/) or [Postman](https://www.postman.com/) (optional, 10 min)
4. **Preview the Lab Notebook:**
   - [☁️ Lab09 Google Colab](https://colab.research.google.com/drive/1-lHhlUMUAF4DQWSU5U2Dc97VemjG9G85?usp=sharing) - Preview the workflow and exercises

## Lab Schedule (120 minutes)

| Time | Section | Activity | Format |
|------|---------|----------|---------|
| 0-15 | **Part 1: API Key Setup** | Demo: HuggingFace setup → Exercise: OpenRouter setup ([Colab Link](https://colab.research.google.com/drive/1-lHhlUMUAF4DQWSU5U2Dc97VemjG9G85?usp=sharing)) | Demo + Exercise |
| 15-30 | **Part 2: First API Test** | Demo: HuggingFace call → Exercise: OpenRouter call + comparison | Demo + Exercise |
| 30-50 | **Part 3: Model Comparison** | Demo: 3 models on same question → Exercise: Your question on 3 models | Demo + Exercise |
| 50-75 | **Part 4: Prompt Engineering** | Demo: Weak vs strong prompts → Exercise: Improve a weak prompt | Demo + Exercise |
| 75-100 | **Part 5: Batch Processing** | Demo: Process 3 quotes → Exercise: Process your philosophical texts | Demo + Exercise |
| 100-120 | **Part 6: Real Data Upload** | BONUS: Complete pipeline with your own CSV data | Optional Exercise |

## Learning Objectives
By the end of this lab, you'll be able to:
- Set up and use API keys securely for philosophical research
- Call APIs to analyze philosophical texts  
- Compare different AI models for your research needs
- Engineer effective prompts for better philosophical analysis
- Process multiple texts in batches through APIs
- Import your own data and apply all API skills

## Key Concepts
| Concept | Description | Application |
|---------|-------------|-------------|
| **API Authentication** | Secure loading of API keys using Google Colab secrets | Protecting credentials in research workflows |
| **Model Comparison** | Testing multiple LLMs (HuggingFace, OpenRouter) on same task | Finding best model for philosophical analysis |
| **Prompt Engineering** | Designing structured prompts with role, task, format, constraints | Getting better philosophical insights from AI |
| **Batch Processing** | Systematic analysis of multiple texts using API loops | Scaling philosophical research to large datasets |

## Quick Links
| Resource | Description | Format |
|----------|-------------|---------|
| [Lab09_LLMwAPIs.ipynb](Scripts/Lab09_LLMwAPIs.ipynb) | **Main lab notebook** | Jupyter Notebook |
| [☁️ Google Colab Version](https://colab.research.google.com/drive/1-lHhlUMUAF4DQWSU5U2Dc97VemjG9G85?usp=sharing) | **Run notebook in browser** | Google Colab |
| [HuggingFace](https://huggingface.co) | Free API for models like Phi-4 | Web Platform |
| [OpenRouter](https://openrouter.ai) | API access to GPT, Claude, etc. ($1 free credit) | Web Platform |

## Navigation
**Previous Lab:** [← Lab 8 - Gentle Hugging Face - Capabilities of LLMs](../Lab08-Gentle%20Hugging%20Face-Capabilities%20of%20LLMs/Lab08-lecture-guide.md)  
**Next Lab:** [Lab 10 - Context Engineering - (Graph)RAGged LLMs →](../Lab10-Context%20Engineering-(Graph)RAGged-LLMs/Lab10-lecture-guide.md) 


