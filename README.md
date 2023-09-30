# Python-class-1
DAY 1 and 2:
we had learnt about the basics of python, solves few coding exercises.

DAY 3, 4, 5:
WE had learnt about SGQ.
  S:Scenario ; G:GAP ; Q:Quest
We leant about the outcomes and action [outcome-how they are benefited. Action: how we r benefited]
100% ---70% Training
     ---30% Testing
Based on this we have to form a 1. problem statement -- like anything based on weather, revenue, stalk marketting, optimisation etc.
                                2. SGQ has to be done
                                3. Problem representation.
Bases on this EDA has to be done [by plotting graphs, flowcharts]
4. Modelling
5. Performance matrices
Lastly two types of presentation has to be done, 1.TECH and 2.NON-TECH
TECH PRESENTATION includes:-
      1.Problem statement
      2. SGQs
      3. Problem representation
      4. Actual solution
NON-TECH PRESENTATION includes:-
      1. EDA -- plots + inference
      2. Forecasting specific EDA
      3. Model
      4. Performance matrices

      
DAY 6 and 7 :
We laernt about boxplots
we had calculated the mean and percetile


DAY 8 and 9:
We learnt about ANOVA, ARIMA model and SERIMA model
ANOVA:: --- Ho [null]
       ---- Ha [Alternate]
       these two constitued together gives a model as an end result.
       
ARIMA MODEL [Auto Regressive Integrated Moving Average]:::
    First, we have to do HYPOTHESIS TESTING INFERENCE
    we take some input-xyz with the help of parametres p,d,q
    we get a model, if its less than 15% we have to do hypertuning after which we get the final output.
    Here, p and q -- can be used to calculat minimum of PACF and ACF
          d-- it is used to differentiate or differencing or subtract
Seasonality graphs are of 2 types: 1. Product/multiplicative graph
                                   2. Additive graph
*Data entry values should be equal[70-70]
*There should be more similarity ratio.
*Now, if we get 98% similarity, hyper tuning is restricting the model.
*Once we get negative values we have to stop.

AIC:-Summary has to be given
   :-Model has to predict the values
   :-Forecast values

SERIMA MODEL:
It is way similar to ARIMA model, but the only difference is we include p,d,q,and s [where s stands for seasonality check]
