# 🤖 Generative AI, ML & DL Portfolio

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--learn-orange.svg)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-PyTorch%20%7C%20TensorFlow-red.svg)
![Generative AI](https://img.shields.io/badge/Generative%20AI-LangChain%20%7C%20OpenAI-green.svg)
![NLP](https://img.shields.io/badge/NLP-Transformers%20%7C%20Knowledge%20Graphs-purple.svg)

**A comprehensive showcase of Generative AI, Machine Learning, and Deep Learning projects**

[Projects](#-featured-projects) • [Skills](#-technical-skills) • [About](#-about)

</div>

---

## 📋 Overview

This portfolio presents a comprehensive collection of projects spanning from traditional machine learning algorithms to cutting-edge generative AI applications. Each project demonstrates different aspects of AI development, including:

- **Generative AI**: LLM-powered applications, chatbots, content generation, and **parameter-efficient fine-tuning** (LoRA / QLoRA) on domain datasets
- **NLP & Knowledge Graphs**: Entity extraction, relationship mapping, and structured data processing
- **Real-time AI**: WebRTC integration with AI models for live applications
- **Deep Learning**: Neural network architectures and training pipelines
- **Machine Learning**: Classification algorithms, regression models, model comparison, and performance analysis

---

## 📊 Projects Overview

<!-- 
  TO ADD A NEW PROJECT:
  1. Add a new row below following the format: | # | [emoji] **Project Name** | Brief description (1-2 lines) | [View](GitHub-URL) |
  2. Update the project number (#) sequentially
  3. Add the detailed project section in "Featured Projects" section below
  4. Update the "Quick Links" section at the bottom
  5. Update the "Project Statistics" table if needed
-->

| # | Project | Description | Repository |
|---|---------|-------------|------------|
| 1 | 🎙️ **[Synthetic Radio Host](https://github.com/vineetdev/Synthetic-Radio-Host)** | AI-powered podcast generation system using Ollama LLM and ElevenLabs TTS. Generates Hinglish conversations with multi-speaker dialogue, automatic content research, and comprehensive testing. | [View](https://github.com/vineetdev/Synthetic-Radio-Host) |
| 2 | 💼 **[Financial Knowledge Graph Extractor](https://github.com/vineetdev/financial-knowledge-graph-extractor)** | Transforms unstructured financial documents into structured knowledge graphs. Extracts entities, relationships, and financial metrics using LangChain and OpenAI GPT-4o-mini. | [View](https://github.com/vineetdev/financial-knowledge-graph-extractor) |
| 3 | 📹 **[WebRTC Ollama Video Call](https://github.com/vineetdev/WebRTC-Samples/tree/main/webrtc-ollama-call-videos)** | Real-time AI video communication system integrating WebRTC with Ollama for live LLM inference. Enables peer-to-peer video/audio streaming with low-latency AI processing. | [View](https://github.com/vineetdev/WebRTC-Samples/tree/main/webrtc-ollama-call-videos) |
| 4 | 🏦 **[Banking QA LLM Fine-Tuning (DistilGPT-2 & TinyLlama)](https://github.com/vineetdev/banking-qa-llm-finetune-distilgpt2-tinyllama)** | Parameter-efficient fine-tuning on Hugging Face **Bitext** retail banking QA: **LoRA** on DistilGPT-2 and **QLoRA** (4-bit) on TinyLlama 1.1B Chat. Jupyter notebooks with BLEU, ROUGE, and sentence-embedding cosine evaluation. | [View](https://github.com/vineetdev/banking-qa-llm-finetune-distilgpt2-tinyllama) |
| 5 | 💬 **[Simple Chatbot with LangChain & Streamlit](https://github.com/vineetdev/SIMPLE-CHATBOT-WITH-LANGCHAIN-STREAMLIT)** | Basic LLM-powered conversational interface demonstrating LangChain integration with OpenAI API. Features clean Streamlit UI for real-time interactive conversations. | [View](https://github.com/vineetdev/SIMPLE-CHATBOT-WITH-LANGCHAIN-STREAMLIT) |
| 6 | 🧠 **[Chatbot with History](https://github.com/vineetdev/CHATBOT-WITH-HISTORY-LANGCHAIN-STREAMLIT-OPENAI)** | Advanced conversational AI with memory management. Maintains conversation context across multiple turns using LangChain, Streamlit, and OpenAI API with session-based tracking. | [View](https://github.com/vineetdev/CHATBOT-WITH-HISTORY-LANGCHAIN-STREAMLIT-OPENAI) |
| 7 | 🔢 **[MNIST ML Classification Comparison](https://github.com/vineetdev/mnist-ml-classification-comparison)** | Comprehensive performance analysis of 6 ML algorithms (KNN, SVM, Random Forest, etc.) on MNIST dataset. Includes metrics, efficiency analysis, PCA impact study, and visualizations. | [View](https://github.com/vineetdev/mnist-ml-classification-comparison) |
| 8 | 📊 **[Regression Models Comparison](https://github.com/vineetdev/regression-comparison-linear-multiple-polynomial)** | Comprehensive comparison of Simple Linear, Multiple Linear, and Polynomial Regression models for predicting bike rental counts. Includes data preprocessing, model evaluation, performance analysis, and interactive Streamlit app. | [View](https://github.com/vineetdev/regression-comparison-linear-multiple-polynomial) |
<!-- Add new projects above this line -->

---

## 📧 Contact

Feel free to reach out for collaborations, questions, or opportunities!

- **LinkedIn**: [https://www.linkedin.com/in/vineetkrsrivastava/]
- **Email**: [mailto:communication.vineet@gmail.com]

---

## 🚀 Featured Projects

<!-- 
  TO ADD A NEW PROJECT DETAILED SECTION:
  1. Copy the format below and update with your project details
  2. Use the same number as in the Projects Overview table
  3. Include: Title, Subtitle, GitHub badge, Description, Key Features, Tech Stack
  4. Add a horizontal rule (---) between projects
-->

### 1. 🎙️ Synthetic Radio Host
**AI-Powered Podcast Generation System**

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/vineetdev/Synthetic-Radio-Host)

An end-to-end system that generates synthetic radio podcasts using:
- **LLM Integration**: Ollama for script generation in Hinglish (Hindi-English mix)
- **Text-to-Speech**: ElevenLabs API for natural voice synthesis
- **Wikipedia Integration**: Automatic content research and context fetching
- **Audio Processing**: Multi-speaker dialogue generation with pauses and transitions

**Key Features:**
- One-shot learning for consistent conversation style
- Smart accent tagging system for Indian English and Hindi accents
- Comprehensive test suite (45+ test cases)
- Full documentation and design specifications

**Tech Stack:** Python, Ollama, ElevenLabs API, Wikipedia API, pytest

---

### 2. 💼 Financial Knowledge Graph Extractor
**AI-Powered Financial Document Analysis**

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/vineetdev/financial-knowledge-graph-extractor)

Transforms unstructured financial documents into structured knowledge graphs:
- **Entity Extraction**: Companies, executives, subsidiaries, financial metrics
- **Relationship Mapping**: Corporate structures, ownership, partnerships
- **Graph Visualization**: Interactive network graphs using NetworkX and Mermaid
- **LLM-Powered**: OpenAI GPT-4o-mini for intelligent extraction

**Key Features:**
- PDF document processing and text extraction
- Financial number linking to entities
- Multiple visualization formats (static, interactive HTML)
- GraphRAG capabilities for querying corporate structures

**Tech Stack:** Python, LangChain, OpenAI API, NetworkX, PDF parsing

---

### 3. 📹 WebRTC Ollama Video Call
**Real-time AI Video Communication**

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/vineetdev/WebRTC-Samples/tree/main/webrtc-ollama-call-videos)

Integration of AI models with real-time video communication:
- **WebRTC Integration**: Peer-to-peer video/audio streaming
- **Ollama Integration**: Local LLM inference for real-time processing
- **Live AI Processing**: Real-time AI model inference on video streams
- **Low Latency**: Optimized for real-time applications

**Tech Stack:** JavaScript, WebRTC, Ollama, Node.js

---

### 4. 🏦 Banking QA LLM Fine-Tuning (DistilGPT-2 & TinyLlama)
**Parameter-Efficient Fine-Tuning on Retail Banking FAQs**

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/vineetdev/banking-qa-llm-finetune-distilgpt2-tinyllama)

Domain adaptation of small LMs on the public [Bitext Retail Banking LLM Chatbot Training Dataset](https://huggingface.co/datasets/bitext/Bitext-retail-banking-llm-chatbot-training-dataset) using **PEFT**—mirroring the same banking QA task at two scales:

- **DistilGPT-2 + LoRA**: Full-precision LoRA on attention projections; train/val caps (10k/1k); **10** evenly spaced held-out queries; early stopping; optional interactive prompt demo.
- **TinyLlama 1.1B Chat + QLoRA**: 4-bit quantized backbone with LoRA adapters; **20k / 2k** train/val on the first 22k rows; label masking on assistant tokens; **2**-question before/after checks plus automated metrics.
- **Evaluation**: NLTK **BLEU**, **ROUGE-1/2/L**, and **cosine similarity** via `sentence-transformers` (`all-MiniLM-L6-v2`)—README explains why cosine and ROUGE-1 matter most for long, paraphrased banking answers.

**Key Features:**
- Side-by-side notebooks: `distilgpt2-bitext-finetune.ipynb` and `tinyllama-bitext-banking-finetune.ipynb`
- `requirements.txt` for local installs; TinyLlama path optimized for **Google Colab** (`bitsandbytes` for 4-bit)
- Honest **scope & limitations** (eval sets differ; not a controlled cross-model benchmark without a shared held-out file)

**Tech Stack:** Python, PyTorch, Hugging Face `transformers` / `datasets`, PEFT (LoRA), bitsandbytes (QLoRA), NLTK, rouge-score, sentence-transformers, scikit-learn

---

### 5. 💬 Simple Chatbot with LangChain & Streamlit
**Basic LLM-Powered Conversational Interface**

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/vineetdev/SIMPLE-CHATBOT-WITH-LANGCHAIN-STREAMLIT)

A clean, simple chatbot implementation demonstrating:
- **LangChain Integration**: Chain-based conversation flow
- **Streamlit UI**: User-friendly web interface
- **LLM Integration**: OpenAI API for natural language understanding
- **Real-time Chat**: Interactive conversation experience

**Tech Stack:** Python, LangChain, Streamlit, OpenAI API

---

### 6. 🧠 Chatbot with History (LangChain, Streamlit, OpenAI)
**Advanced Conversational AI with Memory**

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/vineetdev/CHATBOT-WITH-HISTORY-LANGCHAIN-STREAMLIT-OPENAI)

An enhanced chatbot with conversation memory and context retention:
- **Conversation History**: Maintains context across multiple turns
- **Memory Management**: Efficient storage and retrieval of chat history
- **Context-Aware Responses**: Understands previous conversation context
- **Streamlit Integration**: Beautiful, responsive web interface

**Key Features:**
- Session-based conversation tracking
- Context-aware response generation
- History visualization and management
- Error handling and graceful degradation

**Tech Stack:** Python, LangChain, Streamlit, OpenAI API, Session State Management

---

### 7. 🔢 MNIST ML Classification Comparison
**Comprehensive Algorithm Performance Analysis**

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/vineetdev/mnist-ml-classification-comparison)

A detailed comparison of 6 different ML classification algorithms on the MNIST dataset:
- **Algorithms**: KNN, Logistic Regression, Naive Bayes, SVM, Random Forest, Decision Tree
- **Performance Metrics**: Accuracy, Precision, Recall, F1-Score
- **Efficiency Analysis**: Training and prediction time measurements
- **PCA Impact**: Dimensionality reduction analysis

**Key Features:**
- Side-by-side algorithm comparison
- Tree visualization for Decision Trees and Random Forest
- Comprehensive performance charts
- Detailed PCA impact analysis

**Tech Stack:** Python, Scikit-learn, Matplotlib, Seaborn, Pandas

---

### 8. 📊 Regression Models Comparison
**Linear, Multiple Linear & Polynomial Regression Analysis**

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/vineetdev/regression-comparison-linear-multiple-polynomial)

A comprehensive comparison of three regression models for predicting bike rental counts:
- **Simple Linear Regression**: Single-feature model using temperature as predictor
- **Multiple Linear Regression**: Multi-feature model with weather and temporal variables
- **Polynomial Regression**: Non-linear regression with quadratic temperature features

**Key Features:**
- Data preprocessing and feature scaling using StandardScaler
- Model evaluation with R² scores and performance metrics
- Residual analysis and visualization
- Interactive Streamlit web application
- Side-by-side model comparison with visualizations

**Tech Stack:** Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, Streamlit

<!-- Add new project detailed sections above this line -->

---

## 🛠️ Technical Skills

### Machine Learning & Deep Learning
- **Algorithms**: KNN, SVM, Random Forest, Decision Trees, Logistic Regression, Naive Bayes
- **Frameworks**: Scikit-learn, TensorFlow, PyTorch
- **Evaluation**: Cross-validation, performance metrics, hyperparameter tuning
- **Visualization**: Matplotlib, Seaborn, Plotly

### Generative AI & LLMs
- **Frameworks**: LangChain, LangGraph, Hugging Face Transformers, PEFT (LoRA / QLoRA)
- **APIs**: OpenAI (GPT-4, GPT-3.5), Ollama (local LLMs)
- **Applications**: Chatbots, content generation, text-to-speech, domain-specific LM fine-tuning
- **Memory Management**: Conversation history, context retention

### Natural Language Processing
- **Knowledge Graphs**: Entity extraction, relationship mapping, GraphRAG
- **Text Processing**: PDF parsing, text extraction, structured data generation
- **Embeddings**: Vector databases, semantic search
- **Multi-language**: Hinglish (Hindi-English) processing

### Real-time AI & Web Technologies
- **WebRTC**: Real-time video/audio streaming
- **Streamlit**: Interactive web applications
- **API Integration**: RESTful APIs, WebSocket connections
- **Audio Processing**: TTS, audio synthesis, multi-speaker generation

### Software Engineering
- **Testing**: pytest, comprehensive test suites
- **Documentation**: Technical design documents, README files
- **Version Control**: Git, GitHub
- **Code Quality**: Clean code practices, error handling

---

## 📊 Project Statistics

<!-- Update counts and add new categories when adding projects -->

| Category | Count | Technologies |
|----------|-------|--------------|
| **Generative AI** | 4 | LangChain, OpenAI, Ollama, Streamlit, Transformers, PEFT (LoRA/QLoRA) |
| **ML/DL Projects** | 2 | Scikit-learn, Classification Algorithms, Regression Models |
| **NLP & Knowledge Graphs** | 1 | LangChain, NetworkX, Entity Extraction |
| **Real-time AI** | 1 | WebRTC, Ollama, Video Processing |
| **Total Projects** | 8 | Multiple AI/ML domains |

---

## 🎯 Learning Journey

This portfolio represents a progression from:
1. **Traditional ML** → Understanding classification algorithms and performance metrics
2. **Deep Learning** → Neural network architectures and training
3. **NLP Fundamentals** → Text processing and knowledge extraction
4. **Generative AI** → LLM integration and conversational AI
5. **Real-time Applications** → WebRTC and live AI processing
6. **Production Systems** → Testing, documentation, and deployment

---

## 📈 Key Achievements

- ✅ Built end-to-end AI systems from data processing to deployment
- ✅ Implemented multiple ML algorithms with comprehensive performance analysis
- ✅ Created production-ready chatbots with conversation memory
- ✅ Fine-tuned small LMs on retail banking QA with LoRA and QLoRA (Hugging Face PEFT)
- ✅ Developed knowledge graph extraction systems for financial documents
- ✅ Integrated real-time AI with video communication protocols
- ✅ Maintained high code quality with comprehensive test suites

---

## 🔗 Quick Links

<!-- Add new project links here in the same order as the Projects Overview table -->

- [Synthetic Radio Host](https://github.com/vineetdev/Synthetic-Radio-Host)
- [Financial Knowledge Graph Extractor](https://github.com/vineetdev/financial-knowledge-graph-extractor)
- [WebRTC Ollama Integration](https://github.com/vineetdev/WebRTC-Samples/tree/main/webrtc-ollama-call-videos)
- [Banking QA LLM Fine-Tuning (DistilGPT-2 & TinyLlama)](https://github.com/vineetdev/banking-qa-llm-finetune-distilgpt2-tinyllama)
- [Simple Chatbot](https://github.com/vineetdev/SIMPLE-CHATBOT-WITH-LANGCHAIN-STREAMLIT)
- [Chatbot with History](https://github.com/vineetdev/CHATBOT-WITH-HISTORY-LANGCHAIN-STREAMLIT-OPENAI)
- [MNIST ML Classification Comparison](https://github.com/vineetdev/mnist-ml-classification-comparison)
- [Regression Models Comparison](https://github.com/vineetdev/regression-comparison-linear-multiple-polynomial)

---

## 📝 About

This portfolio showcases practical applications of AI/ML technologies across various domains. Each project includes:
- Complete source code
- Comprehensive documentation
- Performance analysis and results
- Technical design documents
- Test suites where applicable

**Focus Areas:**
- Practical, real-world applications
- Clean, maintainable code
- Comprehensive documentation
- Performance optimization
- User-friendly interfaces

---

<div align="center">

**Built with ❤️ using Python, LangChain, and modern AI/ML frameworks**

⭐ Star this repository if you find it helpful!

</div>

