# Assignment 3 – Retrieval-Augmented Generation (RAG) using LangChain

This project is part of my GenAI assignment where I implemented a basic RAG (Retrieval-Augmented Generation) pipeline using LangChain.  
The system loads a text document, splits it into chunks, creates vector embeddings, stores them in Chroma, and answers user queries using a retriever + mock LLM.



## What I Did

- Used a sample `.txt` document containing unit-wise syllabus content
- Loaded the document using `TextLoader`
- Split the text into manageable chunks using `CharacterTextSplitter`
- Converted chunks to embeddings using `HuggingFaceEmbeddings`
- Stored embeddings in `Chroma` vector database
- Built a retriever and a QA system using `RetrievalQA`
- Used a simulated LLM to show the pipeline works end-to-end






