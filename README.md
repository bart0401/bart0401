<div align="center">

# 👋 Multi Agent AI Engineer

### Multi Agent AI Engineer | LangChain Contributor

</div>

---

## 🚀 About Me

**AI Engineer** specializing in Multi AI Agent service development.

- 🤖 **LangChain Contributor** - Contributing to the open source ecosystem
- 🔧 AI Agent architecture design and implementation expertise
- 📊 Experience developing AI solutions combining spatial and time-series data
- 🌐 Focused on building production-ready AI services

---

## 🎯 LangChain Contributions

Key contributions to the LangChain project:

### 🐛 Issues (5)

- **Agent Fallback & Middleware Compatibility Improvement** - [Issue #33129](https://github.com/langchain-ai/langchain/issues/33129)
  - Discovered and proposed solutions for type checking issues when using fallback models and middleware together in `create_agent()`

- **ModelResponse Import Issue** - [Issue #33453](https://github.com/langchain-ai/langchain/issues/33453)
  - Reported issue with directly importing `ModelResponse` class from `langchain.agents.middleware`

- **Middleware Async Support Analysis** - [Issue #33474](https://github.com/langchain-ai/langchain/issues/33474)
  - Detailed analysis and report on `NotImplementedError` caused by lack of async support in `PlanningMiddleware`, `AnthropicPromptCachingMiddleware`, and `ModelFallbackMiddleware` in LangChain 1.0.0a14

- **Documentation Deprecated Middleware Class** - [Issue #936](https://github.com/langchain-ai/docs/issues/936)
  - Reported outdated documentation using deprecated `PlanningMiddleware` instead of `TodoListMiddleware`, causing ImportError for users following official docs

- **Async Function Removal Analysis** - [Issue #174](https://github.com/langchain-ai/deepagents/issues/174)
  - Investigated disappearance of `async_create_deep_agent` in 0.0.12rc2, traced culprit to [Pull Request #171](https://github.com/langchain-ai/deepagents/pull/171) refactoring
  <hr style="border-top: 3px dotted #ccc;">

### 🔨 Pull Requests (2)

- **ModelResponse Export Fix** - [Pull Request #33454](https://github.com/langchain-ai/langchain/pull/33454) **[Merged]**
  - Added `ModelResponse` to `__init__.py` to properly export from package

- **Middleware Async Support Implementation** - [Pull Request #33475](https://github.com/langchain-ai/langchain/pull/33475) **[Closed - Duplicate]**
  - Implemented `awrap_model_call` method for `PlanningMiddleware` and `ModelFallbackMiddleware` to support async agent calls
  - Enables middleware usage in FastAPI, WebSocket, LangGraph and other async environments
---

## 🛠️ Tech Stack

### 🤖 AI Agent Frameworks & Tools
<div align="left">
    <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white"/>
    <img src="https://img.shields.io/badge/LangGraph-FF6B6B?style=flat-square&logo=graphql&logoColor=white"/>
    <img src="https://img.shields.io/badge/DeepAgents-4A90E2?style=flat-square"/>
    <img src="https://img.shields.io/badge/LangChain_MCP_Adapters-2C3E50?style=flat-square"/>
    <img src="https://img.shields.io/badge/FastMCP-00D9FF?style=flat-square"/>
</div>

### 🧠 ML/DL & Model Training
<div align="left">
    <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
    <img src="https://img.shields.io/badge/Transformers-FF9D00?style=flat-square&logo=huggingface&logoColor=white"/>
    <img src="https://img.shields.io/badge/Sentence_Transformers-00B8D4?style=flat-square&logo=huggingface&logoColor=white"/>
    <img src="https://img.shields.io/badge/PEFT-9B59B6?style=flat-square&logo=huggingface&logoColor=white"/>
    <img src="https://img.shields.io/badge/vLLM-5C4EE5?style=flat-square&logo=v&logoColor=white"/>
    <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
    <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
    <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
    <img src="https://img.shields.io/badge/Unsloth-FF6B35?style=flat-square&logo=lightning&logoColor=white"/>
    <img src="https://img.shields.io/badge/Ray-028CF0?style=flat-square&logo=ray&logoColor=white"/>
</div>

### 📊 Data Processing & Analysis
<div align="left">
    <img src="https://img.shields.io/badge/GeoPandas-9370DB?style=flat-square&logo=python&logoColor=white"/>
    <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
    <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
    <img src="https://img.shields.io/badge/Matplotlib-11557c?style=flat-square&logo=python&logoColor=white"/>
    <img src="https://img.shields.io/badge/Seaborn-7DB0BC?style=flat-square&logo=python&logoColor=white"/>
    <img src="https://img.shields.io/badge/Spatial Analysis-9370DB?style=flat-square"/>
    <img src="https://img.shields.io/badge/Time Series Analysis-DF7401?style=flat-square"/>
</div>

### 🗄️ Vector Databases
<div align="left">
    <img src="https://img.shields.io/badge/PGVector-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
    <img src="https://img.shields.io/badge/Milvus-00A1EA?style=flat-square&logo=milvus&logoColor=white"/>
    <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white"/>
</div>

### 💾 Databases
<div align="left">
    <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
    <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white"/>
    <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
    <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
    <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
</div>

### ⚡ Message Queue & Task Management
<div align="left">
    <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white"/>
    <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white"/>
</div>

### 🌐 API Development & ORM
<div align="left">
    <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
    <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white"/>
    <img src="https://img.shields.io/badge/Alembic-6BA81E?style=flat-square"/>
</div>

---

<div align="center">

**"An Engineer Proving AI Service Value Through Research & Development"**

[![LangChain](https://img.shields.io/badge/LangChain-Contributor-1C3C3C?style=for-the-badge)](https://github.com/langchain-ai/langchain)

</div>
