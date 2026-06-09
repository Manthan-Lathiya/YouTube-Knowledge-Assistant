# YouTube Knowledge Assistant

## Overview

YouTube Knowledge Assistant is an AI-powered Retrieval-Augmented Generation (RAG) system that transforms YouTube videos into searchable knowledge bases.

Users submit a YouTube URL, the system extracts transcripts, generates vector embeddings, stores them in Supabase, and enables natural language conversations about the video's content.

---

## Features

- YouTube transcript extraction
- Metadata enrichment
- Vector embedding generation
- Supabase Vector Database
- Semantic search
- Timestamp-aware retrieval
- Conversational AI interface
- Video-specific querying

---

## Architecture

YouTube URL

↓

Transcript Extraction

↓

Text Chunking

↓

Embedding Generation

↓

Supabase Vector Database

↓

Retriever

↓

LLM

↓

Chat Interface

---

## Tech Stack

- n8n
- Supabase
- OpenAI Embeddings
- OpenRouter
- Cohere Reranker
- Apify
- Google Sheets

---

## Workflow Capabilities

### Video Processing

- Accepts YouTube URLs
- Extracts transcripts automatically
- Generates embeddings
- Stores searchable knowledge

### Metadata Enrichment

Stores:

- Video title
- URL
- Timestamps
- Transcript chunks

### AI Question Answering

Users can:

- Ask questions about videos
- Generate summaries
- Extract insights
- Find timestamp-specific information

### Transcript Management

- Add videos
- Remove videos
- Re-index content
- Maintain searchable video library

---

## Learning Outcomes

- Retrieval-Augmented Generation
- Vector Search
- Semantic Retrieval
- Embeddings
- AI Agents
- Knowledge Management Systems

---

## Future Improvements

- Multi-video reasoning
- Cross-video comparisons
- Video recommendation engine
- Multi-language support
- Advanced citation system

---

## Author

Manthan Lathiya

GitHub: https://github.com/Manthan-Lathiya
LinkedIn: https://www.linkedin.com/in/manthan-lathiya/
