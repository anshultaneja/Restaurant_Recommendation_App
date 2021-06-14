# Restaurant Food Recommendation

In this project I created a web application that can recommend a restaurant based on the restaurant you liked earlier.
I collected the data using **Web-scrapping** from Zomato-Api. I scrapped following features to make a dataset Name of restaurant, It's cuisines, Reviews List, Rating.
Then the data was preprocessed and saved in the csv file. I used the dataset to **train the model** using **cosine similarity**. I deployed my model using the **Flask** framework on Heroku Cloud Platform.


### 1. problem defination
Problem Build a system capable of recommending a restaurant based on your previous likes and other people with same likes.
A Recommendation System is an information filtering system that seeks to predict the rating a user would give for the item (in this case a restaurant). We can break down the large matrix of ratings from users and items into two smaller matrixes of user-feature and item-feature.


### 2. data
Web scraping is the process of collecting structured web data in an automated fashion. I scrapped the data using Zomato APi 

### 3. Data preprocessing and EDA

 Data preprocessing is a data mining technique which is used to transform the raw data in a useful and efficient format.
 One can see every preprocessing steps in my jupyter notebook provided with the code. 
 
### 4. Creating a model
 Cosine similarity measures the similarity between two vectors of an inner product space. It is measured by the cosine of the angle between two vectors and determines whether two vectors are pointing in roughly the same direction. It is often used to measure document similarity in text analysis. I used cosine similarity to train my model. 
 
### 5. Deployment
For deploying my web application I used Flask framework and deployed it on Heroku.
