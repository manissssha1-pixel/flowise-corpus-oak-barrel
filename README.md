# flowise-corpus-oak---barrel
End-to-end AI chatbot for a café, showcasing conversational agents, vector databases, and memory-driven responses with Flowise and OpenAI.

# Oak & Barrel – AI Café Chatbot (OpenBarrier)

**Oak & Barrel** is an AI-powered café chatbot built under the *OpenBarrier* project.  
The system is designed to store structured café information and intelligently respond to customer queries using conversational AI and semantic retrieval.

This project demonstrates how modern LLM-based architectures can be used to create an interactive, context-aware virtual assistant for a café.



## Project Overview

The Oak & Barrel chatbot acts as a digital assistant for the café by:

- Storing café-related information (menu, timings, location, services, policies)
- Answering customer questions conversationally
- Maintaining conversation context across multiple turns
- Retrieving accurate information using vector search


## Key Features

- Conversational chatbot for café-related queries  
- Context-aware responses using conversation memory  
- Semantic search over stored café data  
- Modular and scalable AI architecture  



## Tech Stack & Components

- **ChatGPT (OpenAI)**  
  Core language model for natural, human-like responses

- **OpenAI Embeddings**  
  Converts café data into vector representations

- **Pinecone**  
  Vector database for fast and accurate semantic retrieval

- **Conversational Agent**  
  Orchestrates user interaction and tool usage

- **Conversation Summary Buffer Memory**  
  Maintains long-term conversational context efficiently

- **Retriever Tool**  
  Fetches relevant café information from Pinecone based on user queries



## How the System Works

1. Café information is embedded using **OpenAI Embeddings**
2. Embedded data is stored in **Pinecone**
3. User queries are processed by the **Conversational Agent**
4. Relevant context is retrieved using the **Retriever Tool**
5. **Conversation Summary Buffer Memory** preserves context
6. **ChatGPT** generates accurate, natural responses



## Use Cases

- “What are Oak & Barrel’s opening hours?”
- “Do you have vegetarian or vegan options?”
- “Where is the café located?”
- “What’s special today at Oak & Barrel?”



## Project Structure
Oak-Barrel/
│
├── chatflow.json          # Flowise chatflow configuration
├── README.md              # Project documentation
└── assets/                # (optional) café data or documents


## Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/<your-username>/oak-and-barrel.git