<div align="center">

# 👋 Hi, I'm **Benny Hendrawan**

### AI Engineer · Builder of Intelligent Systems

[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://instagram.com/tripmurpy)
[![GitHub](https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tripmurpy)

---

*I build production-grade AI systems — RAG pipelines, agentic architectures, and LLM integrations*
*that transform raw data into intelligent, usable applications.*

> 🎯 **Open to opportunities** in AI Engineering, Data Engineering, or Backend Development.

---

### 📂 Quick Project Access
[💰 BennyCash](https://github.com/tripmurpy/Benny-Personal-Money-Assistant) • [🏪 Graha-chatbot-cs](https://github.com/tripmurpy/West-group-store) • [💊 apotek-chatbot-cs](https://github.com/tripmurpy/Project-chatbot-Apotek) • [🍳 CookPal AI](https://github.com/tripmurpy/cookpal-rag) • [📋 ASKY](https://github.com/tripmurpy/asky-project)

</div>

---


<div align="center">

`LangChain` `LangGraph` `Agentic RAG` `MCP` `Prompt Engineering` `Groq API` `Google AI Studio` `Qwen` `Hugging Face`
`Python` `SQL` `PostgreSQL` `Supabase (pgvector)` `ChromaDB` `FastAPI` `Telegram Bot API` `Google Sheets API`

</div>

---

## 🚀 Featured Projects

---

### 💰 BennyCash — AI-Powered Personal Finance Manager

> **Your personal finance manager that lives inside Telegram. No apps. No forms. Just conversation.**

<div align="center">

[![View Repository](https://img.shields.io/badge/🔗_View_Repository-181717?style=for-the-badge&logo=github)](https://github.com/tripmurpy/Benny-Personal-Money-Assistant)

</div>

BennyCash eliminates the friction of daily expense tracking by transforming it into a natural chat experience. Powered by an ensemble of cutting-edge AI models, it doesn't just listen — it **sees**, **hears**, and **understands**.

**🎯 Key Capabilities:**
- **💬 Natural Language Input** — Type `"Beli kopi 25rb di Starbucks"` and AI auto-categorizes, deducts balance, and records it
- **👁️ Receipt Scanning (Qwen VL)** — Snap a photo of any receipt. AI extracts items, prices, dates, and totals automatically
- **👂 Voice Recognition (Groq Whisper)** — Too busy to type? Send a voice note. Speech → structured data, instantly
- **📊 Smart Analytics** — Real-time balance tracking, categorized spending, PDF financial reports, and 14-day trend analysis
- **🎯 Goal Tracking** — Set saving goals with visual progress bars and motivational nudges
- **🧮 Budget Alerts** — Smart warnings at 80%, 90%, and budget overflow with intelligent split deduction
- **🧠 AI Coaching** — Weekly personalized financial insights based on your spending patterns
- **🔍 RAG-Powered Q&A** — Ask contextual questions like *"Berapa harga Fore Amerikano?"* with vector search accuracy

**⚙️ Architecture:** `Supabase pgvector` vector store → `BAAI/bge-m3` embeddings → `Qwen VL` vision → `Groq Whisper` audio → `LLM` generation

```
Python · LangChain · Supabase pgvector · Groq Whisper · Qwen VL · Telegram Bot API
```

---

### 🏪 Benny CS — AI Customer Service for Business

> **Your brand's most friendly, always-on customer service agent — built for the generation that spots corporate scripts from a mile away.**

<div align="center">

[![View Repository](https://img.shields.io/badge/🔗_View_Repository-181717?style=for-the-badge&logo=github)](https://github.com/tripmurpy/West-group-store)

</div>

Benny CS is a next-generation AI Customer Service Chatbot designed for businesses that want authentic, warm, and relatable interactions with Gen Z and Millennial customers. Built on a full RAG architecture, every answer is grounded in your actual business data — not hallucinations.

**🎯 Key Capabilities:**
- **🤖 RAG-Grounded Responses** — Every answer sourced from your business knowledge base via vector similarity search
- **💬 "Bestie" Persona** — Warm, Gen-Z friendly tone that feels human — not robotic
- **⚡ Powered by Qwen Flash** — Blazing-fast inference with multilingual support (ID & EN)
- **🔌 REST API Ready** — Simple `POST /api/chat` endpoint for any frontend integration
- **📄 Multi-Document Ingestion** — Automatically chunks, embeds, and indexes your business documents
- **☁️ Cloud-Deployed** — Production-ready with Railway deployment

**⚙️ Architecture:**
```
Document Ingestion → Chunking → Qwen Embedding → Supabase pgvector
     ↓
User Query → Query Embedding → Similarity Search (Top-K) → Qwen Flash LLM → Response
```

```
Python · FastAPI · LangChain · Supabase pgvector · Qwen Flash · Railway
```

---

### 💊 Apotek AI — Pharmacy Customer Service Chatbot

> **AI pharmacist assistant that understands your symptoms and recommends the right medicine — from a database of 50,000+ drugs.**

<div align="center">

[![View Repository](https://img.shields.io/badge/🔗_View_Repository-181717?style=for-the-badge&logo=github)](https://github.com/tripmurpy/Project-chatbot-Apotek)

</div>

Apotek AI combines a Telegram Bot interface with a powerful RAG engine to deliver accurate, contextual medicine recommendations. Users describe their symptoms in natural language, and the system retrieves the most relevant drugs from a massive dataset — then generates a clear, helpful response using Gemini AI.

**🎯 Key Capabilities:**
- **🔬 50,000+ Medicine Database** — Comprehensive drug dataset loaded, embedded, and searchable via vector similarity
- **🗣️ Symptom-Based Search** — Describe symptoms naturally → AI finds matching medications
- **🧬 ChromaDB Vector Store** — In-memory vector database with `paraphrase-multilingual-MiniLM-L12-v2` embeddings
- **🤖 Gemini AI Generation** — Contextual, human-readable responses grounded in actual drug data
- **🎙️ Voice Input (WIP)** — Voice note processing pipeline under active development
- **🌐 Web Interface** — Beautiful HTML/CSS/JS chat UI alongside Telegram

**⚙️ Architecture:**
```
Medicine CSV (50K+) → Embedding (MiniLM-L12-v2) → ChromaDB Vector Store
     ↓
User Symptom → Vector Search → Relevant Drug Context → Gemini AI → Response
```

```
Python · Telegram Bot API · ChromaDB · Gemini AI · SentenceTransformers · HTML/CSS/JS
```

---

### 🍳 CookPal AI — Recipe & Food Knowledge Assistant

> **Your personal AI chef on Telegram — powered by a curated knowledge base of recipes, ingredients, and cooking techniques.**

<div align="center">

`🔒 Private Repository`

</div>

CookPal is a full-stack RAG application built from scratch — from data ingestion to user-facing Telegram bot. It demonstrates end-to-end mastery of the RAG pipeline: data cleaning, chunking strategies, embedding generation, vector storage, retrieval logic, and LLM response orchestration.

**🎯 Key Capabilities:**
- **📚 Full RAG Pipeline** — Designed and built from scratch: ingestion → chunking → embedding → retrieval → generation
- **🔍 Semantic Search** — Supabase pgvector with `BAAI/bge-m3` multilingual embeddings
- **⚡ Groq LLM** — Fast, accurate response generation via LangChain
- **📊 Large-Scale Data Processing** — Cleaned and preprocessed massive recipe datasets
- **🤖 Telegram Bot Interface** — Deployed and accessible via Telegram
- **☁️ Railway Deployment** — Production-ready cloud hosting

```
Python · LangChain · Supabase pgvector · Groq API · BAAI/bge-m3 · Telegram Bot · Railway
```

---

### 📋 ASKY — AI Task Manager (Telegram × Google Sheets)

> **Tell the AI what you need to do in plain language. It extracts, categorizes, and organizes your tasks in Google Sheets — automatically.**

<div align="center">

[![View Repository](https://img.shields.io/badge/🔗_View_Repository-181717?style=for-the-badge&logo=github)](https://github.com/tripmurpy/project-tpt)
&nbsp;&nbsp;
[![Source Code](https://img.shields.io/badge/📦_Source_Code-181717?style=for-the-badge&logo=github)](https://github.com/tripmurpy/asky-project)

</div>

ASKY bridges unstructured human language and structured task management. Type *"I need to submit the report by Friday and call the client tomorrow"* — and the AI extracts individual tasks, infers due dates, auto-categorizes them, and saves everything to Google Sheets. It even sends daily evening reminders for pending tasks.

**🎯 Key Capabilities:**
- **🧠 NLP Task Extraction** — Powered by `Llama 3.3 70B` via Groq API for precise intent parsing
- **📊 Google Sheets Integration** — Persistent task storage with automatic schema management
- **⏰ Smart Reminders** — Automated daily notification scheduler
- **📁 Auto-Categorization** — AI infers task categories and due dates from natural language
- **🔄 Multi-Task Parsing** — Extract up to 10 tasks from a single message

**⚙️ Architecture:**
```
User Message → Telegram Bot → AI Agent (Llama 3.3) → Structured JSON
     ↓
Google Sheets API → Persistent Storage → Daily Reminder Scheduler
```

```
Python · Telegram Bot API · Groq API (Llama 3.3) · Google Sheets API · Google Cloud
```

---

## 🎓 Education

**Universitas Gunadarma** — Informatics / Information Systems
`2024 – present` · Class 2KA14

> Relevant coursework: Object-Oriented Programming · Database Systems · Operating Systems · Statistics

**Data Engineering Zoomcamp** — DataTalks.Club *(participant)*

---

## 📊 GitHub Activity

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=tripmurpy&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=tripmurpy&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

### 💬 Let's Connect

*I'm always open to discussing AI projects, collaboration opportunities, or new ideas.*

[![Instagram](https://img.shields.io/badge/tripmurpy-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://instagram.com/tripmurpy)
[![GitHub](https://img.shields.io/badge/tripmurpy-%23181717.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tripmurpy)

---

⚡ *"I don't just build chatbots — I build AI systems that understand, think, and deliver."*

</div>

---

*Last updated: April 2026*
