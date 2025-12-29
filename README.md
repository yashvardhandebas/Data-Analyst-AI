# 🤖 Local AI Data Analyst (Ollama + Streamlit)

A powerful, private, and local AI agent that allows you to analyze Excel and CSV data using natural language. Instead of manually creating charts, just ask a question, and the AI will write and execute the Python code for you.



## ✨ Features
- **100% Data Privacy:** Your data stays on your machine. No cloud APIs required.
- **Natural Language to Code:** Powered by **Llama 3.2** to translate English queries into Pandas/Matplotlib code.
- **Interactive Dashboard:** Built with **Streamlit** for a clean, user-friendly experience.
- **Instant Visualization:** Automatically renders bar charts, pie charts, and statistical tables.

## 🛠️ Tech Stack
- **Engine:** [Ollama](https://ollama.com/) (Llama 3.2:latest)
- **Frontend:** [Streamlit](https://streamlit.io/)
- **Data Handling:** [Pandas](https://pandas.pydata.org/)
- **Visualization:** [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/)

## 🚀 Installation & Setup

### 1. Install Ollama
Download and install Ollama from [ollama.com](https://ollama.com). Once installed, download the Llama 3.2 model:
```bash
ollama pull llama3.2
