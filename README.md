# AI Research Agent

AI research agent built with LangChain and OpenAI that uses tools (search and Wikipedia)
to answer queries and return structured JSON output.

## Setup

```bash

python -m venv venv

venv\Scripts\Activate.ps1 (windows)

pip install -r requirements.txt

OPENAI_API_KEY=your_api_key_here
RUN:
python main.py


OUTPUT FORMAT:
{
  "topic": "string",
  "summary": "string",
  "sources": ["string"],
  "tools_used": ["string"]
}

