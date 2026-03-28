# 🤖 AI Financial Reports RAG Chatbot

## 📌 Overview

This project is an **AI-powered RAG (Retrieval-Augmented Generation) chatbot** built using **n8n** that automatically processes financial reports and enables intelligent querying.

The system ingests financial reports (Q1–Q4), converts them into embeddings, stores them in a vector database, and allows users to ask questions with accurate, context-based answers.

---

## 🚀 Key Features

* 📂 Automated ingestion from Google Drive
* 🔄 Data preprocessing and chunking
* 🧠 Embedding generation using HuggingFace
* 📊 Vector storage with Pinecone
* 💬 AI chatbot powered by OpenAI
* 🔍 Context-aware financial question answering
* ⚡ Fully automated workflow using n8n

---

## 🏗️ Architecture

1. Google Drive → Fetch financial reports
2. Filter new files using Google Sheets
3. Download & preprocess documents
4. Split text into chunks
5. Generate embeddings (HuggingFace)
6. Store embeddings in Pinecone
7. Query system via chatbot
8. Retrieve relevant data and generate answers

---

## 🧰 Tech Stack

* n8n (Workflow Automation)
* OpenAI (LLM)
* Pinecone (Vector Database)
* HuggingFace (Embeddings)
* Google Drive API
* Google Sheets API


---

## 💡 Business Value

This solution demonstrates how organizations can:

* Automate document processing workflows
* Extract insights from unstructured data
* Enable real-time decision support using AI
* Reduce manual effort in financial analysis

---

## 🎯 Use Cases

* Financial reporting analysis
* Business intelligence automation
* Enterprise knowledge systems
* AI-powered document search

---

## 📂 How to Use

1. Import `workflow.json` into n8n
2. Configure credentials:

   * OpenAI API
   * Pinecone
   * Google Drive
   * Google Sheets
3. Run the workflow
4. Start asking questions via chatbot

---

## 👨‍💻 Author

Antonious (Automation Engineer specialist | AI Workflow Builder)

---
