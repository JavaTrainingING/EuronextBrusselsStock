#AdvanceJavaTraining@ING-OCT19 : Backend Assignment :  EuronextBrusselsStock

#Assignment Description
We would like you to create a Java based back-end application(REST API) the stocks listed in Euronext Brussels stock exchange(https://live.euronext.com/markets/brussels/equities/list).

It should contain the following REST endpoints:

Add a stock into Euronext.
GET List of all stocks.
GEt stock by stockId.
GEt stock by stockName.
Update the price of the stock.
DELETE the stock.
The list of stocks should come from a database like MySQL. The stock object contains at least the fields; stockId (Number), stockName (String), currentPrice (Amount) and lastUpdate (Time-stamp). Use the frameworks as you see fit to build and test this.

Implementation
Treat this application as a real MVP that should go to production.

Version Control
Commit the code to Github into your branch.


## Front-end Assessment
Create the web application(Front-end) to consume above mentioned REST API(Choose any language of your choice to develop the front-end application).