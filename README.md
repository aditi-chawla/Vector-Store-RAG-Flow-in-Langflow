# Vector Store RAG with Langflow & watsonx.ai

This repository contains a **Retrieval-Augmented Generation (RAG) pipeline** built with **Langflow**, using **IBM watsonx.ai** for both **embeddings** and **LLMs**.

## Features

* Document ingestion with automatic text chunking (configurable size & overlap).
* Embedding generation via **watsonx.ai Embedding models**.
* Vector storage and similarity search with **Chroma** (can be swapped with Milvus, Pinecone, etc.).
* Query-time retrieval of top-k relevant chunks.
* Prompt template for grounded Q\&A, enriched with retrieved context.
* Answer generation using **watsonx.ai LLMs** (e.g., Granite models).
* Fully visual, no-code/low-code orchestration via **Langflow**.

## Contents

* `v2 - Vector Store RAG.json` → Langflow flow configuration (import directly into Langflow).
* Example prompts and setup instructions.
* Documentation on integrating watsonx.ai API keys and configuring the flow.

## Getting Started

1. Clone this repo.
2. Import the provided JSON flow into **Langflow**.
3. Configure watsonx.ai API credentials in the embedding and LLM nodes.
4. Upload documents, run queries, and get contextual answers.

## Benefits

* Enterprise-ready RAG with IBM watsonx.ai.
* Easy to customize and extend (re-ranking, moderation, etc.).
* Visual development with Langflow for faster iteration.

