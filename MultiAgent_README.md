
# Multi-Agent System using Google ADK

## 📌 Project Overview
This project implements a **Multi-Agent System** using **Google ADK (AI Development Kit)**.  
It demonstrates how multiple AI agents collaborate, share tasks, and execute different roles inside a coordinated workflow.

The notebook includes:
- Multiple AI agent initialization
- Role-based task execution
- Inter-agent communication
- Workflow coordination
- Chat message handling and streaming

---

## 🚀 Features
- Multiple agents working together
- Modular and scalable architecture
- Task routing and delegation between agents
- Utility functions for message streaming
- Easy to extend for real-world workflows

---

## 🛠️ Technologies Used
- Python  
- Google ADK  
- Generative AI Models  
- Jupyter Notebook  

---

## 📂 Project Structure
```
Multi-Agent.ipynb       # Main multi-agent implementation
README.md               # Documentation
```

---

## ⚙️ Setup Instructions

### 1. Install Dependencies
```bash
pip install google-generativeai google-adk kaggle-secrets
```

### 2. Configure the API Key

#### If running on Kaggle:
1. Go to *Settings → Secrets*
2. Add a secret named: `GOOGLE_API_KEY`

#### If running locally:
```bash
export GOOGLE_API_KEY="your_api_key_here"
```

---

## 💡 How It Works
1. Import Google ADK core and agent components.  
2. Create multiple agents with different roles (planner, researcher, writer, evaluator, etc.).  
3. Pass messages between agents using the agent pipeline.  
4. Agents collaborate and produce the final combined output.  

---

## 🧪 Example Usage
```python
response = planner_agent.run("Create an outline for AI governance framework")
print(response)
```

---

## 📈 Future Enhancements
- Chain-of-thought–based multi-agent reasoning  
- Agent memory support  
- Web and API deployment  
- Visualization of multi-agent workflows  

---

## 📜 License
This project follows the licensing terms included inside the notebook.

---

## 🤝 Contributing
Contributions, issues, and pull requests are welcome!
