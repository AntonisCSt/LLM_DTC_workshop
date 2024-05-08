# RAG_QUESTIONAIRE_workshop

Tutorial reference: https://github.com/alexeygrigorev/llm-rag-workshop

## Process Flow

1. **Input**: Questions are provided as input.
2. **Look-up Question**: The questions are looked up in the database using Elastic Search.
3. **Provide Results**: Different results are generated based on the search query.
4. **Prompt LLM**: The language learning model (LLM) is prompted to answer the questions using the results.
5. **Output**: The LLM provides answers based on the results.

So need to build:

- Database
- Promt/llm
- Orchestrator

