# 🤖 Agentic AI Patterns – Python Implementations

This repository demonstrates multiple foundational **Agent Design Patterns** using simple Python examples.

It includes:

- ✅ ReAct Agent  
- ✅ CodeAct Agent  
- ✅ Modern Tool Use (MCP Pattern)  
- ✅ Self-Reflection Agent  
- ✅ Multi-Agent Workflow  
- ✅ Agentic RAG (Retrieval-Augmented Generation)  

These are minimal implementations designed to clearly explain core agentic concepts.

---

# 📁 Project Structure
├── ReActAgent.py
├── CodeActAgent.py
├── ModernToolAgent.py
├── SelfReflectAgent.py
├── MultiAgentWorkflow.py
├── AgenticRAG.py
└── README.md

---

# 🧠 What Are Agentic AI Patterns?

Agentic AI systems are AI architectures where models:

- Reason step-by-step
- Use tools
- Execute actions
- Reflect and self-correct
- Collaborate with other agents
- Retrieve external memory/context

This repository covers six foundational patterns.

---

# 1️⃣ ReAct Agent (Reason + Act)

## 📄 File: `ReActAgent.py`

### 🔍 Concept

ReAct stands for:

> **Reason → Act → Observe → Answer**

The agent:
1. Reasons about a query
2. Uses a tool (search)
3. Returns an answer

### 🔁 Flow
User Query
↓
Reason()
↓
Act() (tool usage)
↓
Final Answer

### ▶️ Run

```bash
python ReActAgent.py
Example Output
Reasoning about: What is the capital of France?
Reasoning: Let's search online for this information.
Using search tool...
The capital of France is Paris.
🧠 Real-World Usage

Tool-calling LLMs (ChatGPT tools)

Web-search augmented reasoning

Research assistants

Planning agents
