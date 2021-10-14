PROBLEM STATEMENT:
A) INTRODUCTON:
				On June 2015, 2016 debt negotiations between Greek Govt and its creditors borke off abrubptly. Large market movements as a concequence of political and economic headlines are hardly uncommon, liquid markets are most suspectable to swing when the news breaks. Using VIX as a proxy for market volatality, we investigate how macroeconoic headlines affect the changes. Here, we predict equity market value using tweets from major news sources, investment banks and notable economists.

B) TYPE OF PROBLEM:
				Twitter provides a plethora of market data. In this project we have extracted around 100,000 tweets from various accounts to predict the upward movements. Using this data we are researching how this economic news affects the market.
				
EXPLORATORY DATA ANALYSIS:
				EDA includes extracting the twitter data based on the stock names viz, Apple, Tesla, Nvidia, Paypal and Microsoft, cleaning of twitter data that were pulled i.e., removing unnecessary data from tweets. After cleaning the data, below are the plots that were plotted against the sentiments that is Positive, Negative and Neutral. 
				
![Top 30 most frequently occuring words](https://user-images.githubusercontent.com/72445337/137369455-7672b8e9-d683-4dc8-adfa-3913515f631b.PNG)
![Word cloud](https://user-images.githubusercontent.com/72445337/137369669-bed2eedd-5ddf-4c65-9551-201fcf682803.PNG)
![Sentiment analysis](https://user-images.githubusercontent.com/72445337/137369836-4ea7a934-6a82-4622-a0e7-1911c713f33d.PNG)

MODELLING:
	We have implemented differnt ML models Linear Regression, Random Forest Regression, Gradient Boost Regression methods. We have choosen Random Forest Regression ML for our project, as this model is best suited for Regression based problems.

DEPLOYMENT:
	We have deployed the model using Streamlit framework, as it is a opensource Python library that allows us to create beautiful web apps for Machine Learning. It is hosted on Heroku, as it a container based Platform As A Service(PAAS), because it is flexible and easy to host on this platform. 

Deployment Link: 

https://predictionsvola.herokuapp.com/

Video Link:

https://user-images.githubusercontent.com/72445337/137373534-70494eb3-7671-428b-969e-334f0da6d0f2.mp4

Team Members:

Alpesh Godre
Navya P
Kushwanth








				
