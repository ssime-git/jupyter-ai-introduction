# Jupyter AI Introduction

![Jupyter AI Logo](./assets/image.png)

A curated environment for exploring Jupyter AI capabilities with pre-configured model providers.

## Features

- Pre-built Docker environment with Jupyter Lab
- Integrated support for Ollama and Google Gemini
- Example notebooks for AI workflow demonstrations

## Prerequisites

- [Docker Desktop](https://www.docker.com) (Linux: Docker Engine + Compose Plugin)
- [Git](https://git-scm.com/downloads)

## Quick Start

```bash
git clone https://github.com/jupyter-ai/jupyter-ai-introduction.git
cd jupyter-ai-introduction

# Start services (Jupyter Lab + Ollama)
docker compose up -d
```

## Configuration

1. Copy environment template:
   ```bash
   cp env_template .env
   ```
2. Add your [Google Gemini API Key](https://aistudio.google.com/app/apikey)

## Usage Guide

Access Jupyter Lab at `http://localhost:8888` and start using Jupyter AI in a jupyter notebook.

## Model Providers

Supported providers with installation requirements:

| Provider | Required Packages |
|----------|-------------------|
| Ollama | langchain-ollama |
| Gemini | langchain-google-genai numpy<2.0 |

[Full documentation →](https://jupyter-ai.readthedocs.io)