# 🚀 LangGraph Agents — Modular Multi-Agent Framework

A modular, production-ready framework for building intelligent **multi-agent systems** using **LangGraph**.  
This repository contains a growing collection of **fully working LangGraph agents**, each demonstrating a unique workflow, tool integration, and state-management pattern.

Designed for:

- 🔥 Rapid prototyping  
- 🧱 Reusable graph components  
- 🧠 Advanced tool-calling logic  
- 🌓 Deterministic + stochastic workflows  
- 📦 Clean, extendable architecture for multiple agents  

---

# 📚 Table of Contents

- [Overview](#-overview)
- [Agents Included](#-agents-included)
  - [1. Random Sports Selector Agent](#1-random-sports-selector-agent)
  - [2. Arxiv & Web Research Assistant](#2-arxiv--web-research-assistant)
  - [3. Upcoming Agents](#3-upcoming-agents)
- [Tech Stack](#-tech-stack)
- [Setup](#-setup)
- [Project Structure](#-project-structure)
- [License](#-license)

---

# 🔥 Overview

This repository provides a **scalable LangGraph agent collection** with reusable patterns for:

- State management using `TypedDict`
- Conditional and deterministic edges
- Tool-enabled LLM nodes
- Multi-step workflows and orchestration
- Visualization-ready graph pipelines  
- Clean, production-friendly design

Each agent lives in its own notebook/module so you can easily extend or reuse logic.

---

# 🤖 Agents Included

## 🟢 **1. Random Sports Selector Agent**
*A simple but complete demonstration of conditional edges, state mutation, and graph execution.*

This agent:

- Initializes a **state dictionary**
- Runs a **start node**
- Uses randomness to choose between:
  - 🏏 **Cricket node**
  - 🏸 **Badminton node**
- Ends the graph flow after one branch

### 🔧 Core Features
- `TypedDict`-based state  
- Random conditional routing  
- Modular node definitions  
- Fully visualizable graph  

---

## 🔵 **2. Arxiv & Web Research Assistant**
A Groq-powered research agent integrating:

- Arxiv search  
- Wikipedia lookup  
- Tavily Web Search  
- LangChain tool binding  
- LangGraph workflow orchestration  

Perfect for AI research workflows, automated literature review, and intelligent information gathering.

---

## 🟣 **3. Upcoming Agents**
New agents will be added here, such as:

- Code Execution Agents  
- Memory-Augmented Workflow Agents  
- Multi-Tool Reasoning Agents  
- API Integration Agents  

Stay tuned!

---

# 🧰 Tech Stack

- **LangGraph**
- **LangChain**
- **Groq LLMs**
- **Tavily Search**
- **Python 3.10+**

---

# 📦 Setup

```bash
pip install langchain langgraph langchain-core langchain-community
pip install langchain-groq python-dotenv tavily-python
```

---

# 📁 Project Structure

```
LangGraph-Agents/
│── agents/
│   ├── random_sports_selector.ipynb
│   ├── arxiv_web_research_agent.ipynb
│── README.md
│── requirements.txt
```

---

# 📄 License
MIT License  
