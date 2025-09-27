# Chatbot-With-External-Tools-Workflow-With-LangGraph-GenAI-Project
This Repository contains my working files of "Chatbot With External Tools Workflow With LangGraph Project", an GenAI Project

(i) Configured external tools (Wikipedia and Arxiv) and bound them to the LLM to handle queries the chatbot could not answer directly.

(ii) Defined a State class to track messages and created a StateGraph workflow connecting chatbot nodes with start and end nodes for structured execution.

(iii) Implemented a multi-agent chatbot function that dynamically decides whether to respond itself or delegate queries to the bound tools based on user input.

(iv) Compiled and visualized the graph, then tested the application with real-time streaming input, demonstrating the LLM’s interaction with external tools in a stateful workflow.
