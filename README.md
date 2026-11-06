# Mindora – AI Chatbot

## Project Description
Mindora is a simple AI-powered chatbot developed using a Local Large Language Model (LLM), Ollama, Streamlit, and LangChain Memory. 
It provides interactive conversations and remembers previous messages using different memory techniques.

## Objectives
- To develop an AI chatbot using a local LLM.
- To implement conversation memory using LangChain.
- To maintain conversation context.
- To provide a simple and user-friendly interface.
- To run the chatbot locally without depending on cloud-based LLM services.

## Technologies Used
- **Programming Language:** Python
- **Frontend:** Streamlit
- **LLM Framework:** Ollama
- **Language Model:** Gemma 3 (1B)
- **AI Framework:** LangChain
- **Memory Management:** LangChain Memory

## Features
- Interactive AI chatbot.
- Local LLM integration using Ollama.
- Buffer Memory to store complete conversation history.
- Summary Memory to maintain summarized conversation context.
- Window Memory to remember recent conversation messages.
- Option to select different local LLM models.
- Clear Current Chat option.
- Clear All Memories option.
- Simple and user-friendly interface.

## Memory Types

### 1. Buffer Memory
Stores the complete conversation history and helps the chatbot remember previous messages.

### 2. Summary Memory
Summarizes previous conversations to maintain important information in a compact form.

### 3. Window Memory
Stores a limited number of recent conversation messages.

## Working Principle
1. The user enters a message in the Streamlit chat interface.
2. The message is passed to the local LLM through Ollama.
3. LangChain Memory manages the conversation history.
4. The selected memory type provides previous conversation context.
5. The LLM generates a response based on the current message and available context.
6. The response is displayed in the Streamlit interface.

## Installation and Execution

### Step 1: Install Python
Install Python on your system.

### Step 2: Install Ollama
Download and install Ollama from:
https://ollama.com/

### Step 3: Download the Model
```bash
ollama pull gemma3:1b
```

### Step 4: Clone or Download the Project
Open the project folder in Visual Studio Code.

### Step 5: Create a Virtual Environment
```bash
python -m venv venv
```

### Step 6: Activate the Virtual Environment
```bash
venv\Scripts\activate
```

### Step 7: Install Required Packages
```bash
pip install -r requirements.txt
```

### Step 8: Run the Application
```bash
streamlit run app.py
```

The application will open in the browser at:
http://localhost:8501

## Expected Output
The Mindora AI Chatbot provides an interactive chat interface where users can ask questions and receive AI-generated responses. 
It remembers conversation details based on the selected memory type.

## Advantages
- Runs using a local language model.
- Supports different conversation memory techniques.
- Easy to use and understand.
- Provides contextual responses.
- Reduces dependency on cloud-based AI services.

## Conclusion
Mindora AI Chatbot successfully demonstrates the integration of a Local LLM with LangChain Memory. 
It provides interactive conversations and maintains context using Buffer Memory, Summary Memory, and Window Memory. 
This project helps understand the practical implementation of conversational AI systems.
