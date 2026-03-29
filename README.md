<div align="center">

# :brain: Large Language Models (LLM)

### Fine-tuning, prompt engineering, RAG systems, AI agents, and LLM evaluation

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/)
[![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white)](https://www.anthropic.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)
[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)](https://www.langchain.com/)

</div>

---

## Overview

A portfolio of Large Language Model projects spanning fine-tuning, prompt engineering, retrieval-augmented generation, autonomous agents, tool use, and rigorous evaluation. Each project demonstrates practical applications of LLMs in production-grade systems with a focus on reliability, safety, and performance.

## Topics Covered

| # | Topic | Description | Status |
|---|-------|-------------|--------|
| 1 | **Prompt Engineering** | Advanced prompting techniques: chain-of-thought, few-shot, self-consistency, and structured outputs | :construction: Planned |
| 2 | **Fine-Tuning** | LoRA, QLoRA, and full fine-tuning of open-source models for domain-specific tasks | :construction: Planned |
| 3 | **RAG Systems** | Retrieval-Augmented Generation with vector databases, chunking strategies, and reranking | :construction: Planned |
| 4 | **AI Agents** | Autonomous agents with planning, memory, and multi-step reasoning | :construction: Planned |
| 5 | **Tool Use & Function Calling** | Equipping LLMs with external tools, APIs, and structured function calling | :construction: Planned |
| 6 | **Evaluation & Benchmarking** | LLM-as-judge, automated evaluation pipelines, and custom benchmark design | :construction: Planned |
| 7 | **Embedding Models** | Sentence embeddings, semantic search, and clustering with embedding models | :construction: Planned |
| 8 | **Multi-Modal LLMs** | Vision-language models, image understanding, and multi-modal RAG | :construction: Planned |
| 9 | **Guardrails & Safety** | Output filtering, constitutional AI, content moderation, and prompt injection defense | :construction: Planned |
| 10 | **Deployment & Serving** | vLLM, TGI, quantization (GPTQ, AWQ), and efficient inference at scale | :construction: Planned |

## Tech Stack

| Category | Tools |
|----------|-------|
| **Languages** | Python |
| **LLM Providers** | Anthropic (Claude), OpenAI (GPT), Google (Gemini) |
| **Frameworks** | LangChain, LlamaIndex, Haystack |
| **Fine-Tuning** | HuggingFace Transformers, PEFT, TRL, Axolotl |
| **Vector Databases** | ChromaDB, Pinecone, Weaviate, FAISS |
| **Evaluation** | RAGAS, DeepEval, LangSmith |
| **Serving** | vLLM, Text Generation Inference, Ollama |

## Project Structure

```
LLM/
|-- prompt_engineering/     # Prompting techniques & templates
|-- fine_tuning/            # Model fine-tuning experiments
|-- rag/                    # RAG system implementations
|-- agents/                 # Autonomous agent projects
|-- tool_use/               # Tool use & function calling
|-- evaluation/             # Evaluation pipelines & benchmarks
|-- embeddings/             # Embedding models & semantic search
|-- notebooks/              # Exploratory notebooks
|-- utils/                  # Shared utilities
`-- README.md
```

## Getting Started

```bash
# Clone the repository
git clone https://github.com/DatariusAI/LLM.git
cd LLM

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Set up API keys
cp .env.example .env
# Add your API keys to .env
```

## Roadmap

- [ ] Prompt engineering cookbook with Claude, GPT, and Gemini
- [ ] Fine-tune Llama/Mistral with QLoRA for domain tasks
- [ ] Production RAG pipeline with evaluation
- [ ] Multi-agent system with tool use
- [ ] LLM evaluation framework and custom benchmarks
- [ ] Guardrails and safety layer implementation
- [ ] Efficient serving with quantization comparison

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Part of the [DatariusAI](https://github.com/DatariusAI) portfolio**

</div>
