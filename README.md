# ai-learning-plan
This is an AI generated learning plan for me to understand the basics of AI models

## 🧠 AI Learning Plan (Introductory, Technical, and Developer-Friendly)

This is a curated 2–4 week learning plan to get a hands-on understanding of modern AI, especially large language models (LLMs), with a focus on coding, infrastructure, and privacy-aware local usage.

---

## ✅ Week 1–2: Core Concepts + Hands-on LLMs

### 🎓 [Hugging Face NLP Course (Chapters 1–4)](https://huggingface.co/learn/nlp-course/chapter1)
- [ ] ✅ Chapter 1: Introduction & Pipelines
- [ ] ✅ Chapter 2: Tokenizers & Transformers
- [ ] ✅ Chapter 3: Pretrained Models & Inference
- [ ] ✅ Chapter 4: Behind the Scenes (Model internals)
- 📌 Hands-on with Python + `transformers` library

### 🧪 [OpenAI Cookbook (Basic Usage)](https://github.com/openai/openai-cookbook#example-notebooks)
- [ ] ✅ Try simple completions and summaries
- [ ] ✅ Use embeddings for similarity search
- [ ] ✅ Optional: Build a CLI tool that summarizes a file

---

## ✅ Week 3: Infra & ML System Design

### 🧱 [Full Stack Deep Learning – Lecture 1: ML System Overview](https://www.youtube.com/watch?v=0wUF_Ov8b0A)
- [ ] ✅ Watch Lecture 1 (~1.5h)
- [ ] ✅ Reflect on lifecycle: Data → Training → Inference → Monitoring

### ⚙️ [MLOps Zoomcamp – Week 1](https://github.com/DataTalksClub/mlops-zoomcamp)
- [ ] ✅ Experiment tracking with MLflow
- [ ] ✅ Intro to data/version control tools
- [ ] ✅ Understand key infra concepts (reproducibility, pipelines)

---

## ✅ Optional Week 4: Dive Deeper (Pick Based on Interest)

### 🛠️ Local Model Use (Ollama, LM Studio, llama.cpp)
- [ ] ✅ [Install Ollama](https://ollama.com/)
- [ ] ✅ Pull a model like `deepseek-coder` or `mistral`
- [ ] ✅ Try local inference with private code input

### 📚 LangChain or LlamaIndex
- [ ] ✅ [LangChain Quickstart](https://docs.langchain.com/docs/get-started/introduction)
- [ ] ✅ [LlamaIndex: Load & query a codebase](https://docs.llamaindex.ai/en/stable/getting_started/starter_example.html)

### 🧩 Mini-project Ideas
- [ ] 🔧 Build a CLI tool that analyzes code comments
- [ ] 🔧 Set up a retrieval-augmented generation (RAG) system on a repo
- [ ] 🔧 Wrap a local LLM with a FastAPI interface

---

## 📌 Tools Overview

| Tool             | Purpose                                        |
|------------------|------------------------------------------------|
| Hugging Face     | Pretrained models, tokenizers, pipelines       |
| OpenAI API       | Easy access to GPT-like models via code        |
| Full Stack DL    | Understand system architecture of ML apps      |
| MLOps Zoomcamp   | Learn about production ML tools & tracking     |
| Ollama / LMStudio| Run local LLMs privately on your own machine   |
| LangChain        | Build LLM apps using chains and memory         |
| LlamaIndex       | Codebase indexing + smart retrieval            |

---

## 📝 Notes
- Keep everything local to avoid leaking code or data.
- Hugging Face models can be used offline via `transformers`.
- Ollama and LM Studio are great for local experimentation.
- If something “clicks,” dive deeper into training or infra next.

---
