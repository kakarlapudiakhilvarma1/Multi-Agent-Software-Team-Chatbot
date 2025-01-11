🛠️ AI Workflow StateGraph with GROQ API Integration 🚀
This repository demonstrates an AI-powered workflow using the langgraph library and GROQ's ChatGroq API. The project automates a software development pipeline, simulating various roles to streamline the process of building and deploying software systems.

🌟 Features
✨ State Graph Architecture
Use a graph-based workflow to manage sequential tasks with modular and reusable state management.

🧠 Role-Specific AI Models
Simulate roles like Analyst, Architect, Developer, Reviewer, Tester, Diagram Designer, and Summary Writer, each with custom prompts.

🔗 GROQ API Integration
Harness the power of GROQ LLMs with ChatGroq to generate precise, role-based outputs.

🖼️ Mermaid Diagram Support
Visualize your workflow as a Mermaid diagram with exportable .png images.

🖥️ Interactive Command-Line Interface
Engage with the workflow in real-time, simulating a conversation with multiple roles.

🗺️ Workflow Overview
This project automates the following roles:

1️⃣ Analyst: Gathers requirements and translates them into clear development instructions.
2️⃣ Architect: Designs scalable system architectures based on requirements.
3️⃣ Developer: Implements functionality by writing production-ready code.
4️⃣ Reviewer: Reviews the code for quality and suggests improvements.
5️⃣ Tester: Creates test automation scripts to ensure high-quality deliverables.
6️⃣ Diagram Designer: Visualizes the workflow and code using Mermaid diagrams.
7️⃣ Summary Writer: Prepares concise, human-readable documentation.

The workflow is structured using StateGraph, where each node corresponds to a specific role in the pipeline.

🏗️ Project Structure
plaintext
Copy code
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

⚙️ Installation
Clone the repository:

bash
Copy code
git clone https://github.com/kakarlapudiakhilvarma1/Multi-Agent-Software-Team-Chatbot.git
