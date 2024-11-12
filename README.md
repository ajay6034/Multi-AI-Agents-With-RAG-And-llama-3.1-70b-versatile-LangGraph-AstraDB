# Multi-AI-Agents-With-RAG-And-llama-3.1-70b-versatile-LangGraph-AstraDB
## LLM-Based Autonomous Agent System
- This project demonstrates an autonomous agent system driven by a large language model (LLM) at its core. The system integrates LLMs with components like Retrieval-Augmented Generation (RAG) and Wikipedia-based question-answering to create a comprehensive and interactive query-answering experience.

### Project Overview
- In this LLM-powered agent system, the model acts as the "brain" of the agent, capable of understanding user queries, generating responses, and retrieving relevant data. Inspired by popular concepts like AutoGPT and GPT-Engineer, this project showcases how an LLM can serve as a general problem solver beyond simple text generation.

### Core Components
1. Question Routing: Determines whether a query should be routed to RAG or Wikipedia search based on keywords.
2. RAG Retrieval: Uses a retrieval-augmented approach to fetch specific documents related to the query.
3. Wikipedia Search: For general knowledge queries, the system accesses Wikipedia for accurate summaries.

### Workflow
- The workflow consists of nodes for question routing, RAG retrieval, and Wikipedia search. 
Based on the input, it either:
Retrieves documents via RAG if detailed responses are needed.
Accesses Wikipedia to provide summaries for general questions.

## Sample Outputs Genearated

### Output Genearated Through Retriever(AstraDB)
![image](https://github.com/user-attachments/assets/7a691900-6f84-478b-9fa4-72fda24403ba)

### Outpput Genearted Through WikiSearch
![image](https://github.com/user-attachments/assets/0fe494c0-7a2a-4f11-a945-11a4ce0aa0d3)

