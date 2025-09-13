# Week 6  

## day 1  

Context  

Retrieve data from McAuley-Lab/Amazon-Reviews-2023 in hugging face related to Appliances. It has a title, a description, features,details and price for each item.  
To enable this dataset to have sufficient info to estimate price for each item and make training a model more efficiently, the text in this dataset is truncated to fit within around 180 tokens for each item. This tokenizing process is using meta-llama/Meta-Llama-3.1-8B.  


## day 2   

Context  

Retrieve data from McAuley-Lab/Amazon-Reviews-2023 in hugging face related to Automotive, Electronics, Office_Products, Tools_and_Home_Improvement, Cell_Phones_and_Accessories, Toys_and_Games, Appliances and Musical_Instruments. Create a sample dataset based on this dataset to make a range of prices
more balanced among items. Break down this sample dataset into a training and test dataset and save them in files called train.pkl and test.pkl. train.pkl file is too big to be loaded into github.  


## day 3  

Context  

Use files train.pkl and test.pkl to train tranditonal machine models and compare estimated prices and acutal prices to calculate average absolute predition error in terms of price differences.    
The tranditional models include Linear Regression, a Bag of Words model plus Linear Regression, word2vec plus Linear Regression, word2vec plus Linear SVR
and word2vec plus Random Forest regression.  
word2vec plus Random Forest regression performs the best among all models, generating the smallest predition price error $100 dollars.  

## day 4  

Context  

Use a file test.pkl and frontier models to estimate prices and compare estimated prices and acutal prices to calculate average absolute predition error in terms of price differences.   
The frontier models include Claude, gpt-40-mini, and gpt-40. 
gpt-40 performs the best among all frontier and traditional machine learning models, generating the smallest predition price error $76 dollars.  


## day 5  

Context  

Select 200 records from a file train.pkl to create a train and validation dataset in a file train.pkl.  
Convert these datasets into JSONL format and upload them to OPEN AI to do train runs. The model used for training is gpt-4o-mini-2024-07-18.  
Use Weights and Biases,a free platform for monitoring training runs.  
This fine tuned model does not perform better than the frontier model gpt-40, generating the smallest predition price error $102 dollars. 
Resources ussages in train runs from Weights and Biases   
<img width="3644" height="1360" alt="image" src="https://github.com/user-attachments/assets/4465227e-1ef0-4fbc-a6d4-028a593cff72" />  
Performance metrics in train runs from Weights and Biases  
<img width="3688" height="1292" alt="image" src="https://github.com/user-attachments/assets/aaac6709-3dd4-4f81-bf56-960b47c4bbe5" />  





