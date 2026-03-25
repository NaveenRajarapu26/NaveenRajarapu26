# Hi, I'm Naveen Rajarapu 👋

🟢 **Open to full-time AI/ML roles — OPT available June 1, 2026**

🎓 MS in Artificial Intelligence @ Lawrence Technological University (GPA 3.72 | May 2026)
🔬 Graduate Research Assistant – Medical AI
🤖 Applied AI Engineer | LLM Systems | RAG Pipelines | Agentic Workflows | Production Deployment

---

## 🔬 Research Focus

Currently working on:

- AI-driven early warning systems for pacemaker malfunction detection
- Synthetic ECG generation using GANs to address clinical data scarcity
- Federated learning for privacy-preserving distributed model training
- NLP research comparing LoRA fine-tuning, RAG, and prompt engineering for personalized dialogue generation *(paper submitted April 2026)*

---

## 🚀 Featured Projects

### 🏥 Medical RAG Assistant
Production RAG system for medical document Q&A with hybrid retrieval and evaluation

- Hybrid retrieval: ChromaDB vector search + BM25 sparse + CrossEncoder reranking
- RAGAS evaluation suite with golden test set (answer relevancy, faithfulness, context recall)
- Citation tracing — every answer links back to the exact source passage
- Deployed on Render · Stack: Python, LangChain, ChromaDB, RAGAS, Groq API, Streamlit

### 🤖 Medical Evidence Agent *(In Progress)*
Production-grade multi-agent system built on top of the Medical RAG Assistant

- LangGraph 3-agent workflow: Retrieval Agent → Reasoning Agent → Safety Agent
- Guardrails AI: hallucination detection, unsafe query refusal, PII filtering
- Pydantic structured outputs with confidence scores and LLM-as-judge quality scoring
- FastAPI async backend · JWT auth · PostgreSQL · LangSmith · MLflow · AWS S3 · Docker · GitHub Actions CI/CD

### 📝 Personalized Dialogue LLM — Comparative Study
NLP research comparing three LLM adaptation approaches · *Paper submitted April 2026*

- Comparing prompt engineering vs RAG vs LoRA fine-tuning for personality-conditioned dialogue
- 14 participants · 3 conversational domains (casual, family, academic)
- Multi-metric evaluation: BLEU, ROUGE, BERTScore across all three systems
- Stack: Python, LoRA, Hugging Face PEFT, LangChain, RAG

### ❤️ Pacemaker Malfunction Prediction *(GRA Research)*
Deep learning for clinical ECG analysis and early fault detection

- Deep learning models trained on 10,000+ ECG records across 5+ fault scenarios
- GAN-based synthetic ECG generation improving downstream model F1-score by 25%
- Federated learning for distributed training with full patient data privacy
- Stack: PyTorch, TensorFlow, GANs, Federated Learning, MLflow

### 📰 Fake News Detection — BERT Fine-tuning
Fine-tuned transformer for misinformation classification · Deployed as Flask REST API

- 93% test accuracy on real-world news datasets
- Precision/Recall optimization through attention masking and hyperparameter tuning
- Stack: Python, PyTorch, Hugging Face Transformers, Flask

---

## 🛠 Tech Stack

**LLM & Agentic AI**
LangChain · LangGraph · LangSmith · Agentic RAG · Multi-Agent Workflows · Tool Calling · Prompt Engineering · ChromaDB · BM25 · Groq API · OpenAI API

**Evaluation & Safety**
RAGAS · LLM-as-Judge · Guardrails AI · Hallucination Detection · BLEU · ROUGE · BERTScore · MLflow · Golden Test Sets

**Fine-tuning & NLP**
LoRA · QLoRA · Hugging Face PEFT · Transformers · BERT · Sentence Transformers · Cross-Encoder Reranking

**Production & Backend**
FastAPI · Asyncio · Pydantic · Docker · GitHub Actions CI/CD · PostgreSQL · JWT Auth · AWS S3 · Render

**ML & Deep Learning**
PyTorch · TensorFlow · Keras · scikit-learn · GANs · Federated Learning · CNNs · Reinforcement Learning

---

## 📫 Connect

LinkedIn: [linkedin.com/in/naveen-rajarapu](https://linkedin.com/in/naveen-rajarapu)
Email: [naveenrajarapu12@gmail.com](mailto:naveenrajarapu12@gmail.com)
