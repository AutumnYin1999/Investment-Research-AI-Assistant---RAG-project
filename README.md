# Investment Research AI Assistant — RAG Project

An AI assistant for investment research, built on a Retrieval-Augmented Generation (RAG) pipeline.

## Overview

This project ingests financial documents (research reports, filings, news) and answers
investment-research questions by retrieving relevant context and generating grounded responses.

## Status

🚧 Early setup — project scaffolding in progress.

## Getting Started

```bash
# Create and activate a virtual environment
python -m venv .venv
.venv\Scripts\activate        # Windows
# source .venv/bin/activate   # macOS/Linux

# Install dependencies (once requirements.txt exists)
pip install -r requirements.txt
```

## Configuration

Copy `.env.example` to `.env` and fill in your API keys. **Never commit `.env`.**
