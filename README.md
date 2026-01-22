# This repository includes 2 GenAI Projects

# 🤖 HRAssistant : AI-Powered HR Employee Onboarding Agent
  ## 🚀 Features
  - **Candidate Profiling**: Automatically extract and summarize details from resumes/CSV records.
  - **Semantic Search**: Use vector storage (ChromaDB) to find the right employees or candidates based on skills, not just keywords.
  - **Traceable Memory**: Built-in JSON memory to track agent reasoning and sources for every answer.
  - **Context-Aware Insights**: Answers complex HR queries by combining internal documentation with pre-trained LLM knowledge.
# 🏙️  News Reporter  : AI-Powered Top News reporting tool
  ## 🚀 Features
  - Load URLs to fetch article content.
  - Process article content through LangChain's UnstructuredURL Loader
  - Construct an embedding vector using HuggingFace embeddings and leverage ChromaDB as the vectorstore, to enable swift and effective  retrieval of relevant information.
  - Interact with the LLM's (Llama3 via Groq) by inputting queries and receiving answers along with source URLs.
