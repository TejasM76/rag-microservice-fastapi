# RAG Microservice

A production-ready Retrieval-Augmented Generation (RAG) microservice built with FastAPI, featuring document ingestion, semantic search, and comprehensive observability.

## Features

- **Document Ingestion**: Supports PDF and Markdown files with intelligent chunking
- **Semantic Search**: Uses sentence-transformers for embedding and Chroma for vector storage
- **FastAPI**: RESTful API with automatic OpenAPI documentation
- **Observability**: Structured logging, Prometheus metrics, and request tracing
- **HITL Support**: Confidence scoring with human-in-the-loop escalation
- **Evaluation**: Built-in evaluation harness with multiple metrics
- **Docker**: Containerized deployment with docker-compose

## Quick Start

### Local Development

1. **Install dependencies**:
