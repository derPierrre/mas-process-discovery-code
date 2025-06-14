# Process Discovery with LLM-based Multi-Agent Systems

This repository contains the implementation code for the Master Thesis.

## Quick Start

The project is designed to work seamlessly with **Visual Studio Code Dev Containers**, providing a complete development environment with MLflow integration out of the box.

### Prerequisites
- Visual Studio Code
- Docker Desktop
- Dev Containers extension for VS Code

### Setup
1. Clone this repository
2. Open in Visual Studio Code
3. When prompted, click "Reopen in Container"
4. The container will automatically set up the complete environment including MLflow

## API Configuration

The project supports multiple LLM providers. Configure the required API keys as environment variables before starting the container:

### Supported Providers

| Provider | Environment Variable | Notes |
|----------|---------------------|--------|
| **DeepSeek** | `DEEPSEEK_API_KEY` | |
| **Mistral** | `MISTRAL_API_KEY` | ✅ Free tier available |
| **Gemini** | `GEMINI_API_KEY` | ✅ Free tier available |
| **Google Vertex AI** | `GOOGLE_APPLICATION_CREDENTIALS` | Path to service account JSON file |
