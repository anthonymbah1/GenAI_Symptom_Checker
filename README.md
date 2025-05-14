# 🧠 GenAI-Powered Symptom Checker & RAG System

A smart healthcare assistant that combines urgency classification using traditional machine learning with a Retrieval-Augmented Generation (RAG) system powered by LangChain + OpenAI.

---

## 🚀 Project Overview

This project includes:

- **Random Forest classifier** trained on symptom descriptions
- **TF-IDF vectorization + SMOTE** for class balance and feature prep
- **OpenAI + FAISS + LangChain** to enable natural Q&A based on hospital database
- **Streamlit interface** to simulate chatbot-style interactions

---

## 🧱 Folder Structure

```
gen_ai_project/
├── app/
│   └── b3.py                      # Symptom classifier + RAG logic
├── notebooks/
│   ├── Icarebot_GenAi.ipynb       # Integrated app logic & QA testing
│   ├── GenAI_RAG_Implementation.ipynb
│   └── GenAI_Model_Creation.ipynb
├── models/                        # (excluded from repo)
├── data/                          # (excluded from repo)
├── .env.example                   # Sample keys file
├── .gitignore
├── Deploy/
│   └── requirements.txt
└── README.md
```
## 🧠 Tech Stack
- 🧠 openai for LLM

- 📚 langchain, faiss-cpu for retrieval

- 🧮 pandas, sqlite3

- 🧪 tiktoken for token counting

- 🌍 Streamlit (optional frontend)

## 🔐 Environment Variables
Your .env file should include:
```
OPENAI_API_KEY=your_openai_key_here
PINECONE_API_KEY=your_pinecone_key_here
DB_PATH=data/teambeebsss.db
```
## 🛠️ How to Run
```
# Clone the repo
git clone https://github.com/anthonymbah1/GenAI_Symptom_Checker.git
cd GenAI_Symptom_Checker

# Create .env from template
cp .env.example .env

# Install dependencies
pip install -r Deploy/requirements.txt

# Run the app (or open in Colab)
python app/b3.py

```
## 👨🏽‍💻 Author
**Tony Mbah**
🔗 [LinkedIn Profile](https://www.linkedin.com/in/tony-mbah)
