# Coursera-Capstone-Project
In this project we will focus on using the location data to explore interesting problems in real word!
The project title is:
**Location recommendation for *Chinese Restaurant* in *Columbus*.**

## Table of content
 1. Introduction/Business Problem
 2. Solution (Methodology)
 3. Result /Discussion /Conclusion
 4. Acknowledgement
 
## 1. Introduction/Business Problem
Let say if you are a buisiness manerger who want to invest a *Chinese restaruant* in your resident city. You are live in the mid-size city which has fast growth. You have to decide where or which **neighberhoods** to open the restaruant.  
In order to answer this question, you have to build a model get some recommendations where to start your business.   
+ Therefore, we will learn a model from a mature city/metropolitan city since we believe that it is more develeped. Your city will become a metropolis some day.
+ Another thing you believe is that any one of business venue does not exist alone,and "Chinese restaruant" always tends to be find with some other type of shops,because neighberhoods have "cultures" to like them both.
## 2. Solution (Methodology)
### How can we learn?
  Therefore, we will use **Regression** method to learn and predict number of the *Chinese restaruant* in a neighberhood by providing the venues information of **Toronto** City. Venues information is discoverd from [Foursquare](https://foursquare.com/) API. 
- [explore and cluster the neighborhoods in Toronto](https://github.com/yuyongze2014/coursera-capstone-project/blob/master/explore%20and%20cluster%20the%20neighborhoods%20in%20Toronto.ipynb)
- [explore and cluster the neighborhoods in Toronto2](https://github.com/yuyongze2014/coursera-capstone-project/blob/master/explore%20and%20cluster%20the%20neighborhoods%20in%20Toronto2.ipynb)
-  [explore and cluster the neighborhoods in Toronto3](https://github.com/yuyongze2014/coursera-capstone-project/blob/master/explore%20and%20cluster%20the%20neighborhoods%20in%20Toronto2.ipynb)

Then, you will the build model to pridict the number of *Chinese restaruant* in your city and compare with exiting number of *Chinese restaruant*. And a potaitial place to start your business!

#### How can we achieve the data?
In this project, we will us *Columbus,OH* as example, to see how we can achieve it.
Neighborhoods infomation is get from [city-data.com](http://www.city-data.com/nbmaps/neigh-Columbus-Ohio.html) 
And the location infomation is get from (https://www.gps-coordinates.net/)

## 3. Result/Discussion/Conclusion
We get 10 top recommendations of location to start you business on Chinese Restaruant in Columbus. 
The detailed information is in this document:
(https://github.com/yuyongze2014/coursera-capstone-project/blob/master/Coursera-Capstone-Project.pdf)

The original script notebook is [here](https://github.com/yuyongze2014/coursera-capstone-project/blob/master/Capstone-project-Chinese-Restaurant%20.ipynb)

This methods can be further impelemented into discover any type of venue in any city. So that a **recommendation system** can be constructed in the futher.

## 4. Ackowledgement 
In this project, we have to acknowledge the data science course provided by IBM powered by Coursera



