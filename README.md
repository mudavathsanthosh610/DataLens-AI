# 🔍 DataLens AI

Upload any file — CSV, Excel, PDF, or PowerPoint — and let AI uncover insights, trends, and answers instantly.

## Features

- **📊 Data Analysis** — Upload CSV/Excel files for automated charts, trends, and SQL-powered Q&A
- **📄 Document Intelligence** — Upload PDF/PPT files for AI-powered summaries and interactive chat
- **🤖 Multi-Provider AI** — Choose between Google Gemini or OpenAI GPT-4o
- **📈 Visual Insights** — Auto-generated trend lines, category comparisons, distribution charts
- **💬 Interactive Chat** — Ask natural language questions about your data or documents

## Getting Started

### Prerequisites
- Python 3.9+
- A Google API key (Gemini) or OpenAI API key

### Installation

```bash
pip install -r requirements.txt
```

### Running Locally

```bash
streamlit run "DataLENS AI.py"
```

### Environment Variables (Optional)

Create a `.env` file:
```
GOOGLE_API_KEY=your_google_api_key
OPENAI_API_KEY=your_openai_api_key
```

Or enter your API key directly in the sidebar.

## Tech Stack

- **Streamlit** — Web UI framework
- **Agno** — AI agent framework
- **DuckDB** — In-process SQL analytics
- **Pandas** — Data manipulation
- **Google Gemini / OpenAI** — LLM providers

## Deployment

Deployed on [Streamlit Community Cloud](https://streamlit.io/cloud).

## License

MIT
