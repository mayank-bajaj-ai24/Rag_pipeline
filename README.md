# RAG Pipeline for Therapy Data

This repository contains a simple **Retrieval-Augmented Generation (RAG)** pipeline built around therapy and mental-health related documents. [web:178]

## Features

- Load data from Excel and PDF therapy-related datasets.
- Clean and chunk long texts into overlapping segments.
- Create embeddings using `sentence-transformers`.
- Build a FAISS vector index for efficient similarity search.
- Retrieve top‑k relevant chunks for a user query.
- Designed to run locally on CPU with configurable batch sizes and row limits.
