# LLM-Agent-Writer
Multi-agent LLM system for research, structured content planning, and article generation with traceable reasoning and UI.

# 🧠 LLM-Agent-Writer

A modular multi-agent system built with Large Language Models (LLMs) that can autonomously research, plan, and write structured content such as articles and blog posts. Powered by OpenAI/LLM APIs, LangChain, and Streamlit UI.

![Architecture Diagram](./assets/llm_agent_writer_architecture.png) <!-- (optional - place your diagram here) -->
<img width="876" height="609" alt="Screenshot 2025-08-01 at 16 00 19" src="https://github.com/user-attachments/assets/d7bed381-f827-4bd4-9556-9e2642454593" />


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
<img width="876" height="609" alt="Screenshot 2025-08-01 at 16 00 19" src="https://github.com/user-attachments/assets/c0da9e7d-a9d3-4759-98d1-693009328e38" />

---

## 📁 Project Structure

<img width="876" height="609" alt="Screenshot 2025-08-01 at 16 00 19" src="https://github.com/user-attachments/assets/db44f5f3-12bd-4ba9-8af1-8c287652ab70" />

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
