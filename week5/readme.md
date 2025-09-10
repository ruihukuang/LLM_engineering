# Week 5  

## day 1  

Context  

Build a simple RAG system. There is a knowledge base of the company shared drive. The task is to build an AI knowledge worker. If a question is related to employees or products by name, add relevant details to the prompt.  

The screenshot below shows UI of this system.  

This system is case sensitive and may not retrieve info when an input for example an employee name is not complete.  

<img width="3210" height="1952" alt="image" src="https://github.com/user-attachments/assets/fb5763cc-0427-41f3-81f9-7989e504cbcc" />  





## day 2  

Context  

A RAG system is built based on the following process:  

Use LangChain to build a knowledge base. Read in the documents in all folders. Add metadata to the documents. Break down the contents into overlapping chunks. Use a function to find search words in chunks.   

The search is also case sensitive. But it could generate outputs when a part of an input for example an employee name is not complete.  

Screenshots below show outputs for some inputs.  

<img width="3014" height="1448" alt="image" src="https://github.com/user-attachments/assets/ce500176-5ea2-4038-9926-2cc9f4e62da2" />   


<img width="3082" height="806" alt="image" src="https://github.com/user-attachments/assets/17229109-17b1-4e75-ac02-5977bda4dcdc" />  


## day 3  

A RAG system plus vector embeddings using OpenAIEmbeddings(Auto-Encoding LLMs) is used to create a vectore store chroma in LangChain based on the following process:  

Use LangChain to build a knowledge base. Read in the documents in all folders. Add metadata to the documents. Break down the contents into overlapping chunks. Put the chunks of data into a Vector Store that associates a Vector Embedding with each chunk. 

In addition,  the vector Store is visualized. Relavent info are automatically close to each other in the 2D or 3D graph.  


## day 4   

Create a RAG pipeline with a LLM model, a vector store and memory. THe LLM model is gpt-4o-mini. The vector store is chroma in LangChain. A chatbox is based on this pipeline.  

This search is not case sensitive. 



