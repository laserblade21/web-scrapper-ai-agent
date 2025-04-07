# 💻 Web Scraping AI Agent

This Streamlit app leverages the power of OpenAI's language models and the `scrapegraphai` library to intelligently extract data from any website. Just provide your OpenAI API key, specify the URL, and describe what you want to extract — the AI agent handles the rest.

---

## 🚀 Features

- 🔍 Scrape any website by simply providing the URL  
- 🤖 Powered by OpenAI’s GPT-3.5-turbo or GPT-4  
- ✍️ Customize what the AI should extract using natural language prompts  
- 🧠 Uses `scrapegraphai`'s SmartScraperGraph for intelligent data extraction  
- 🖥️ Interactive and easy-to-use Streamlit interface

---

## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone <your-repo-url>
cd <your-repo-directory>
pip install -r requirements.txt
🧠 How It Works
The app prompts you to enter your OpenAI API key for authentication.

Choose your preferred language model (GPT-3.5-turbo or GPT-4).

Input the URL of the website you want to scrape.

Describe (in plain English) what data you want to extract.

A SmartScraperGraph object is created using the URL, your prompt, and the selected LLM.

The AI agent intelligently extracts the specified content.

Results are displayed right in the app for easy viewing and copying.
