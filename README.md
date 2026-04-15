# RAG Document Q&A System

**Status:** In active development (April 2026)

A production-grade Retrieval-Augmented Generation application where users
upload PDFs and ask questions, receiving cited answers from document content.

## Tech Stack
- Frontend: Angular 20, Angular Material, RxJS
- Backend: .NET 8 Web API, Semantic Kernel
- AI: Azure OpenAI (GPT-4o-mini + text-embedding-3-small)
- Vector Search: Azure AI Search
- Storage: Azure Blob Storage (PDFs), SQL Server (metadata)
- Deployment: Azure App Service

## Planned Features
- [ ] PDF upload and chunking pipeline
- [ ] Vector embedding and indexing
- [ ] Hybrid semantic + keyword search
- [ ] Streaming chat responses with SSE
- [ ] Citation highlighting with PDF page references
- [ ] Cost tracking dashboard
- [ ] Evaluation harness for hallucination tracking

## Why
Most enterprise GenAI projects today are RAG. This is a deep-dive into
every layer — chunking, embeddings, retrieval quality, hallucination
handling, and production observability — on the .NET + Azure stack.

---
Part of my GenAI learning journey.
