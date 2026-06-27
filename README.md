# 🤖 AI-Powered Natural Language to SQL Chatbot using LangChain & LLMs

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-AI_Framework-00A67E?style=for-the-badge)
![Flask](https://img.shields.io/badge/Flask-Backend-black?style=for-the-badge&logo=flask)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite)
![OpenAI](https://img.shields.io/badge/OpenAI-LLM-412991?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-API-orange?style=for-the-badge)
![Google Gemini](https://img.shields.io/badge/Gemini-Google-blue?style=for-the-badge)

</p>


<p align="center">
  <img src="images/overview-banner.png" alt="SQL Chatbot Overview" width="100%">
</p>
---

# 📌 Overview

The **AI-Powered SQL Chatbot** is a Natural Language to SQL (NL2SQL) application that enables users to query relational databases using plain English instead of manually writing SQL statements.

The application leverages **Large Language Models (LLMs)** through **LangChain** to understand user intent, generate optimized SQL queries, execute them against a **SQLite** database, and return both the generated SQL query and a human-readable answer.

This project was developed during my **AI/ML Internship at Dynamisity Pvt. Ltd.** as part of exploring conversational AI, prompt engineering, database reasoning, and LangChain-based applications.

---

# 🚀 Key Features

✅ Ask database questions in natural language

✅ Automatic SQL query generation using LLMs

✅ Execute generated SQL queries

✅ Human-readable AI-generated answers

✅ Supports multiple LLM providers

- OpenAI
- Google Gemini
- Groq

✅ REST API using Flask

✅ Interactive Web Interface

✅ Modular LangChain pipeline

---

# 🏗 System Architecture

> *(Replace the image path after uploading your architecture screenshot.)*

```text
User Question
      │
      ▼
Web Interface
(HTML/CSS/JS)
      │
      ▼
Flask Backend API
      │
      ▼
LangChain SQL Chain
      │
      ▼
Large Language Model
(OpenAI / Gemini / Groq)
      │
      ▼
Generated SQL Query
      │
      ▼
SQLite Database
      │
      ▼
Query Results
      │
      ▼
LLM Response Formatter
      │
      ▼
Final Answer
```

Or

```markdown
![Architecture](images/architecture.png)
```

---

# ⚙️ Project Workflow

```
User enters a question
          │
          ▼
LLM understands intent
          │
          ▼
LangChain generates SQL
          │
          ▼
SQL executed on SQLite
          │
          ▼
Database returns records
          │
          ▼
LLM converts records into
easy-to-understand response
          │
          ▼
User receives final answer
```

---

# 💻 Technology Stack

## Programming Language

- Python

---

## AI & LLM

- OpenAI API
- Google Gemini API
- Groq API

---

## Frameworks

- LangChain
- Flask

---

## Database

- SQLite

---

## Frontend

- HTML5
- CSS3
- JavaScript

---

## Development Environment

- Visual Studio Code

---

## Concepts Used

- Prompt Engineering
- Natural Language Processing (NLP)
- Natural Language to SQL (NL2SQL)
- Retrieval of Database Metadata
- SQL Query Generation
- REST APIs

---

# 📂 Project Structure

```text
SQL-Chatbot-LangChain
│
├── README.md
│
├── images
│   ├── architecture.png
│   ├── signup-page.png
│   ├── otp-verification.png
│   ├── chatbot-interface.png
│   ├── testcase-1.png
│   ├── testcase-2.png
│   └── testcase-3.png
│
├── docs
│
└── LICENSE
```

---

# ✨ Application Features

### 🔹 User Authentication

- Sign Up
- Login
- OTP Verification

---

### 🔹 AI SQL Assistant

- Converts English into SQL
- Generates optimized SQL queries
- Executes SQL
- Shows SQL query
- Displays database result
- Explains results in natural language

---

### 🔹 Multi-Model Testing

The project was tested using multiple LLM providers:

- OpenAI
- Google Gemini
- Groq

to compare SQL generation quality and response accuracy.

---

# 📸 Screenshots

## SQL Chatbot Architecture

```markdown
![Architecture](images/architecture.png)
```

---

## User Registration

```markdown
![Signup](images/signup-page.png)
```

---

## OTP Verification

```markdown
![OTP](images/otp-verification.png)
```

---

## Chat Interface

```markdown
![Chatbot](images/chatbot-interface.png)
```

---

## SQL Generation Example

```markdown
![Test Case](images/testcase-1.png)
```

---

# 🧪 Sample Query

### User Question

```
How many employees are there?
```

Generated SQL

```sql
SELECT COUNT(*) FROM Employee;
```

Output

```
8
```

AI Response

```
There are 8 employees in the database.
```

---

# 🎯 Skills Demonstrated

- Large Language Models (LLMs)
- LangChain
- Prompt Engineering
- SQL Query Generation
- Natural Language Processing
- Flask API Development
- REST APIs
- SQLite
- AI Application Development

---

# 🚧 Challenges Faced

- Converting ambiguous user questions into valid SQL
- Preventing invalid SQL generation
- Prompt tuning for improved query accuracy
- Supporting multiple LLM providers
- Formatting SQL responses for better readability
- Handling database execution errors gracefully

---

# 📈 Learning Outcomes

Through this project I gained practical experience in:

- Building AI-powered applications
- LangChain pipelines
- Prompt Engineering
- LLM Integration
- Natural Language to SQL systems
- Flask backend development
- SQL database interaction
- REST API development

---

# 🔮 Future Improvements

- Azure OpenAI Integration
- PostgreSQL & MySQL Support
- Role-based Authentication
- Query History
- Database Schema Visualization
- Voice-based Queries
- Retrieval-Augmented Generation (RAG)
- Docker Deployment
- Azure App Service Deployment

---

# ⚠️ Disclaimer

This repository showcases the architecture, implementation approach, workflow, and documentation of a project developed during my AI/ML internship.

The original source code belongs to the organization and is **not publicly available**. This repository is intended solely for portfolio and learning purposes.

---

# 👩‍💻 Author

**Priyanka Sonawane**

AI/ML Developer | Dynamics 365 CRM Consultant | Generative AI Enthusiast

📧 LinkedIn: *(Add your LinkedIn URL)*

🌐 GitHub: https://github.com/PriyankaSonawane2030

---
