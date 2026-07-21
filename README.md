# 🔬 ResearchMind – Multi-Agent AI Research System

ResearchMind is an AI-powered research assistant that automates the process of gathering, analyzing, and summarizing information using a **multi-agent pipeline**.

Instead of relying on a single LLM response, ResearchMind employs specialized AI agents that collaborate to search the web, extract detailed information, generate a structured research report, and review its quality.

---

## 🚀 Features

- 🤖 Multi-Agent Architecture
- 🔍 Intelligent Web Search
- 📄 Automatic Content Scraping
- ✍️ AI-Generated Research Reports
- 🧐 AI Critic for Report Review
- 📥 Download Research Report
- 🎨 Clean and Interactive User Interface

---

## 🏗️ Architecture

```
                User Query
                     │
                     ▼
              Search Agent
                     │
                     ▼
              Reader Agent
                     │
                     ▼
              Writer Chain
                     │
                     ▼
              Critic Chain
                     │
                     ▼
              Final Report
```

---

## ⚙️ Research Pipeline

### 1️⃣ Search Agent
- Searches the web for recent and reliable information.
- Collects relevant sources related to the research topic.

### 2️⃣ Reader Agent
- Selects the most relevant resource.
- Extracts and processes detailed content from the source.

### 3️⃣ Writer Chain
- Combines search results and extracted information.
- Generates a structured and comprehensive research report.

### 4️⃣ Critic Chain
- Reviews the generated report.
- Provides suggestions, feedback, and quality improvements.

---

## 🛠️ Tech Stack

### AI & LLM
- LangChain
- Mistral AI

### Search & Retrieval
- Tavily Search API

### Backend
- Python

### Interface
- Streamlit

---

## 📂 Project Structure

```
ResearchMind/
│
├── agents.py              # Search & Reader agents
├── chains.py              # Writer and Critic chains
├── app.py                 # Streamlit application
├── requirements.txt
├── .env
└── README.md
```

---

## 🔧 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/ResearchMind.git
```

Move into the project

```bash
cd ResearchMind
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create a `.env` file

```env
MISTRAL_API_KEY=your_key
TAVILY_API_KEY=your_key
```

Run the application

```bash
streamlit run app.py
```

---

## 📋 Example Workflow

```
User:
"Recent advancements in Quantum Computing"

        │

        ▼

Search Agent
        │

        ▼

Reader Agent
        │

        ▼

Writer Chain
        │

        ▼

Critic Chain
        │

        ▼

Comprehensive Research Report
```

---

## 🌟 Future Improvements

- Multi-source content synthesis
- PDF & DOCX report export
- Citation generation
- Research history
- Fact verification
- More specialized AI agents
- Support for multiple LLM providers

---

## 📜 License

This project is intended for learning and educational purposes.

---

## 👨‍💻 Author

**Dhiraj Patil**

Computer Engineering Student | AI & GenAI Enthusiast
