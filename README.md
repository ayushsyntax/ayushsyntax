<div align="center">

# Ayush Kumar

**Artificial Intelligence & Data Science (B.Tech 2023–2027)**  
Designing reliable machine learning and generative AI systems.

</div>

---

## Philosophy

> Build slowly. Understand deeply.  
> Systems over shortcuts. Clarity over complexity.

I am interested in how models behave in real conditions —  
where they fail, how they generalize, and how they can improve.

Most of my work focuses on:
- End-to-end ML systems  
- Transformer internals  
- Retrieval & agentic architectures  
- Deployment discipline  
- Reproducible pipelines  

I prefer building from first principles before scaling abstraction.

---

# Selected Systems

---

## 01 — Agentic Research Assistant

**Production-style LLM orchestration system built with LangGraph**

Structured reasoning loop:

User → LLM → Tool → Context → LLM → Memory → Response

Key characteristics:
- Controlled tool-calling (web, news, PDF RAG)
- Persistent memory (SQLite checkpointers)
- Thread-scoped vector stores
- RAG as a tool (retrieval is conditional, not automatic)
- Full observability via LangSmith tracing
- FastAPI backend + Streamlit interface

Focus:
Structured reasoning, controlled tool execution, inspectable state.

Repository  
https://github.com/ayushsyntax/Agentic-Research-Assistant

---

## 02 — Regression ML: End-to-End Production System

**Complete ML lifecycle with deployment discipline**

Design:
- Chronological split (Train < 2020 | Eval 2020–21 | Holdout 2022–23)
- Time-aware validation (no leakage)
- Unified feature pipeline (training–serving parity)
- High-cardinality encoding strategies
- Optuna hyperparameter search
- MLflow experiment tracking

Deployment:
- Dockerized services
- FastAPI inference layer
- Streamlit analytics dashboard
- AWS ECS Fargate deployment
- CI/CD via GitHub Actions
- Versioned artifacts in S3

Focus:
Reliability, reproducibility, and real deployment constraints.

Repository  
https://github.com/ayushsyntax/Regression_ML-End-to-End

---

## 03 — GPT from Scratch (PyTorch)

**Decoder-only transformer built and trained from first principles**

Implemented:
- Character-level tokenizer
- Learned positional embeddings
- Multi-head causal self-attention
- Pre-LayerNorm architecture
- Weight tying
- Temperature & top-k sampling
- Full training & evaluation pipeline

Evaluation:
Perplexity: 3.02  
Accuracy: 64.9%

Focus:
Understanding transformer internals by building them.

Repository  
https://github.com/ayushsyntax/GPT-from-Scratch-in-PyTorch

---

## 04 — Reasona: Self-Improving RAG

**Experimental adaptive retrieval system**

Pipeline:

Query  
→ Hypothetical answer (HyDE)  
→ Retrieval  
→ Critic  
→ Self-edit  
→ Vector store update  

Focus:
Can retrieval systems incrementally improve without retraining?

Repository  
https://github.com/ayushsyntax/Reasona

---

# Technical Stack

### Core
Python · C++ · SQL  

### Machine Learning
Scikit-Learn · XGBoost · PyTorch · TensorFlow  

### LLM & Retrieval Systems
LangGraph · LangChain · RAG · Embeddings · Tool-Calling  

### Deployment & MLOps
FastAPI · Docker · MLflow · GitHub Actions · AWS (S3, ECS, ECR)  

### Data
Pandas · NumPy · Matplotlib · Seaborn · Streamlit  

---

# Current Direction

- Transformer internals and attention behavior  
- Memory-aware agent systems  
- Evaluation of retrieval pipelines  
- Failure analysis in ML systems  
- Production trade-offs in GenAI systems  

---

# Engineering Approach

I try to keep systems:

- Understandable  
- Testable  
- Deployment-aware  
- Designed with explicit assumptions  

I learn best by building complete systems rather than isolated components.

---

<div align="center">

### Links

LinkedIn  
https://www.linkedin.com/in/ayush-kumar-0a7b85303  

X  
https://x.com/AyushSyntax  

</div>
