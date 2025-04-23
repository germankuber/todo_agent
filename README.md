# 📝 Todo Agent

A sophisticated AI-powered todo list manager that helps you keep track of your tasks with natural language processing capabilities.

## ✨ Features

- 🤖 Natural language task management
- 🧠 Intelligent task categorization
- ⏰ Deadline tracking
- ✅ Task status updates
- 👤 User profile management
- 💾 Persistent storage of tasks and preferences

## 🔧 Prerequisites

- 🐍 Python 3.12 or higher
- 📦 Poetry (Python package manager)

## 🚀 Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd todo-agent
```

2. Install dependencies using Poetry:
```bash
poetry install
```

3. Activate the virtual environment:
```bash
poetry shell
```

## ⚙️ Configuration

Before running the agent, you need to set up your environment variables. Create a `.env` file in the root directory with the following variables:

```env
OPENAI_API_KEY=your_openai_api_key
```

## 📖 Usage

1. Start the agent:
```bash
python todo_agent.py
```

2. Interact with the agent using natural language. Examples:
   - "Add a task to buy groceries tomorrow" 🛒
   - "What are my pending tasks?" 📋
   - "Mark the grocery shopping task as complete" ✅
   - "Update my profile with my location" 📍

## 📁 Project Structure

- `todo_agent.py`: Main application file
- `configuration.py`: Configuration settings
- `pyproject.toml`: Poetry dependency management
- `poetry.lock`: Locked dependencies versions

## 📚 Dependencies

The project uses the following main dependencies:
- 🔄 langgraph
- 🔗 langchain-core
- 🌐 langchain-community
- 🔒 trustcall
- 🤖 langchain-openai
- 📊 langsmith
- 🧠 langchain-anthropic

All dependencies are managed through Poetry and specified in `pyproject.toml`.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
