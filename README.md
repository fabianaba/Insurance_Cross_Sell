# Insurance All - Cross Sell
[Classification Techniques][Learn to Rank, LTR System] Prediction of most probable current customers to purchase a new product, a _vehicle insurance_.

![PA004](https://github.com/fabianaba/Insurance_Cross_Sell/blob/master/pa004.png)

## 1. Business problem

<i>Insurance All</i> is a fictitious insurance company that traditionally has provided Health Insurance and now intends to offer its customers a new product, a Vehicle Insurance. In order to achieve this purpose efficiently, it gathered some information about 304,000 of their current customers and asked if they would be interested in purchasing a vehicle insurance. The dataset features are:

* __id__: Unique ID for the customer
* __Gender__: Gender of the customer
* __Age__: Age of the customer
* __Driving License__: Whether the customer has a driving license or not
* __Region Code__: Unique code for the location of the customer
* __Previously Insured__: Whether the customer already has a vehicle insurance or not
* __Vehicle Age__: Age of the vehicle
* __Vehicle Damage__: Whether the customer already had a vehicle that has suffered damage in the past or not
* __Annual Premium__: The amount paid by the customer annually for the current Health Insurance
* __Policy Sales Channel__: Anonymized code for the channel of outreaching the customer
* __Vintage__: Amount of time (in days) the customer is under the current term for the health insurance
* __Response__: Whether the customer is interested in purchasing a Vehicle Insurance or not

The company has hired a Data Science consulting firm to define a data-driven marketing strategy to sell the new product by clarifying some questions:

1. Among all the features gathered, which ones show more evidence of a client's intention of purchase a car insurance?

2. If the team sales is able to make 20,000 calls to offer the product, which fraction of a new group of 76,000 customers would be reached?

3. If the sales team is now able to make 40,000 calls, which fraction of the customers would be reached?

4. How many calls does the sales team need to make in order to reach 80\% of the interested customers?

In order to answer these questions, the machine learning model must inform the probability for each client to purchase the vehicle insurance, and the new database must be sorted by this information. Having the clients with higher probabilities ranked on top, the questions above would be properly addressed.

## 2. Business assumptions

* Pursuing Vehicle Insurance is NOT mandatory in this case study scenario.

* The sales team works with Google Sheets as a corporate tool. The solution must be presented in the same format.

## 3. Solution planning

* __3.1. Final product__:

What will actually be delivered?

A feature within the Google Sheets tool, which sorts the 76,000 customers (or any new customers included in the spreadsheet) by purchase tendency.

* __3.2. Tools__:

What tools will be used in the process?

* Python 3.8.12

* Jupiter Notebook

* Git and Github

* Coggle Mindmaps

* SweetViz

* Heroku Cloud

* Regression and Classification Algorithms

* Machine Learning packages sklearn and xgboost

* Attribute Selection Techniques

* Flask and Python API's

* Google Sheets Apps Script.










#### <i>  --- This is an ongoing project and the next steps will be added as soon as they have been reached.</i>