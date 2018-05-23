# Risk-and-Return-The-Sharpe-Ratio
This project utilises a dataset containing stock returns and information of Facebook and Amazon shares. Using this information we use the  Sharpe Ratio concept to deduce which of the two stocks is the better pick 


Sharpe Ratio : sqrt(252) * abs(R1- R2)/stddev(R1,R2) 

description ::  252 - a figure that we multiply the ratio with which constitutes the working days( 365- approx(weekends, holidays)) ->
                to add a time variancy over calculations 
                
                R1 - stock 1 in portfolio 
                R2 - stock 2 in portfolio 
                
                stddev(R1, R2) - standard deviation of R1 wrt R2 
                
Conclusion : 
Higher the sharpe ratio, better it's history and hence better its chances are predicted to perform in thhe future

Platform  used :: Jupyter- python 3.6 
Authorisation : Project provided by DataCamp
