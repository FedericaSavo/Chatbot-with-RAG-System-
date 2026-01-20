# Chatbot-with-RAG-System-

<img width="868" height="352" alt="Screenshot 2026-01-20 alle 16 41 25" src="https://github.com/user-attachments/assets/cedcb70f-46fd-4626-b0e2-8d60a3645cf0" />

## Overview
This project automates a chatbot that answers user questions from a knowledge source using a **RAG system for precise retrieval**. Responses are stored in Airtable and unresolved questions trigger Zendesk tickets for follow-up.

---

## Features
- Answer questions from a knowledge source  
- Retrieve relevant info using a RAG system  
- Store responses in Airtable  
- Open Zendesk tickets for unanswered queries  

---

## Technologies Used
- **n8n**  
- **AI / RAG system**  
- **Airtable API** 
- **Zendesk API** 

---

## How It Works
1. **User Question**: A user submits a question about a specific topic (e.g., PDF manual).  
2. **Workflow Trigger**: n8n workflow starts automatically.  
3. **RAG & AI Processing**:  
   - The **RAG system searches the knowledge source** for relevant information.  
   - AI generates a **concise and accurate answer**.  
4. **Store Response**: The answer is saved in Airtable.  
5. **Unanswered Cases**:  
   - If the RAG system cannot find enough information, a **Zendesk ticket** is created.  



