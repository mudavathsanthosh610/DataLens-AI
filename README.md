
# 🔍 DataLens AI — Intelligent Data & Document Analysis

> **Upload. Ask. Analyze. Discover.**
>
> DataLens AI is an AI-powered data and document analysis platform that transforms raw files into meaningful insights, visualizations, summaries, and natural-language answers.

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-red?logo=streamlit)](https://streamlit.io/)
[![DuckDB](https://img.shields.io/badge/DuckDB-SQL%20Analytics-yellow?logo=duckdb)](https://duckdb.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)](https://pandas.pydata.org/)
[![Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?logo=google)](https://ai.google.dev/)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o-412991?logo=openai)](https://openai.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🚀 Live Demo

🌐 **Try DataLens AI live:**

👉 https://datalens-ai-8dkv2sbtjpknf9celtlr7h.streamlit.app/

> Upload your own dataset or document and interact with it using natural language.

---

## 📌 Overview

Working with raw data and documents often requires switching between spreadsheets, SQL tools, visualization software, and document readers.

**DataLens AI brings these capabilities together into a single AI-powered workspace.**

With DataLens AI, users can:

- 📊 Analyze CSV and Excel datasets
- 📈 Automatically generate visual insights
- 🔎 Discover trends and patterns
- 🧮 Ask SQL-powered questions about structured data
- 📄 Summarize PDF and PowerPoint documents
- 💬 Chat with uploaded files using natural language
- 🤖 Choose between multiple AI providers
- ⚡ Get insights without manually writing complex queries

The goal is simple:

> **Turn files into answers and insights with AI.**

---

# ✨ Key Features

## 📊 1. Intelligent Data Analysis

Upload structured datasets such as:

- CSV
- Excel / XLSX

DataLens AI analyzes the dataset and helps identify:

- Important columns
- Data distributions
- Trends
- Category comparisons
- Numerical relationships
- Potential patterns
- Summary statistics

---

## 📈 2. Automatic Visual Insights

DataLens AI can generate useful visualizations from uploaded datasets.

Examples include:

- 📉 Trend lines
- 📊 Category comparisons
- 📦 Distribution analysis
- 📈 Numerical trends
- 🔢 Summary statistics

Instead of manually creating every chart, users can explore their data through AI-assisted analysis.

---

## 🧮 3. SQL-Powered Data Questions

For structured datasets, DataLens AI uses **DuckDB** to perform fast in-process analytical queries.

You can ask questions such as:

```text
What are the top 10 products by revenue?
Which category has the highest average sales?
Show me the monthly sales trend.
What is the total revenue generated?

The application converts natural-language questions into analytical operations and returns meaningful results.

📄 4. Document Intelligence

DataLens AI also supports document-based analysis.

Supported formats:

PDF
PowerPoint / PPT

Users can upload documents and use AI to:

Generate summaries
Extract important information
Understand document content
Ask questions
Interact with the uploaded document
💬 5. Interactive AI Chat

Instead of searching through a large file manually, simply ask a question.

For example:

What are the main findings in this document?
Summarize this presentation.
What are the most important trends in this dataset?
Which category performed the best?

DataLens AI provides a conversational interface for exploring your files.

🤖 6. Multi-Provider AI

DataLens AI supports multiple AI providers.

Google Gemini

Use Google's Gemini models for AI-powered analysis and document interaction.

OpenAI

Use OpenAI models for intelligent natural-language analysis.

This gives users flexibility to choose their preferred AI provider.

🧠 How DataLens AI Works
              ┌─────────────────────┐
              │      User Upload    │
              └──────────┬──────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │   File Detection    │
              └──────────┬──────────┘
                         │
             ┌───────────┴───────────┐
             │                       │
             ▼                       ▼
      ┌──────────────┐       ┌────────────────┐
      │ CSV / Excel  │       │ PDF / PPT      │
      └──────┬───────┘       └───────┬────────┘
             │                       │
             ▼                       ▼
      ┌──────────────┐       ┌────────────────┐
      │ Pandas +     │       │ Document       │
      │ DuckDB       │       │ Processing     │
      └──────┬───────┘       └───────┬────────┘
             │                       │
             └───────────┬───────────┘
                         ▼
                ┌──────────────────┐
                │   AI Processing  │
                │ Gemini / OpenAI  │
                └────────┬─────────┘
                         │
             ┌───────────┴───────────┐
             │                       │
             ▼                       ▼
      ┌──────────────┐       ┌────────────────┐
      │ Visual       │       │ AI Answers &   │
      │ Insights      │       │ Summaries      │
      └──────────────┘       └────────────────┘
🛠️ Tech Stack
Technology	Purpose
🐍 Python	Core application logic
🎈 Streamlit	Interactive web application
🤖 Agno	AI agent framework
🦆 DuckDB	SQL-based analytical processing
🐼 Pandas	Data manipulation and analysis
📊 Data Visualization Libraries	Charts and visual insights
✨ Google Gemini	AI analysis
🧠 OpenAI	AI analysis
📄 PDF/PPT Processing	Document intelligence
📂 Supported File Types
File Type	Supported	Main Capability
.csv	✅	Data analysis + charts + Q&A
.xlsx	✅	Data analysis + charts + Q&A
.pdf	✅	Summarization + interactive Q&A
.pptx	✅	Summarization + interactive Q&A
⚙️ Getting Started
1. Clone the Repository
git clone https://github.com/mudavathsanthosh610/DataLens-AI.git

Navigate into the project:

cd DataLens-AI
2. Create a Virtual Environment
Windows
python -m venv venv
venv\Scripts\activate
macOS / Linux
python3 -m venv venv
source venv/bin/activate
3. Install Dependencies
pip install -r requirements.txt
🔑 API Key Configuration

DataLens AI requires an API key from one of the supported AI providers.

Option 1 — Environment Variables

Create a .env file in the project root:

GOOGLE_API_KEY=your_google_api_key
OPENAI_API_KEY=your_openai_api_key

Replace the values with your actual API keys.

Option 2 — Enter API Key in the Application

You can also provide your API key directly through the application's sidebar.

⚠️ Never commit API keys or .env files to GitHub.

Add the following to .gitignore:

.env
*.env
__pycache__/
venv/
.venv/
▶️ Running the Application Locally

Start the Streamlit application:

streamlit run "DataLENS AI.py"

The application will open in your browser.

If it doesn't open automatically, Streamlit will provide a local URL such as:

http://localhost:8501
🧪 Example Workflow
Step 1 — Upload

Upload a:

CSV
Excel
PDF
PowerPoint
Step 2 — Select AI Provider

Choose your preferred AI provider:

Google Gemini
        OR
OpenAI
Step 3 — Analyze

For datasets, explore:

Statistics
Trends
Categories
Visualizations
SQL-powered analysis

For documents, explore:

Summaries
Key information
AI-generated answers
Step 4 — Ask Questions

Interact with your uploaded file using natural language.

Example:

What are the key trends in this dataset?
Which product generated the highest revenue?
Summarize the important points from this presentation.
💡 Example Use Cases

DataLens AI can be useful for:

📊 Business Analytics

Analyze sales, revenue, customer, and product datasets.

🎓 Students & Researchers

Quickly explore datasets and summarize research documents.

💼 Business Teams

Extract insights from spreadsheets and presentations.

📑 Document Analysis

Ask questions about large PDF and PowerPoint files.

📈 Data Exploration

Quickly identify trends and patterns without manually writing SQL queries.

🤖 AI-Assisted Analytics

Combine traditional data analysis with modern LLM capabilities.

🏗️ Project Structure
DataLens-AI/
│
├── DataLENS AI.py
├── requirements.txt
├── README.md
├── .gitignore
├── LICENSE
│
└── assets/
    └── screenshots/

The exact structure may vary depending on the latest version of the project.

🔐 Security & Privacy

DataLens AI may process uploaded files through local analysis tools and/or AI providers depending on the selected functionality.

Important
Never upload confidential information unless you understand how the selected AI provider processes your data.
Never expose API keys in source code.
Never commit .env files.
Use environment variables or secure deployment secrets for production.
☁️ Deployment

DataLens AI is deployed using:

Streamlit Community Cloud

Live application:

👉 https://datalens-ai-8dkv2sbtjpknf9celtlr7h.streamlit.app/

For deployment, configure your required API keys through the platform's secrets/environment configuration rather than committing them to the repository.

🚀 Future Improvements

Planned improvements may include:

 More file formats
 Advanced data cleaning
 More visualization types
 Automated dashboard generation
 Advanced RAG-based document querying
 Conversation history
 Export analysis reports
 Downloadable charts and insights
 More AI model providers
 Improved multi-file analysis
 Authentication and user accounts
 Advanced agentic data analysis
📸 Screenshots

Add screenshots of the application here to make the repository more visually attractive.

Example:

## 📸 Screenshots

### 🏠 Dashboard

![DataLens AI Dashboard](assets/screenshots/dashboard.png)

### 📊 Data Analysis

![Data Analysis](assets/screenshots/data-analysis.png)

### 💬 AI Chat

![AI Chat](assets/screenshots/ai-chat.png)

### 📄 Document Intelligence

![Document Analysis](assets/screenshots/document-analysis.png)
🎯 Why DataLens AI?

Traditional data analysis often requires users to know:

Python
Pandas
SQL
Visualization tools
Document processing tools

DataLens AI aims to reduce that complexity by providing a conversational AI interface.

Instead of asking:

"How do I write this SQL query?"

Users can ask:

"Which category generated the highest revenue?"

And let the application handle the analytical workflow.

🌟 Project Highlights
🤖 AI-powered data analysis
📊 Automated visual insights
🧮 DuckDB SQL analytics
📄 PDF & PowerPoint intelligence
💬 Natural-language interaction
🔀 Multiple AI providers
⚡ Streamlit-powered interface
☁️ Cloud deployed
🔐 Environment-based API configuration
👨‍💻 Author
Mudavath Santhosh

AI & ML Developer | NLP | Deep Learning | LLMs

I build AI-powered applications focused on automation, intelligent data processing, and real-world problem solving.

🔗 Connect With Me
💻 GitHub: https://github.com/mudavathsanthosh610
💼 LinkedIn: https://www.linkedin.com/in/mudavath-santhosh-3005422a3
🌐 Portfolio: https://santhosh2006portfolio.netlify.app/
⭐ Support

If you find DataLens AI useful:

⭐ Star this repository
🍴 Fork the project
🐛 Report issues
💡 Suggest improvements

Your feedback helps improve the project!

📜 License

This project is licensed under the MIT License.

See the LICENSE file for more information.

<p align="center">
🔍 DataLens AI

Turn your files into insights with AI.

⭐ Star the repository if you like the project!

</p> ```
One important improvement I recommend

Since your GitHub profile currently shows DataLens-AI as a pinned repository, this README will make the project look substantially more polished when recruiters open it. Your profile currently lists DataLens-AI alongside projects such as your Resume Scoring Agent and AppOrbit.

Also, don't leave the README only text-based. The biggest improvement would be adding 4–6 actual screenshots of your running DataLens AI application under the Screenshots section. That will make the repository immediately understandable to a recruiter.
