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

Context  

A RAG system plus vector embeddings using OpenAIEmbeddings(Auto-Encoding LLMs) is used to create a vectore store chroma in LangChain based on the following process:  

Use LangChain to build a knowledge base. Read in the documents in all folders. Add metadata to the documents. Break down the contents into overlapping chunks. Put the chunks of data into a Vector Store that associates a Vector Embedding with each chunk. 

In addition,  the vector Store is visualized. Relavent info are automatically close to each other in the 2D or 3D graph.  


## day 4   

Context  

Create a RAG pipeline with a LLM model, a vector store and memory. THe LLM model is gpt-4o-mini. The vector store is chroma in LangChain. A chatbox is based on this pipeline.  

This search is not case sensitive and could generate outputs when a part of an input for example an employee name is not complete. But it could not provide outputs when an input partically matches info in the chunks. Sometimes it could provide hints for relevant info when it does not know an answer. It also could not provide outputs when an input is misspelled.  

Screeshots show outputs.  

<img width="2420" height="832" alt="image" src="https://github.com/user-attachments/assets/e864edf9-2698-4aa3-8ab2-de6c529a2385" />  

<img width="2442" height="706" alt="image" src="https://github.com/user-attachments/assets/4e47c865-3572-460c-a232-ae3865d54bf8" />  


## day 4.5  

Context  

Create a RAG pipeline with a LLM model, a vector store and memory. THe LLM model is gpt-4o-mini. The vector store is FAISS in LangChain. A chatbox is based on this pipeline.  

This search is not case sensitive and could generate outputs when a part of an input for example an employee name is not complete. It also could not provide outputs when an input is misspelled. But it could not provide outputs when an input partically matches info in the chunks. It could not provide hints for relevant info when it does not know an answer.  

Screeshots show outputs. 

<img width="2452" height="838" alt="image" src="https://github.com/user-attachments/assets/8b278a5a-d857-4ead-9766-539f95222221" />   

<img width="2440" height="860" alt="image" src="https://github.com/user-attachments/assets/0f1c169c-f4f5-411d-9806-85491692e04c" />  


## day 5  


Context  

When a chatbox could not provide outputs, it requires debugging using StdOutCallbackHandler to check prompt details. In this lab, increasing the number of chunks to be used in chatbox improves outputs.  

Before changes, outputs are shown in the screenshot.  

<img width="2528" height="878" alt="image" src="https://github.com/user-attachments/assets/62da54cd-ba22-4030-9864-a6e2f2253b78" />  


After changes, outputs are shown in the screenshot.  

<img width="2524" height="746" alt="image" src="https://github.com/user-attachments/assets/624f4d83-3a1a-4daa-b7e0-dc13f2983167" />  




