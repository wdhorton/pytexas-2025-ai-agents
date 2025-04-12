# PyTexas 2025 - Demystifying AI Agents with Python Code

This repository contains materials for my PyTexas 2025 presentation on AI agents.

## Prerequisites

- Python 3.12+ installed

## Getting Started

Follow these steps to set up and run the notebook after cloning this repository:

### 1. Clone the Repository

If you haven't already cloned this repository, do so with:

```bash
git clone https://github.com/wdhorton/pytexas-2025-ai-agents.git
cd pytexas-2025-ai-agents
```

### 2. Set Up a Virtual Environment (Recommended)

Create and activate a virtual environment to isolate dependencies:

```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On macOS/Linux:
source venv/bin/activate
# On Windows:
# venv\Scripts\activate
```

### 3. Install Dependencies

Install the required packages listed in the requirements.txt file:

```bash
pip install -r requirements.txt
```

This will install:
- openai - OpenAI API client
- requests - HTTP library for API calls
- crewai - Framework for building AI agent systems
- html2text - HTML to markdown conversion (used in some examples)

### 4. Set Up API Keys

The notebook examples require API keys for OpenAI and Serper (for web search). Here's how to obtain and set them:

#### OpenAI API Key

1. Go to [OpenAI's website](https://platform.openai.com/signup) and create an account if you don't have one
2. Navigate to the [API keys section](https://platform.openai.com/api-keys) in your account dashboard
3. Click "Create new secret key" and give it a name
4. Copy your newly created API key (you won't be able to see it again)

#### Serper API Key (for web search examples)

1. Go to [Serper.dev](https://serper.dev) and create an account
2. After signing up, you'll be able to access your API key from your dashboard
3. Copy your API key for use in the notebook

#### Setting Environment Variables

Set these as environment variables:

```bash
# On macOS/Linux:
export OPENAI_API_KEY="your-openai-api-key"
export SERPER_API_KEY="your-serper-api-key"

# On Windows:
# set OPENAI_API_KEY=your-openai-api-key
# set SERPER_API_KEY=your-serper-api-key
```

### 5. Launch the Notebook

Start Jupyter to open and run the notebook:

```bash
jupyter notebook
```

This will open Jupyter in your browser. Navigate to and open "Demystifying AI Agents with Python Code.ipynb".

## Troubleshooting

- If you encounter module import errors, verify that all dependencies are installed
- Check your API keys if you receive authentication errors
- Ensure you're running the notebook within the virtual environment where dependencies are installed