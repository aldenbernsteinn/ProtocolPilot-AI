# ProtocolPilot
![ProtocolPilotmockup](https://github.com/user-attachments/assets/39283acd-9fba-44f9-bc1f-9bccef948891)

**ProtocolPilot** is a compact AI-driven application designed to automate compliance verification across various professional domains. Leveraging multi-source Retrieval Augmented Generation (RAG), the system performs intelligent comparisons between industry handbooks/standards and specific documents, all locally on your machine.

The application offers a user-friendly interface for uploading documents, creating indexes, and querying the system without being CPU or GPU intensive. It quickly provides role-specific insights, highlighting potential compliance issues and areas needing attention based on user-uploaded "handbooks" that include guidelines and protocol.

ProtocolPilot aims to significantly reduce the time and effort required for compliance checking, while improving accuracy and consistency across various professional standards.

## Key Features

1. **Role-based analysis** tailored for multiple professions (legal, financial, technical, etc.)
2. **Multi-RAG system**: separate indexes for handbooks, roles, and documents
3. **AI-powered contextual interpretation** of standards and documents
4. **Automated discrepancy detection** and compliance reporting

## Primary Technologies

- **Python**
- **PySide6 (Qt for Python)** for the GUI
- **Langchain** for RAG implementation
- **Ollama** for local language model integration
- **Chroma** for vector store and similarity search
