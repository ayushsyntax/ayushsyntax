
Everything I build fits somewhere in this map.

---

# 03. Flagship Systems

---

## Agentic Research Assistant

Structured LLM orchestration with LangGraph.

Design principles:
- Retrieval as a tool, not an automatic crutch
- Persistent memory via SQLite checkpointers
- Thread-scoped vector stores
- Guarded tool invocation
- Full trace inspection with LangSmith

Architecture:
User → Reasoning Node → Tool → Context → Memory → Response

Why it matters:
Most agent demos hide state. This one exposes it.

Repository  
https://github.com/ayushsyntax/Agentic-Research-Assistant

---

## End-to-End Regression ML System

A full ML lifecycle project built for production realism.

Engineering decisions:
- Strict chronological splits
- No leakage validation
- Unified training/inference pipeline
- Hyperparameter tuning with Optuna
- MLflow artifact versioning
- Dockerized services
- AWS ECS deployment
- CI/CD via GitHub Actions

Why it matters:
Training code and inference code are identical pipelines.

Repository  
https://github.com/ayushsyntax/Regression_ML-End-to-End

---

## GPT from Scratch (PyTorch)

Decoder-only transformer trained on ~1.1M characters of Shakespeare.

Built manually:
- Tokenization
- Positional embeddings
- Multi-head attention
- Pre-LayerNorm
- Weight tying
- Sampling strategies

Evaluation:
Perplexity: 3.02  
Accuracy: 64.9%

Why it matters:
Understanding transformer mechanics beyond API usage.

Repository  
https://github.com/ayushsyntax/GPT-from-Scratch-in-PyTorch

---

## Reasona — Self-Improving RAG

HyDE + Critic + Self-edit + Vector update.

Exploration:
Can retrieval systems improve incrementally without retraining the base model?

Repository  
https://github.com/ayushsyntax/Reasona

---

# 04. Technical Surface Area

Languages  
Python · C++ · SQL  

ML  
Scikit-Learn · XGBoost · PyTorch · TensorFlow  

LLM Systems  
LangGraph · LangChain · RAG · Embeddings · Tool Calling  

Infrastructure  
FastAPI · Docker · MLflow · GitHub Actions · AWS  

Data  
Pandas · NumPy · Matplotlib · Streamlit  

---

# 05. Lessons from Building Systems

• Data leakage is subtle and unforgiving  
• Training accuracy does not equal production reliability  
• Agent systems require guardrails, not just prompts  
• Observability reduces hallucinated confidence  
• Clean pipelines save more time than clever hacks  

Complexity grows naturally.  
Clarity must be engineered.

---

# 06. Current Direction

- Transformer internals
- Memory-aware agents
- Retrieval evaluation metrics
- Production trade-offs in GenAI
- Failure-mode documentation

---

<div align="center">

### Build slowly. Understand deeply.

[LinkedIn](https://www.linkedin.com/in/ayush-kumar-0a7b85303)  
[X](https://x.com/AyushSyntax)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3A6EA5,100:1F2937&height=120&section=footer"/>
