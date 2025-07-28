# Lab 1: Python Fundamentals - Lecture Guide

## Navigation
**Course:** AIDE Summer Machine Learning and Python Programming Bootcamp 2025  
**Lab:** 1 - Python Fundamentals  
**Next Lab:** [→ Lab 2 - Data Fundamentals and Intro to ML](../Lab02-Data%20Fundemantal%20and%20Intro%20to%20ML/Lab02-lecture-guide.md)

## Lab Schedule

### Opening (5 minutes)
- Welcome and introductions (2 min)
- Course overview and expectations (2 min)
- **Setup verification (Google Colab access)** (1 min)
  - Access the Colab notebook
  - Verify Python runtime is active
  - Test basic code execution

### Session 1: Python Fundamentals Workshop (120 minutes)
**Main Notebook:** [Python_Fundamentals_phil.ipynb](Scripts/Python_Fundamentals_phil.ipynb)  
**Colab Version:** [Google Colab Link](https://colab.research.google.com/drive/1t7XwyBSwnYF1chH_GmIoJ76yIsJJxcbS?usp=sharing)

#### **Part 1: Variables and Data Types** (15 minutes)
- Basic data types (string, integer, float, boolean)
- Variable assignment and multiple assignment
- F-string formatting for bibliographic citations
- Philosophy-focused examples with paper titles and authors

#### **Part 2: String Operations** (15 minutes)
- String length, uppercase/lowercase transformations
- Word counting with `.split()` and `len()`
- Text cleaning with `.strip()`
- Analyzing philosophical quotes and paper titles

#### **Part 3: Lists** (15 minutes)
- Creating and accessing lists with indices
- List methods: `.append()`, `min()`, `max()`
- Processing collections of philosophers and years
- Building and analyzing reading lists

#### **Part 4: Dictionaries** (15 minutes)
- Key-value pairs for structured research data
- Creating philosopher profiles and paper records
- Accessing and modifying dictionary data
- Building citation databases

#### **Part 5: Conditionals and Loops** (20 minutes)
- `if/elif/else` statements for classification
- `for` loops for processing collections
- Categorizing papers by impact, era, and criteria
- Combining loops with conditionals for analysis

#### **Part 6: Functions** (15 minutes)
- Function definition with parameters and return values
- Creating reusable citation formatters
- Building paper analysis tools
- Functions integrating all previous concepts

#### **Part 7: File Operations** (15 minutes)
- Reading and writing files with `open()`
- Processing structured data (CSV-like format)
- Creating sample data files
- Building simple bibliography systems

#### **Final Project: Research Paper Analyzer** (15 minutes)
- Comprehensive function combining all concepts
- Real-world application to philosophical papers
- Analysis including citations, impact, and categorization
- Integration exercise demonstrating mastery

### Wrap-up and Q&A (10 minutes)
- Review comprehensive skill set
- Address student questions
- Preview next lab topics

## Learning Objectives
By the end of this lab, students will be able to:
- **Variables & Data Types:** Store and manipulate research data using appropriate types (strings, integers, booleans)
- **String Processing:** Analyze text data including quotes, titles, and citations using Python string methods
- **Data Structures:** Use lists and dictionaries effectively for organizing research information
- **Control Flow:** Apply conditionals and loops to classify and process collections of research data
- **Function Creation:** Build reusable functions for citation formatting and paper analysis
- **File Operations:** Read and write research data to external files
- **Integration:** Combine all concepts to create a comprehensive research paper analyzer

## Key Concepts

| Concept | Description | Research Example |
|---------|-------------|------------------|
| **Variables** | Store different data types for research | `paper_title = "The Structure of Scientific Revolutions"`, `year = 1962` |
| **String Operations** | Text processing and analysis | `quote.split()`, `title.upper()`, `len(text)` |
| **Lists** | Ordered collections for research data | `philosophers = ["Plato", "Aristotle", "Kant"]` |
| **Dictionaries** | Structured data with key-value pairs | `paper = {"title": "Two Dogmas", "author": "Quine", "year": 1951}` |
| **Conditionals** | Classification and decision making | `if citations > 100: impact = "High"` |
| **Loops** | Process collections of research items | `for paper in papers: analyze(paper)` |
| **Functions** | Reusable analysis tools | `def format_citation(author, year, title): ...` |
| **File Operations** | Import and export research data | `with open("philosophers.txt", "r") as f: ...` |

## Resources

| Resource | Description |
|----------|-------------|
| [Python_Fundamentals_phil.ipynb](Scripts/Python_Fundamentals_phil.ipynb) | **Main comprehensive workshop** |
| [Google Colab Version](https://colab.research.google.com/drive/1t7XwyBSwnYF1chH_GmIoJ76yIsJJxcbS?usp=sharing) | **Cloud-based version for easy access** |
| [Python.org Official Tutorial](https://docs.python.org/3/tutorial/) | Chapters 1-4 for reference |

## Colab-Specific Notes
- **Runtime Type**: Ensure Python 3 runtime is selected
- **GPU/TPU**: Not needed for this lab (CPU is sufficient)
- **File Upload**: Students can upload local files if needed
- **Session Timeout**: Colab sessions may timeout after 12 hours
- **Save Progress**: Remind students to save their work regularly

## Supplementary Materials 
1. **Harvard CS50 Lecture 0** (1 hr 40 minutes)
   - [Introduction to Computer Science](https://cs50.harvard.edu/x/2024/weeks/0/)
   - Core programming concepts and computational thinking
   
2. **Coursera Python for Data Science, AI and Development** (40 minutes)
   - Module 1 (Python data types)
   - Module 2 (Python data structures)
   - Module 3 (Conditionals and Functions)

## Troubleshooting Common Issues

| Issue | Solution |
|-------|----------|
| **Colab not loading** | Check internet connection, try refreshing page |
| **Runtime disconnected** | Click "Connect" or restart runtime |
| **Code not executing** | Ensure cell is selected and press Shift+Enter |
| **Import errors** | Check if required libraries are installed |
| **File not found** | Upload file to Colab or use sample data |
| **Session timeout** | Save work and restart runtime if needed |

## 🗂️ Navigation
- [← Back to Main Course](../README.md)
- [→ Next: Lab 2.01 - Data Fundamentals](../Lab02.01-Data%20Fundemantals/Lab02.01-lecture-guide.md)

