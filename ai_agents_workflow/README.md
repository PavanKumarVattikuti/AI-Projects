# 3-Level Hierarchical Agentic Workflow
This project demonstrates a multi-agent orchestration pattern using a 3-level hierarchy. By leveraging Gemma, the workflow breaks down complex tasks through specialized layers of reasoning and execution.

# 🏗️ Architecture
The system is organized into three distinct levels:

- Level 1: Orchestrator – Receives the high-level goal, decomposes it into sub-tasks, and delegates them.

- Level 2: Manager/Supervisor – Oversees specific domains or sub-tasks, ensuring quality and context alignment between the orchestrator and workers.

- Level 3: Worker Agents – Specialized agents that execute granular tasks (e.g., data retrieval, code generation, or analysis).

# 🚀 Getting Started

- *Notebook*: The core logic is contained in 3_level_hierarchical_agent.ipynb.

- *Model*: Powered by Gemma (Google's open-weights LLM).

- *Environment*: Designed to run in Kaggle Notebooks or local Jupyter environments with GPU support.

# 🛠️ Requirements
Python 3.10+

- LangGraph / CrewAI / AutoGen (depending on your specific implementation inside the notebook)

- Hugging Face / Kaggle API Key (for Gemma access)

# 📖 Usage

- Open the notebook in Kaggle.

- Configure your API keys in the Secrets tab.

- Run the cells to see the agents communicate across levels to solve complex prompts.
