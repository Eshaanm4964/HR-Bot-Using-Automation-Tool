# HR_Bot 🤖📄

HR_Bot is an AI-powered HR automation system designed to handle employee queries, resume/document processing, and HR-related workflows using Large Language Models, vector databases, and event-driven automation.

## 🔍 Overview
HR_Bot automates repetitive HR tasks by combining:
- Conversational AI for employee interaction  
- Automated document ingestion from Google Drive  
- Intelligent email classification via Gmail triggers  
- Retrieval-Augmented Generation (RAG) using vector databases  

The system enables faster responses, reduced manual HR effort, and scalable HR operations.

## 🧠 Key Capabilities
- AI-powered HR chatbot for employee queries  
- Automatic knowledge base creation from documents  
- Gmail-triggered workflow automation  
- Intelligent text classification and routing  
- Context-aware responses using vector search  

## 🏗️ System Architecture
1. **User / Employee Interaction**
   - Chat messages handled via an AI Agent with memory support  

2. **Document Ingestion Pipeline**
   - Google Drive trigger detects new files  
   - Documents are downloaded and parsed  
   - Text is split using recursive character splitting  
   - Embeddings are generated using OpenAI  
   - Stored in a vector database for retrieval  

3. **Email Automation**
   - Gmail trigger listens for incoming emails  
   - Text classifier categorizes HR-related emails  
   - Relevant queries are routed to the AI agent  
   - Non-relevant emails are ignored automatically  

4. **Knowledge Retrieval**
   - Vector database used for semantic search  
   - AI agent retrieves relevant HR documents  
   - Generates accurate, context-aware responses  

## 🛠️ Tech Stack
- **LLMs:** OpenAI Chat Models  
- **Embeddings:** OpenAI Embeddings  
- **Vector Store:** Pinecone  
- **Automation:** Event-driven workflows  
- **Integrations:** Gmail API, Google Drive API  
- **Text Processing:** Recursive Text Splitter  

## 📌 Use Cases
- Employee policy queries  
- HR document Q&A (policies, onboarding docs, FAQs)  
- Resume or document-based HR workflows  
- Automated HR email handling  
- Internal HR knowledge assistant  

## 🚀 Getting Started
```bash
git clone https://github.com/your-username/HR_Bot.git
cd HR_Bot
pip install -r requirements.txt
python main.py
