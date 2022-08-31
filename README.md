# Project-Airbnb


## Project
Project Topic:Share Economy

Team Member:Nick Carr,Bharat Guturi,Lin Huan Jhe

Introduction:

The share economy has quickly become a big part of our life and is continuing to grow and innovate industries at a rapid rate. We have decided to gain more insight into the use of Airbnb in Perth metropolitan area. Our end goal is to find out which areas are the most sought out places to stay, how long people stay in these areas and what is an expected price to pay for these places.

### Source
Our data was collected from http://insideairbnb.com/western-australia in which we cleaned the data to ensure we were only using columns that were going to allow us to ask and find answers from our data. Our focus accommodation type is entire house/apartment and private rooms, as these two types of accommodation make up roughly 98% of the Perth metropolitan market. 


### Questions
1.Which suburbs are the most popular to stay, based on the numbers of reviews? What factors may cause this?
![alt text](https://github.com/LynHJ/Project-Airbnb/blob/fafad5cb26cf28da81db9cf58b2a51860245eadb/OutputData/TotalReviews(Heatmap).png)
2.Are there any correlations between occupancy and price?
![alt text](https://github.com/LynHJ/Project-Airbnb/blob/fafad5cb26cf28da81db9cf58b2a51860245eadb/OutputData/result1.png)
![alt text](https://github.com/LynHJ/Project-Airbnb/blob/fafad5cb26cf28da81db9cf58b2a51860245eadb/OutputData/result2.png)
3.What is the average price between short, medium and long-term stays?
![alt text](https://github.com/LynHJ/Project-Airbnb/blob/fafad5cb26cf28da81db9cf58b2a51860245eadb/OutputData/result3.png)
4.What price should I advertise the property to ensure I get a booking?
![alt text](https://github.com/LynHJ/Project-Airbnb/blob/fafad5cb26cf28da81db9cf58b2a51860245eadb/OutputData/result3.png)

#### Summary
1.We use the heatmap method to visualise our data. We can easily see that Fremantle, Perth, and Stirling are the most popular areas.  
2.After doing Regression Analysis, we made a conclusion that travelers who use Airbnb to rent accommodations would choose the locations based on their personal preference rather than renting costs.  
3.We choose 3 of the most popular areas as our targets. We found out that the renting cost would increase or decrease when the renting periods vary. This result might give travelers an idea about deciding where to live when they arrange their different durations of holiday.  
4.We groupby suburbs and calculate the average costs of rental. The result could assist hosts to rent out their properties.  

## Content:
Project  
|  
|&nbsp;-InputData:&nbsp;|-neighbourhoods.csv  
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|-listings.csv  
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|-reviews.csv  
|-OutputData:|-avg_price_entire_apt.csv  
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|-avg_price_private_room.csv  
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|-Price(Heatmap).png  
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|-TotalReviews(Heatmap).png  
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|-result1.png  
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|-result2.png  
|&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;|-result3.png  
|-Project_Airbnb.ipynb  
|-Presentation_file.txt  
|-Project Draft.docx  
|-README.md  

## Installation
1.conda env create -n PythonData --file intro_python_requirements_osx.yml python=3.7  
2.pip install notebook  
3.jupyter nbextension enable --py --sys-prefix widgetsnbextension  
  conda install -c conda-forge gmaps  
  jupyter nbextension enable --py --sys-prefix gmaps  
4.conda install matplotlib  
  

## Prerequisites
Get a free API Key at https://cloud.google.com/maps-platform/
Clone the repo
git clone https://github.com/your_username_/Project-Name.git
Create a api-keys.py to put your API in
gkey = 'ENTER YOUR API'

Appendix/Reference
1.http://insideairbnb.com/western-australia
2.https://www.stratosjets.com/blog/airbnb-statistics/
3.https://www.businesswire.com/news/home/20220617005279/en/Global-Online-Food-Delivery-Services-Markets-2022-2026-2031-with-takeaway.com-Doordash-Deliveroo-Uber-eats-Zomato-Dominating---ResearchAndMarkets.com#:~:text=The%20market%20is%20expected%20to,(CAGR)%20of%205.6%25.
4.https://www.stratosjets.com/blog/airbnb-statistics/

