# Intelligent Text Summarizer & Chatbot using NLP

## 📌 Project Description  

This project implements an **Intelligent Text Summarizer and Chatbot** using **Natural Language Processing (NLP)** and **Deep Learning**. It combines two powerful applications into one system:  

### 🔹 Text Summarization  
The system provides both **extractive** and **abstractive** summarization:  
- **Extractive Summarizer**: Uses NLTK to tokenize text, compute word frequencies, and rank sentences. The top sentences form a concise summary.  
- **Abstractive Summarizer**: Uses Hugging Face **Transformer models** (DistilBART/T5) to generate human-like summaries by paraphrasing the text instead of only extracting sentences.  

### 🔹 Chatbot (Hybrid Retrieval + Generative)  
The chatbot combines **retrieval** and **generation** for accurate and natural responses:  
- **Sentence Embeddings**: Created using **Sentence-Transformers (MiniLM)**.  
- **Efficient Search**: FAISS is used to quickly retrieve the most relevant knowledge base entries.  
- **Generative Responses**: Retrieved context is passed into a **T5 model** to produce coherent, human-like answers.  

### 🔹 Technologies & Libraries Used  
- **Python**  
- **NLP libraries**: NLTK, SpaCy  
- **Deep Learning**: PyTorch, TensorFlow/Keras via Hugging Face Transformers  
- **Sentence-Transformers**: Dense vector embeddings  
- **FAISS**: Fast similarity search  
- **Hugging Face Transformers (BART, T5)**: Abstractive summarization and generative chatbot  

### 🔹 Features Built  
- Extractive Summarizer using frequency-based scoring  
- Abstractive Summarizer using Transformer models  
- Retrieval-based Chatbot using FAISS + Sentence-Transformers  
- Generative Chatbot using T5 for natural answers  
- Combined system allowing users to choose between summarization and chatbot interaction  

### 🔹 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<fizanaushad>/intelligent-text-summarizer-chatbot.git
   cd intelligent-text-summarizer-chatbot
