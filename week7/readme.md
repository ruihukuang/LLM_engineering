# Week 7  

## day 1  

Context  

Quantize a base model to 8-bits and 4-bits when you load it from Hugging face. Memory for a base model is reduced. 

Memory for a base model with 8-bits  

<img width="1568" height="160" alt="image" src="https://github.com/user-attachments/assets/477a3508-ae6c-4ffe-bb50-24107c80529c" />  

Memory for a base model with 4-bits  

<img width="1640" height="150" alt="image" src="https://github.com/user-attachments/assets/51d619cc-73bc-4d1e-890c-9e73855e2d09" />  


## day 2  

Context  

Load data from Hugging face. The data is about products description and their price. Use a base model meta-llama/Meta-Llama-3.1-8B and tokenizers to transform input test data about product description. Based on
the tokenizing input data, use a base model meta-llama/Meta-Llama-3.1-8B using quantizion configuration of 4-bits to predict product price. Compare it with actual data.  

The predict error is $396 shown in the screenshot below.  

<img width="2006" height="184" alt="image" src="https://github.com/user-attachments/assets/74e4344c-7c5b-42d0-8c52-b360edeaf675" />  


## day 3  and 4 

Context  

Load data from Hugging face. The data is about products description and their price. Use a base model meta-llama/Meta-Llama-3.1-8B and tokenizers to transform input test data about product description. Based on the tokenizing input data, a base model meta-llama/Meta-Llama-3.1-8B using quantizion configuration of 4-bits, train a model and load it to hugging face. Specify the configuration parameters for LoRA and also general configuration parameters for training.  

Use Weights & Biases to monitor training process in terms of system shown in the screenshot below.  

<img width="3698" height="1250" alt="image" src="https://github.com/user-attachments/assets/66a11476-27ea-48ff-ab3d-a33040d3d21a" />  

## day 5   

Load data from Hugging face. The data is about products description and their price. Use a base model meta-llama/Meta-Llama-3.1-8B and tokenizers to transform input test data about product description. Based on the tokenizing input data, use a fine tuned model from labs in day 3 and 4 to predict a product price from a weighted average of the top 3 predicted prices. Compare it with actual data.  

The predict error is $47 shown in the screenshot below. 

<img width="1912" height="194" alt="image" src="https://github.com/user-attachments/assets/d79c5123-35e5-4869-92f0-2b555d791eb9" />  




