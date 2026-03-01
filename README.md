# RAG Pipeline with Vector Search and LLMs

## Overview
This project implements a **Retrieval-Augmented Generation (RAG) pipeline** that combines **vector-based document retrieval** with **large language model (LLM) text generation**.  

Given a user query, the system retrieves the most relevant documents from a database and generates a coherent answer using a language model.

---

## Features
- **Vector Search** using embeddings from [Sentence Transformers](https://www.sbert.net/).  
- **Document Storage** in MongoDB Atlas.  
- **Text Generation** using Hugging Face Transformers (`gpt2` pipeline).  
- **Similarity Metrics**: cosine similarity, variance, and ranking scores.  
- **Retrieval-Augmented Generation**: RAG pipeline produces high-quality responses based on context.  

---

## Tech Stack
- Python 3.10+  
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)  
- [Sentence Transformers](https://www.sbert.net/)  
- MongoDB Atlas (Vector + Document Storage)  
- Numpy & scikit-learn (cosine similarity and analysis)  

---

## Installation

```bash
# Install required packages
pip install transformers accelerate huggingface_hub
pip install sentence-transformers
pip install pymongo
pip install scikit-learn numpy
