
```markdown
<div align="center">

# 👋 Hi, I'm Ayush Kumar

**Data Scientist & Machine Learning Engineer**

Building reliable AI systems | Deep Learning | GenAI | MLOps

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ayushsyntax)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://kaggle.com/ayushsyntax)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:your.email@example.com)

![Profile Views](https://komarev.com/ghpvc/?username=ayushsyntax&color=blueviolet&style=flat-square)

</div>

---

## 🚀 About Me

```python
class DataScientist:
    def __init__(self):
        self.name = "Ayush Kumar"
        self.role = "ML Engineer & Data Scientist"
        self.education = "B.Tech in AI & Data Science"
        self.location = "Delhi, India"
        
    def current_focus(self):
        return [
            "Building agentic AI systems with LangGraph",
            "Production ML pipelines with MLOps",
            "Deep learning from first principles",
            "RAG systems and LLM orchestration"
        ]
    
    def philosophy(self):
        return "Build from scratch. Understand deeply. Deploy reliably."
```

I work on machine learning systems with focus on **reliability**, **explainability**, and **real-world deployment**. I learn by building from first principles, understanding failure modes, and iterating towards production-ready solutions.

---

## 🛠️ Tech Stack

<div align="center">

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### MLOps & Deployment
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### GenAI & LLMs
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### Data & Databases
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=for-the-badge&logo=databricks&logoColor=white)

</div>

---

## 📂 Featured Projects

### 🤖 [Agentic Research Assistant (ARA)](https://github.com/ayushsyntax/Agentic-Research-Assistant)

> Production-grade agentic AI with LangGraph | Tool-calling | RAG | Full Observability

**What makes it different:**
- 🧠 LLM decides when to use tools (web search, news, PDF retrieval)
- 💾 Persistent memory across sessions with LangGraph checkpointers
- 🔍 Full observability via LangSmith (traces, latency, token usage)
- 🧵 Thread-scoped vector stores for isolated research contexts
- ⚡ Low-latency Groq Llama 3.3 backend with automatic fallback

**Tech:** `LangGraph` · `LangChain` · `ChromaDB` · `SQLite` · `Streamlit` · `LangSmith` · `FastAPI`

```bash
# Quick Start
git clone https://github.com/ayushsyntax/Agentic-Research-Assistant
cd Agentic-Research-Assistant
docker-compose up
```

---

### 🏠 [End-to-End ML System: Housing Price Prediction](https://github.com/ayushsyntax/Regression_ML-End-to-End)

> Complete production pipeline | MLOps | AWS Deployment | CI/CD

**Architecture:**
```mermaid
graph LR
    A[Data Ingestion] --> B[Feature Engineering]
    B --> C[Model Training - XGBoost]
    C --> D[MLflow Tracking]
    D --> E[Model Registry - S3]
    E --> F[Docker Container]
    F --> G[AWS ECS Deployment]
    G --> H[FastAPI + Streamlit]
```

**Key Features:**
- ⏰ Proper time-series validation (2016-2023 chronological splits)
- 🔧 Unified ETL pipeline (zero train-serve skew)
- 📊 Bayesian hyperparameter tuning with Optuna
- 🚀 Docker + ECS Fargate microservices
- 🔄 GitHub Actions CI/CD with automated testing

**Tech:** `XGBoost` · `Optuna` · `MLflow` · `Docker` · `AWS (ECS, S3, ALB)` · `FastAPI`

---

### 🧬 [GPT from Scratch in PyTorch](https://github.com/ayushsyntax/GPT-from-Scratch-in-PyTorch)

> Decoder-only Transformer built from first principles | No pre-built components

**Implementation Details:**
- 6-layer decoder-only architecture (GPT-2 style)
- Custom multi-head self-attention with causal masking
- Learned positional embeddings
- Character-level tokenizer (built from scratch)
- Trained on Shakespeare's complete works (~1.1M characters)

**Results:**
```
Perplexity: 3.02
Accuracy: 64.9%
Training: ~2 hours on single GPU
```

**Tech:** `PyTorch` · `NumPy` · `Gradio`

🎯 **[Try Live Demo](https://huggingface.co/spaces/ayushsyntax/shakespeare-gpt)**

---

### 🔄 [Reasona: Self-Correcting RAG](https://github.com/ayushsyntax/Reasona)

> Adaptive RAG system using HyDE + SEAL architecture

**How it learns:**
1. **HyDE Module:** Generates hypothetical answer → retrieves better context
2. **RAG Pipeline:** Generates final answer using retrieved context
3. **Critic Agent:** Evaluates answer quality
4. **SEAL Loop:** If incorrect → creates improved Q&A pairs → updates vector DB

**Tech:** `LangChain` · `ChromaDB` · `Ollama` · `FastAPI` · `Streamlit`

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=ayushsyntax&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ayushsyntax&layout=compact&langs_count=8&theme=tokyonight&hide_border=true"/>

</div>

<div align="center">

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=ayushsyntax&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 🏆 Achievements

| Achievement | Details |
|------------|---------|
| 🥇 **Kaggle Competition** | Top 9% in Playground Series (Binary Classification) |
| 🏅 **NexHack 2025** | Top 20 Finalists from 115 teams nationwide |
| 📜 **Columbia University** | Machine Learning I Certification (2025) |
| 📜 **IIT Bombay** | Advanced Python & C++ Certifications (2025) |

---

## 💼 Experience

### **Pickl.AI** — Summer Intern (Jul-Aug 2025)
- Built binary rainfall prediction system using XGBoost with stratified cross-validation
- Achieved **89+ ROC AUC** on imbalanced dataset through feature engineering
- Deployed end-to-end ML pipeline from data ingestion to model serving

### **GirlScript Summer of Code** — Open Source Contributor (Oct 2024)
- Contributed to multiple Python ML projects via Git workflows and code reviews

### **AppSquadz** — Data Analysis Intern (Jul-Aug 2024)
- Conducted EDA on credit card transactions using Pandas, Seaborn, Matplotlib

---

## 📚 Learning Philosophy

```yaml
Approach:
  - Build from scratch before using libraries
  - Understand failure modes, not just accuracy metrics
  - Production mindset: version control, testing, monitoring
  - Learn by iterating, not by reading alone

Current Focus:
  - Transformer internals and attention mechanisms
  - Multi-agent systems with LangGraph
  - Production ML: reproducibility, observability, safety
  - AI alignment and adversarial robustness
```

> *"I prefer to build and experiment when learning, rather than treating models as black boxes."*

---

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/ayushsyntax)
[![Kaggle](https://img.shields.io/badge/Kaggle-Follow-20BEFF?style=for-the-badge&logo=kaggle)](https://kaggle.com/ayushsyntax)
[![Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2?style=for-the-badge&logo=twitter)](https://x.com/AyushSyntax)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail)](mailto:your.email@example.com)

</div>

---

<div align="center">

### 💡 Currently Building

🔨 Multi-agent systems for research automation  
🧪 Experimenting with chain-of-thought prompting strategies  
📖 Contributing to open-source ML projects  

**Open to collaborate on production ML, GenAI, and MLOps projects**

</div>

---

<div align="center">

**Building slowly. Understanding deeply. Deploying reliably.**

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=ayushsyntax&theme=tokyo-night&hide_border=true&area=true)

⭐ *If you find my work helpful, consider starring the repos!*

</div>
```

