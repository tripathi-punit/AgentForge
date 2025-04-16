# AgentForge
Exploring agentic architectures using LlamaIndex for intelligent retrieval and CrewAI for multi-agent orchestration.

# 🧠 AgentForge: Agentic Intelligence with LlamaIndex + CrewAI

Welcome to **AgentForge** – an experimental playground for exploring **agentic behavior** using **LlamaIndex** and **CrewAI**.

---

## 🚀 Objectives

- Integrate LlamaIndex and CrewAI to create autonomous, context-aware agents
- Implement **Model Context Protocol (MCP)** 
- Explore **Chain-of-Thought (CoT)** prompting using agents
- Test multi-agent coordination and Agent-to-Agent (A2A) interactions

---

## 📌 Tasks (Tracked via GitHub Project Board)

1. Integrate basic CrewAI agent
2. Integrate LlamaIndex workflow in multi-agent setup
3. Create retrieval agent with LlamaIndex and test end-to-end agent chain
4. Incorporate MCP (Model Context Protocol)
5. Try A2A (Agent-to-Agent) approach

---

## 🧪 Fancy Use Case Ideas (Optional Experiments)

- 🔍 **Legal Assistant Agents** – One agent reads contracts, another summarizes, a third flags risk
- 📖 **Personal Tutor** – A teaching agent uses CoT to break down complex topics interactively
- 🤖 **RAG Chatbot with Memory** – Contextual chatbot that remembers conversations using LlamaIndex
- 💡 **Idea Generator** – Agents brainstorm startup ideas based on your interests and market trends
- 🧬 **Research Synthesizer** – One agent fetches academic papers, another creates a literature summary

---

## 🧰 Tech Stack

- [LlamaIndex](https://github.com/jerryjliu/llama_index)
- [CrewAI](https://github.com/joaomdmoura/crewAI)
- Python 3.10+
- OpenAI, Ollama, or local LLM backends (configurable)

---

## 📦 Setup

```bash
git clone https://github.com/tripathi-punit/agentforge.git
cd agentforge
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
