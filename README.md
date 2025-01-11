# Multi-Agent-Software-Team-Chatbot 🚀

Here’s the improved and well-structured `README.md` for your project:

This repository demonstrates an **AI-powered workflow** using the `langgraph` library and **GROQ's ChatGroq API**. The project automates a software development pipeline by simulating various roles to streamline the process of building and deploying software systems.  

---

## 🌟 Features  

✨ **State Graph Architecture**  
Manage sequential tasks with a graph-based workflow using modular and reusable state management.  

🧠 **Role-Specific AI Models**  
Simulate roles like **Analyst**, **Architect**, **Developer**, **Reviewer**, **Tester**, **Diagram Designer**, and **Summary Writer**, each equipped with custom AI prompts.  

🔗 **GROQ API Integration**  
Leverage the power of GROQ LLMs via `ChatGroq` to generate precise, role-based outputs.  

🖼️ **Mermaid Diagram Support**  
Visualize your workflow as a **Mermaid diagram** and export it as a `.png` image.  

🖥️ **Interactive Command-Line Interface**  
Engage with the workflow in real-time, simulating conversations with various AI roles.  

---

## 🗺️ Workflow Overview  

This project automates the following roles:  

1️⃣ **Analyst**: Gathers requirements and translates them into clear development instructions.  
2️⃣ **Architect**: Designs scalable system architectures based on requirements.  
3️⃣ **Developer**: Implements functionality by writing production-ready code.  
4️⃣ **Reviewer**: Reviews the code for quality and suggests improvements.  
5️⃣ **Tester**: Creates test automation scripts to ensure high-quality deliverables.  
6️⃣ **Diagram Designer**: Visualizes the workflow and code using Mermaid diagrams.  
7️⃣ **Summary Writer**: Prepares concise, human-readable documentation.  

The workflow is structured using **StateGraph**, where each node corresponds to a specific role in the pipeline.  

---

## 🏗️ Project Structure  

```plaintext  
├── img/                # Directory containing images and visual assets  
│   └── graph.png       # Exported Mermaid diagram of the workflow  
├── .env                # Environment variables file (contains GROQ_API_KEY)  
├── .gitignore          # Git configuration for ignored files  
├── LICENSE             # Project license information  
├── README.md           # Project documentation  
├── app.py              # Main application script for workflow execution  
├── app_ui.py           # UI-related logic for the application  
├── graph.png           # Exported Mermaid diagram (alternative location)  
├── requirements.txt    # Python dependencies for the project  
```  

---

## ⚙️ Installation  

Follow these steps to set up and run the project:  

### 1️⃣ Clone the repository  
```bash  
git clone https://github.com/kakarlapudiakhilvarma1/Multi-Agent-Software-Team-Chatbot.git  
cd Multi-Agent-Software-Team-Chatbot  
```  

### 2️⃣ Set up a virtual environment (optional)  
```bash
Create virtual environment using conda
conda create -p env_name python==3.10 -y

Activate environment
conda activate env_name/
  
```  

### 3️⃣ Install dependencies  
```bash  
pip install -r requirements.txt  
```  

### 4️⃣ Configure the environment variables  
Create a `.env` file in the root directory and add your GROQ API key:  
```plaintext  
GROQ_API_KEY=your_groq_api_key_here  
```  

---

## 🖥️ How to Run  

1. Run the main application:  
   ```bash  
   python app.py  
   ```  

2. Enter your prompts into the CLI to simulate conversations with different AI roles.  

3. To exit, type:  
   ```plaintext  
   cntrl+c
   ```  

---

## 📊 Example Output  

```plaintext  
>> Design a scalable e-commerce system  
Analyst: Creates a detailed software requirement document.  
Architect: Designs a scalable cloud-based architecture.  
Developer: Writes production-ready code.  
Reviewer: Suggests improvements for better code quality.  
Tester: Generates automated test scripts for the system.  
Diagram Designer: Creates a Mermaid diagram of the workflow.  
Summary Writer: Summarizes all outputs into a concise document.  
```  

---

## 📜 Mermaid Diagram  

Below is a visual representation of the workflow:  

![Graph Workflow](img/graph.png)  

---

## 🤝 Contributions  

We welcome contributions to improve this project! To contribute:  

1. Fork the repository.  
2. Create a new branch.  
3. Submit a pull request with a description of your changes.  

---

## 🧰 Built With  

- 🧱 **Python**  
- 🤖 **LangGraph** for workflow automation.  
- 🌐 **ChatGroq** for LLM integration.  
- 📄 **Mermaid** for diagram generation.  

---

## 🔮 Future Enhancements  

- Add more role-specific prompts for enhanced customization.  
- Extend support to integrate additional LLM APIs.  
- Develop a web-based UI for better user interaction.  

---

## 📧 Contact  

Feel free to reach out for suggestions or questions:  
📌 **GitHub**: [kakarlapudiakhilvarma1](https://github.com/kakarlapudiakhilvarma1)  

---

Let me know if you’d like further modifications! 🚀
