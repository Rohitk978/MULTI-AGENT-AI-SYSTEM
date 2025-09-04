MultiAI Agent System
Overview
The MultiAI Agent System is a collaborative multi-agent framework built using LangChain, LangGraph, and Groq LLMs. It simulates a team of AI agents—Supervisor, Researcher, Analyst, and Writer—working together to tackle complex tasks such as information gathering, analysis, and professional report generation. This project showcases advanced AI agent orchestration, multi-step reasoning, and workflow automation powered by Groq's LLaMA-3.1 model.

Key Features

✅ Multi-Agent Collaboration: Agents work as a team to produce high-quality outputs.
🔍 Automated Research: Collects data and insights using Groq-powered LLMs.
📊 Smart Analysis: Extracts actionable insights, risks, and recommendations.
✍️ Report Generation: Produces polished, executive-style reports.
⚡ Groq Integration: Leverages LLaMA-3.1 for fast and efficient reasoning.
🔄 Stateful Workflow: Memory-based agent routing for seamless task coordination.


Project Structure
MultiAI-Agent/
├── MultiAI Agent.py         # Main multi-agent system implementation
├── requirements.txt         # Python dependencies
├── README.md               # Project documentation
├── .env.example            # Example environment file for API keys
└── .gitignore              # Ignored files


Installation
Prerequisites

Python 3.8+
Git
A valid Groq API key (sign up at x.ai)

Setup

Clone the Repository:
git clone https://github.com/your-username/MultiAI-Agent.git
cd MultiAI-Agent


Create a Virtual Environment:
python -m venv myenv
myenv\Scripts\activate  # On Windows
source myenv/bin/activate  # On macOS/Linux


Install Dependencies:
pip install -r requirements.txt


Configure Environment Variables:Create a .env file in the root directory and add your Groq API key:
GROQ_API_KEY=your_groq_api_key_here




Dependencies
The project relies on the following Python libraries (listed in requirements.txt):

langchain
langgraph
langchain-groq
python-dotenv

Install them using:
pip install langchain langgraph langchain-groq python-dotenv


Usage
Run the application:
python "MultiAI Agent.py"

Example Output
📋 Supervisor: Let's start with research. Assigning to Researcher...
🔍 Researcher: I've completed the research on 'AI in Healthcare'...
📊 Analyst: Analysis complete. Extracted risks and opportunities...
✍️ Writer: Report complete! See below for the full document.

📄 FINAL REPORT
==================================================
Generated: 2025-08-31 10:15
Topic: Benefits and Risks of AI in Healthcare
==================================================
[Executive Summary...]
...
Report compiled by Multi-Agent AI System powered by Groq


Methodology
Workflow

Supervisor Agent: Initiates and coordinates tasks, delegating to the appropriate agent.
Researcher Agent: Gathers comprehensive details, including facts, statistics, and case studies.
Analyst Agent: Reviews findings and extracts actionable insights, risks, and recommendations.
Writer Agent: Compiles a structured, professional report.
Router Function: Manages agent switching until the task is complete.

Agents in Action

Researcher: Collects key facts, statistics, and case studies.
Analyst: Identifies risks, opportunities, and recommendations.
Writer: Generates a polished, professional report.


Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a feature branch:git checkout -b feature/your-feature


Commit your changes:git commit -m "Add your feature"


Push to the branch:git push origin feature/your-feature


Open a Pull Request.


License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

LangChain Team: For providing robust agent orchestration tools.
LangGraph: For enabling state-driven workflows.
Groq: For high-speed inference with LLaMA models.


Contact
For questions or support, please open an issue on the GitHub repository.
