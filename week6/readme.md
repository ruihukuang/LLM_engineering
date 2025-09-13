# Week 6  

## day 1  

Context  

Retrieve data from McAuley-Lab/Amazon-Reviews-2023 in hugging face related to Appliances. It has a title, a description, features,details and price for each item.  
To enable this dataset to have sufficient info to estimate price for each item and make training a model more efficiently, the text in this dataset is truncated to fit within around 180 tokens for each item.  


## day 2   

Context  

Retrieve data from McAuley-Lab/Amazon-Reviews-2023 in hugging face related to Automotive, Electronics, Office_Products, Tools_and_Home_Improvement, Cell_Phones_and_Accessories, Toys_and_Games, Appliances and Musical_Instruments. Create a sample dataset based on this dataset to make a range of prices
more balanced among items. Break down this sample dataset into a training and test dataset and save them in files called train.pkl and test.pkl. train.pkl file is too big to be loaded into github.  


## day 3  

Context  

Use files train.pkl and test.pkl to train tranditonal machine models and compare estimated prices and acutal prices to calculate price differences. 
The trandition models include 
