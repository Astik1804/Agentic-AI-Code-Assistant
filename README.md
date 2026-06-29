# 🤖 AI Code Agent

An AI-powered coding assistant built using **LangGraph**, **LangChain**, and **OpenAI GPT models** that helps developers analyze, understand, and modify code through natural language instructions.

The agent leverages modern LLM workflows to perform intelligent coding tasks such as answering questions about code, generating implementations, debugging, refactoring, and explaining source files.

---

## ✨ Features

- 💬 Chat with your codebase using natural language
- 🧠 AI-powered code generation
- 🐞 Debug existing code
- ♻️ Refactor source code
- 📝 Explain complex code snippets
- 🔍 Analyze project structure
- ⚡ Built with LangGraph for agentic workflows
- 🔑 OpenAI API integration

---

## 🏗️ Project Structure

```text
code-agent/
│
├── app.py                 # Main application
├── agent.py               # AI agent logic
├── prompts.py             # System prompts
├── tools.py               # Agent tools
├── requirements.txt       # Python dependencies
├── .env.example           # Environment variables
└── README.md
```

> *The exact file structure may vary slightly depending on updates to the repository.*

---

## 🛠️ Tech Stack

- Python 3.11+
- LangChain
- LangGraph
- OpenAI API
- Streamlit (UI)
- dotenv

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/techwithprateek/ai-engineering-lab.git
```

### 2. Navigate to the project

```bash
cd ai-engineering-lab/code-agent
```

### 3. Create a virtual environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux/macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file inside the project directory.

```env
OPENAI_API_KEY=your_openai_api_key
```

Replace the value with your own OpenAI API key.

---

## ▶️ Running the Application

If the project uses Streamlit:

```bash
streamlit run app.py
```

If it is a Python script:

```bash
python app.py
```

---

## 💡 Example Prompts

- Explain this function.
- Refactor this code.
- Optimize the algorithm.
- Find bugs in this file.
- Generate unit tests.
- Convert this function into a class.
- Improve readability.
- Add documentation.
- Implement missing logic.

---

## 📂 Workflow

```text
User Prompt
      │
      ▼
 LangGraph Agent
      │
      ▼
 Tool Selection
      │
      ▼
 OpenAI GPT Model
      │
      ▼
Generated Response
```

---

## 📦 Requirements

Typical dependencies include:

- langchain
- langgraph
- openai
- python-dotenv
- streamlit

Install all packages using:

```bash
pip install -r requirements.txt
```

---

## 📸 Demo

Example interaction:

```
You:
Explain the merge_sort() function.

AI:
The merge_sort function recursively divides the array into halves,
sorts each half independently, and merges them back together,
resulting in O(n log n) time complexity.
```

---

## 🔮 Future Improvements

- Multi-file code editing
- GitHub integration
- Local LLM support
- Conversation memory
- RAG over repositories
- Docker support
- Unit test generation
- Code review mode

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add feature"
```

4. Push your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 📄 License

This project is intended for educational purposes as part of the **AI Engineering Lab** repository.

---

## 🙏 Acknowledgements

- LangChain
- LangGraph
- OpenAI
- AI Engineering Lab by Tech With Prateek

---

## ⭐ Support

If you found this project helpful, consider giving the repository a ⭐ on GitHub.
