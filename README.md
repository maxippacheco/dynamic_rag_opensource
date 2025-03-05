# Dynamic RAG with Chroma and Hugging Face Llama 2

## Overview

This notebook demonstrates a dynamic Retrieval-Augmented Generation (RAG) system using Chroma and Hugging Face's Llama 2 model. It simulates a real-world scenario where rapid access to accurate information is needed, such as in a meeting or a customer support context. The system efficiently retrieves relevant information from a local Chroma collection and leverages Llama 2 to generate concise summaries.

## Key Features

- Utilizes the SciQ dataset for science question-answering tasks.
- Employs Chroma as a local vector database for cost-effective storage and retrieval.
- Embeds text using the `all-MiniLM-L6-v2` model.
- Queries the collection to retrieve relevant documents.
- Augments user prompts with retrieved documents for Llama 2 generation.
- Generates concise summaries based on the retrieved information.
