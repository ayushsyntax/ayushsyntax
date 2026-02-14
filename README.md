

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3A6EA5,100:6E44FF&height=160&section=header&text=Ayush%20Kumar&fontSize=40&fontColor=ffffff&animation=fadeIn"/>

### 🧠 Artificial Intelligence & Data Science (2023–2027)

Building reliable machine learning & generative AI systems  
that behave well outside the notebook.

<br>

<img src="https://img.shields.io/badge/Python-3A6EA5?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-222222?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge"/>

</div>

---

## 🌿 A Slice of Life

Some evenings are spent debugging a data leak that only appears after deployment.  
Some nights are spent tracing an LLM tool-call that went one step too far.  
Some mornings are just cleaning pipelines so future me doesn’t suffer.

I like building full systems — not just models.

Raw Data  
→ Feature Engineering  
→ Training  
→ Validation  
→ Deployment  
→ Monitoring  
→ Reflection  

What interests me most:
- Where systems fail
- How retrieval improves over time
- How agents reason with tools
- How to reduce silent failure in production

I prefer clarity over cleverness.

---

# 🗺 System Map

```

```
                 ┌──────────────────────┐
                 │      Raw Data        │
                 └────────────┬─────────┘
                              │
                              ▼
                 ┌──────────────────────┐
                 │ Feature Engineering  │
                 └────────────┬─────────┘
                              │
                              ▼
                 ┌──────────────────────┐
                 │     Model Training   │
                 └────────────┬─────────┘
                              │
                              ▼
                 ┌──────────────────────┐
                 │   Evaluation & CV    │
                 └────────────┬─────────┘
                              │
                              ▼
                 ┌──────────────────────┐
                 │  API / Agent Layer   │
                 └────────────┬─────────┘
                              │
                              ▼
                 ┌──────────────────────┐
                 │ Deployment (Docker)  │
                 └────────────┬─────────┘
                              │
                              ▼
                 ┌──────────────────────┐
                 │ Observability Layer  │
                 │ (Logs, Traces, MLflow│
                 └──────────────────────┘
```

```

Everything I build fits somewhere inside this map.

---

# 🧩 Selected Systems

---

## 🔵 Agentic Research Assistant

A structured LLM orchestration system using LangGraph.

Workflow:

User  
→ LLM reasoning node  
→ Tool call (web/news/PDF)  
→ Context aggregation  
→ Memory update  
→ Final response  

Key characteristics:
- Conditional RAG
- Persistent SQLite memory
- Thread-scoped vector stores
- Tool-calling with guardrails
- LangSmith tracing
- FastAPI + Streamlit interface

Focus:
Making reasoning loops inspectable and controllable.

Repository  
https://github.com/ayushsyntax/Agentic-Research-Assistant

---

## 🟠 Regression ML — End-to-End System

A production-grade ML lifecycle project.

Design:
- Strict chronological splits
- No leakage validation
- Unified feature pipeline (train = serve)
- Optuna tuning
- MLflow tracking

Deployment:
- Dockerized services
- FastAPI inference
- Streamlit dashboard
- AWS ECS Fargate
- CI/CD with GitHub Actions

Focus:
Reducing training–serving mismatch.

Repository  
https://github.com/ayushsyntax/Regression_ML-End-to-End

---

## 🟣 GPT from Scratch (PyTorch)

Decoder-only transformer trained on Shakespeare (~1.1M characters).

Built from fundamentals:
- Character tokenizer
- Learned positional embeddings
- Multi-head causal self-attention
- Pre-LayerNorm architecture
- Temperature & top-k sampling

Evaluation:
Perplexity: 3.02  
Accuracy: 64.9%

Focus:
Understanding transformers by implementing them.

Repository  
https://github.com/ayushsyntax/GPT-from-Scratch-in-PyTorch

---

## 🟢 Reasona — Self-Improving RAG

Experimental adaptive retrieval system.

Pipeline:
HyDE → Retrieval → Critic → Self-edit → Vector update

Focus:
Incremental improvement without full retraining.

Repository  
https://github.com/ayushsyntax/Reasona

---

# 🛠 Technical Stack

Core  
Python · C++ · SQL  

ML  
Scikit-Learn · XGBoost · PyTorch · TensorFlow  

LLM Systems  
LangGraph · LangChain · RAG · Embeddings · Tool Calling  

Deployment  
FastAPI · Docker · MLflow · GitHub Actions · AWS  

Data  
Pandas · NumPy · Matplotlib · Seaborn · Streamlit  

---

# 📘 Lessons Learned the Hard Way

• Data leakage hides quietly until deployment  
• A unified feature pipeline prevents silent inference bugs  
• Tool-calling without guardrails creates hallucinated authority  
• Observability is not optional in agent systems  
• Clean structure saves more time than clever shortcuts  
• Training accuracy means nothing without future-safe validation  

Systems teach humility.

---

# 🔭 Currently Exploring

- Transformer attention behavior
- Memory-aware agents
- Retrieval evaluation metrics
- Failure-mode analysis
- Production trade-offs in GenAI systems

---

# ☀️ Philosophy

Build slowly.  
Understand deeply.  
Let clarity compound.  

---

<div align="center">

### 🌐 Connect

[LinkedIn](https://www.linkedin.com/in/ayush-kumar-0a7b85303)  
[X](https://x.com/AyushSyntax)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6E44FF,100:3A6EA5&height=120&section=footer"/>
```

