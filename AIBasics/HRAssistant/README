# 🤖 HRAssistant — AI-Powered HR Employee Onboarding Agent

HRAssistant is an intelligent agent designed to streamline HR workflows of Employee Onboarding
 Parsing candidate information,
 Searching internal employee records,
 Providing data-driven insights for HR managers.

It leverages **Retrieval-Augmented Generation (RAG)** and **Agentic Reasoning** to provide accurate answers based on your private organizational data.

## 🚀 Features

- **Candidate Profiling**: Automatically extract and summarize details from resumes/CSV records.
- **Semantic Search**: Use vector storage (ChromaDB) to find the right employees or candidates based on skills, not just keywords.
- **Traceable Memory**: Built-in JSON memory to track agent reasoning and sources for every answer.
- **Context-Aware Insights**: Answers complex HR queries by combining internal documentation with pre-trained LLM knowledge.

## 🛠️ Tech Stack

- **Language**: Python 3.11
- **Orchestration**: LangChain / LangGraph (logic for reasoning loops)
- **Embeddings**: HuggingFace (`sentence-transformers`)
- **Vector Database**: ChromaDB
- **Environment Management**: `uv` or `virtualenv`
- **Frontend**: Streamlit (optional for UI)

## 📁 Project Structure

```text
HRAssistant/
├── files/              # Raw data (CSV, PDF, etc.)
├── memory/             # Persistent JSON memory for agent state
├── main.py             # Entry point for the HR Agent
├── rag_pipeline.py     # Document loading and indexing logic
└── requirements.txt    # Project dependencies
```
Setup Instructions
1. Environment Setup
Ensure you have uv installed or use a standard virtual environment:``` bash
# Using uv (Recommended)
uv venv
source .venv/bin/activate

# Install dependencies
uv pip install -r requirements.txt
```

2. Configuration
Create a .env file in the project root and add your API credentials:``` text
GROQ_API_KEY=your_groq_key_here
OPENAI_API_KEY=your_openai_key_here
COMPANY_CSV_PATH=files/employee_records.csv
MEMORY_JSON_PATH=memory/hr_agent_memory.json
```

3. Data Ingestion
Place your HR data (e.g., candidate_records.csv) into the files/ directory. The agent will index these files into ChromaDB on the first run.
🚦 Usage
Run the agent via the terminal or start the Streamlit dashboard:``` bash
# Terminal Mode
python main.py

# Dashboard Mode
streamlit run main.py
```


