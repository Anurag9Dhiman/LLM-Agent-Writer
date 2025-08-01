# LLM-Agent-Writer
Multi-agent LLM system for research, structured content planning, and article generation with traceable reasoning and UI.

# 🧠 LLM-Agent-Writer

A modular multi-agent system built with Large Language Models (LLMs) that can autonomously research, plan, and write structured content such as articles and blog posts. Powered by OpenAI/LLM APIs, LangChain, and Streamlit UI.

![Architecture Diagram](./assets/llm_agent_writer_architecture.png) <!-- (optional - place your diagram here) -->



---

## 🚀 Features

- ✍️ **Content Generation**: From topic input to full article via planning and writing agents.
- 🔍 **Research Agent**: Performs searches, gathers context, and extracts relevant facts.
- 🧩 **Planning Agent**: Structures content flow, generates outlines and section breakdowns.
- 📄 **Writing Agent**: Composes detailed content section by section using LLMs.
- 🪞 **Tooling**: Built-in tools for web search, Markdown rendering, summarization, and citation tracking.
- 🧪 **Agent Logs**: Tracks reasoning steps, LLM prompts/responses, and tool outputs.
- 🖼️ **Streamlit UI**: Simple frontend to input topics, view logs, and download generated articles.

---

## 🧱 Architecture

> This system is built around **autonomous agents** communicating via shared memory and tools.


See: [`architecture_diagram.png`](./assets/llm_agent_writer_architecture.png)


---

## 📁 Project Structure

<img width="422" height="616" alt="Screenshot 2025-08-01 at 16 14 14" src="https://github.com/user-attachments/assets/bdf445fd-1b22-4d37-b36f-ce569acc4713" />


---

## ⚙️ Setup & Installation

1. **Clone the repo**:
   ```bash
   git clone https://github.com/Anurag9Dhiman/LLM-Agent-Writer.git
   cd LLM-Agent-Writer

pip install -r requirements.txt


streamlit run ui/app.py

## Example Use Case

Research from real sources

Outline with introduction, body, conclusion

Full article with markdown formatting and citations

All intermediate steps traceable

## 
