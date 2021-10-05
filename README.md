# Data-Mining-using-Clustering
This mini project finds out a real-world problem and proposes a solution for it using  data mining techniques such as K-means clustering and Hierarchical clustering.


## BACKGROUND

  The dataset selected for the project contains more than 500,000 transactions occurred between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers. The dataset includes information such as InvoiceNo, StockCode Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country of the customer.
##### Online Retail Dataset : https://www.kaggle.com/hellbuoy/online-retail-customer-clustering

  The objective of this project is to identify the customer base of this business and the best sets of customers whom the company should target, according to their interactions with the business. This will help the company to promote their items to selected customers who will be most likely to buy their items or service, and decide on whether they want marketing, if so what type of marketing they need.

## TARGET AND BUSINESS GOALS

According to the scenario the business wants to know:

• Who does most business with us?

• Who are the most persistence customers?

• Do our customers hang around for the long run?

We aim to segment the Customers based on RFM so that the company can target its customers efficiently.

• R (Recency): Number of days since last purchase 

• F (Frequency): Number of transactions 

• M (Monetary): Total amount of transactions (revenue contributed)


## CHOICE OF TECHNOLOGY

✓ The dataset was analysed the and pre-processed to optimize the accuracy, and 
implemented the model using <b>Python</b>.

✓ User Interfaces (UIs) has created using <b>Streamlit</b>. It is an open-source Python library 
that allows to create and share, custom web apps.
https://docs.streamlit.io/en/stable/tutorial/create_a_data_explorer_app.html

✓ The application was hosted using <b>Heroku</b>. It is a container-based cloud Platform as a 
Service (PaaS) which we can use to deploy, manage, and scale apps.

## APPROACH

• Step 1 : Reading and exploring the data.

• Step 2 : Data cleansing

• Step 3 : Data preparation (RFM)

• Step 4 : Model Building (K-means Clustering and Hierarchical Clustering)

• Step 5 : Final Analysis


##### Link to the web application : https://onlineretailclustering.herokuapp.com/
