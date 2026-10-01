# rag-pipeline

![Python](https://img.shields.io/badge/python-3.10%2B-blue?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/status-in%20progress-yellow)

## Introduction

**rag-pipeline** is a Retrieval-Augmented Generation (RAG) pipeline that
lets a language model answer questions using your own documents instead of
relying only on what it learned during training.

## What is RAG?

Large language models are powerful, but they can be out of date and may
make up answers when they don't know something. RAG addresses this by
adding a retrieval step before generation:

1. **Ingest**: load documents and split them into smaller chunks.
2. **Embed and index**: convert each chunk into a vector and store it in a
   searchable index.
3. **Retrieve**: for a user's question, find the most relevant chunks.
4. **Generate**: give those chunks to the language model as context so it
   can produce a grounded answer.

## Project Status

This project is under active development. Features, structure, and
documentation will evolve as it progresses.