🤖 Conversational AI Chatbot
This project is a simple conversational AI chatbot built using natural language processing and machine learning techniques. It can interact with users in a human-like manner and provide responses based on user input.
---

📌 Features
Understands user input and gives intelligent responses

Built using Python and machine learning libraries

Supports customizable intents and responses

Easily extendable for different domains or use cases

---
🛠 Technologies Used
Programming Language:
Python 3.x

🧠 Machine Learning & NLP Libraries:
PyTorch – Backend for deep learning models

Transformers (Hugging Face) – To load and run the Flan-T5 language model

Sentence-Transformers – For converting text into semantic embeddings

FAISS – Fast vector similarity search for retrieval

📄 PDF Processing:
PyMuPDF (fitz) – For extracting raw text from PDF files

🔍 LangChain Modules:
langchain.embeddings.SentenceTransformerEmbeddings – Embedding wrapper

langchain.vectorstores.FAISS – Vector store interface

langchain.text_splitter.TokenTextSplitter – Token-based chunking

langchain.chains.RetrievalQA – Retrieval-augmented QA pipeline

langchain.llms.HuggingFacePipeline – LLM abstraction for Hugging Face pipelines
---
📂 Project Structure
conversational-ai-bot/
│
├── intents.json            # Intent and response mappings
├── chatbot.py              # Main logic for the chatbot
├── train_model.py          # Script to train and save the ML model
├── app.py                  # (Optional) Streamlit or Flask app
├── requirements.txt
└── README.md
---
**📂 Results**
![image](https://github.com/user-attachments/assets/35075798-87ec-438c-95cb-1a2b3329be83)
![image](https://github.com/user-attachments/assets/09a2ecce-a87b-4a82-8638-f6c6e5b5ea11)



📬 Contact
Syeda Zuberiya
📧 syedazuberiya7@gmail.com
