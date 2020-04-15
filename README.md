# COVID-19-Global-Outlook

![Image description](https://cdn.downtoearth.org.in/library/large/2020-03-01/0.01792700_1583044755_coronavirus-illustration-carousel.jpg)

**Coronavirus disease 2019 (COVID-19)** is an infectious disease caused by severe acute respiratory syndrome. The first disease was identified in Dicember 2019 in Wuhan. 
On March 11 2020, after 118,000 people being infected in 114 Countries, and causing the death of 4,291 people, **COVID-19 has been recognized as a pandemic**.
Today, April 13,2020, the pandemic infected 1,854,464 people in 185 countries, causing the death of 114,331 people.

In the context of the global COVID-19 pandemic, we follow the suggestions from Kaggle's competitions in order to provide useful insights about the virus' spread. Starting from a global exploratory analysis, then we focus on virus' modelling and prediction for the countries with the largest number of confirmed cases. For modelling, we implement SIR Model with some extensions and, for prediction, logistic and Gompertz model. At the end, we choose the best model based on R2 score, check the predictions' numbers about confirmed and fatalities for the next time interval and display some results from NLTK Sentiment analysis. 

**Multiple Datasources**:

[COVID19 Global Forecasting](https://www.kaggle.com/c/covid19-global-forecasting-week-4) 

[US_State Code](https://www.kaggle.com/corochann/usa-state-code/activity)

[Population by Country-2020](https://www.kaggle.com/tanuprabhu/population-by-country-2020)

[CBC News Coronavirus/COVID-19 Articles (NLP)](https://www.kaggle.com/ryanxjhan/cbc-news-coronavirus-articles-march-26) 




**TABLE OF CONTENTS**

1. **Exploratory data analysis (EDA)**

    1.1. Worldwide Trend
    
    1.2. Country-Wise growth
    
    1.3. Zoom up to
    
      1.3.1. Asia
      
      1.3.2. Europe
      
      1.3.3. US
     
 2. **Modelling**

    2.1. SIR model
    
    2.2. SIR-Model with Lockdown
    
      2.2.1. Fitting SIR with Lockdown to data
      
    2.3. SIR with time-dependent R_0 and CFR
    
      2.3.1. Fitting extended SIR to data
      
 3. **Prediction**
   
    3.1. Logistic model
    
    3.2. Gompertz model
    
    3.3  Results
    
 4. **NLTK Sentiment Analysis**

    4.1. Evolution of news
    
      4.1.1. January
      
      4.1.2. February
      
      4.1.3. March
      
    4.2 Results
    
    
    **Authors** : 
    Barbara Tarantino
    Marco Dibuono
