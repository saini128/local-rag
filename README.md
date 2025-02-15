# SuperEasy 100% Local RAG with Ollama

### Setup
1. git clone https://github.com/saini128/local-rag.git 
2. cd dir
3. pip install -r requirements.txt
4. Install Ollama (https://ollama.com/download)
5. ollama pull llama3.2:3b (etc)
6. ollama pull mxbai-embed-large
7. run upload.py (pdf, .txt, JSON)
8. run localrag.py (with query re-write)
9. run localrag_no_rewrite.py (no query re-write)


### Latest Updates
- Upload.py (v1.2)
   - replaced /n/n with /n 
- New embeddings model mxbai-embed-large from ollama (1.2)
- Rewrite query function to improve retrival on vauge questions (1.2)
- Pick your model from the CLI (1.1)
  - python localrag.py --model mistral (llama3.2:3b is default) 
- Talk in a true loop with conversation history (1.1)
   


### What is RAG?
RAG is a way to enhance the capabilities of LLMs by combining their powerful language understanding with targeted retrieval of relevant information from external sources often with using embeddings in vector databases, leading to more accurate, trustworthy, and versatile AI-powered applications

### What is Ollama?
Ollama is an open-source platform that simplifies the process of running powerful LLMs locally on your own machine, giving users more control and flexibility in their AI projects. https://www.ollama.com
