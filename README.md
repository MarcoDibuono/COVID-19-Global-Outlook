# COVID-19-Global-Outlook

![Image description](https://cdn.downtoearth.org.in/library/large/2020-03-01/0.01792700_1583044755_coronavirus-illustration-carousel.jpg)

Coronavirus disease 2019 (COVID-19) is an infectious disease caused by severe acute respiratory syndrome. The first disease was identified in Dicember 2019 in Wuhan. 
On March 11 2020, after 118,000 people being infected in 114 Countries, and causing the death of 4,291 people, COVID-19 has been recognized as a pandemic.
Today, April 13,2020, the pandemic infected 1,854,464 people in 185 countries, causing the death of 114,331 people.

In the context of the global COVID-19 pandemic, we follow the suggestions from Kaggle's competitions in order to provide useful insights about the virus' spread. Starting from a global exploratory analysis, then we focus on virus' modelling and prediction for the countries with the largest number of confirmed cases. For modelling, we implement SIR Model with some extensions and, for prediction, logistic and Gompertz model. At the end, we choose the best model based on R2 score, check the predictions' numbers about confirmed and fatalities for the next time interval and display some results from NLTK Sentiment analysis. 

Data: [COVID19 Global Forecasting](https://www.kaggle.com/c/covid19-global-forecasting-week-4) 


**TABLE OF CONTENTS**

1. [Exploratory data analysis (EDA)](#section1)

    1.1. [Worldwide Trend](#section11)
    
    1.2. [Country-Wise growth](#section12)
    
    1.3. [Zoom up to](#section13)
    
      1.3.1. [Asia](#section131)
      
      1.3.2. [Europe](#section132)
      
      1.3.3. [US](#section133)
      
 2. [Modelling](#section2)

    2.1. [SIR model](#section21)
    
    2.2. [SIR-Model with Lockdown](#section22)
    
      2.2.1. [Fitting SIR with Lockdown to data](#section131)
      
    2.3. [SIR with time-dependent R_0 and CFR](#section21)
    
      2.3.1. [Fitting extended SIR to data](#section131)
      
  3. [Prediction](#section3)

     3.1. [Logistic model](#section31)
    
     3.2. [Gompertz model](#section32)
    
      
