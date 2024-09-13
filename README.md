# Amazon Data Analysis: Excel Dashboard Creation
![Ama](https://github.com/user-attachments/assets/da1f61dd-082a-413b-ad59-472b3bfffa3c)

# Background : 
DataCo Analysis Group, a leading consultancy in business analytics, specializes in providing comprehensive insights into various industry sectors. This case study, "Streamline & Spotlight," focuses on the intersection of supply chain operations and digital consumer behavior. With a detailed dataset encompassing supply chain metrics (DataCoSupplyChainDataset.csv) and digital access logs (TokenizedAccessLogs.csv), DataCo Analysis Group plays an instrumental role in helping businesses optimize their operations and understand digital engagement. The supply chain dataset offers insights into sales, logistics, and delivery performance, while the access logs shed light on consumer online interactions and preferences. 

# Objective : 
The objective of this case study is to conduct an in-depth analysis of the combined supply chain and digital access datasets provided by DataCo Analysis Group. Students will utilize advanced Excel techniques to dissect these datasets, revealing key patterns and insights. The primary tasks include data cleaning, integration, analysis, and the development of a comprehensive, interactive dashboard. This dashboard will serve as a critical tool in visualizing supply chain efficiencies, customer engagement metrics, and the synergy between them. The project aims to augment DataCo Analysis Group's consulting capabilities, offering actionable insights to clients for optimizing supply chain processes and improving digital marketing strategies. 

# DataSets : 
There are two datasets used in this project:- 
## 1. Supply Chain Dataset:
Type:  Type of transaction made 

Days for shipping (real):  Actual shipping days of the purchased product 

Days for shipment (scheduled):  Days of scheduled delivery of the purchased product 

Benefit per order:  Earnings per order placed 

Sales per customer:  Total sales per customer made per customer 

Delivery Status:  Delivery status of orders: Advance shipping, Late delivery, Shipping canceled, Shipping on time 

Late_delivery_risk:  Categorical variable that indicates if sending is late (1), it is not late (0). 

Category Id:  Product category code 

Category Name:  Description of the product category 

Customer City:  City where the customer made the purchase 

Customer Country:  Country where the customer made the purchase 

Customer Email:  Customer's email 

Customer Fname:  Customer name 

Customer Id  :  Customer ID 

Customer Lname  :  Customer lastname 

Customer Password  :  Masked customer key 

Customer Segment:  Types of Customers: Consumer, Corporate , Home Office 

Customer State  :  State to which the store where the purchase is registered belongs 

Customer Street  :  Street to which the store where the purchase is registered belongs 

Customer Zipcode  :  Customer Zipcode 

Department Id  :  Department code of the store 

Department Name :  Department name of the store 

Latitude  :  Latitude corresponding to the location of store 

Longitude  :  Longitude corresponding to location of store 

Market  :  Market to where the order is delivered: Africa, Europe , LATAM, Pacific ,Asia, USCA 

Order City  :  Destination city of the order

Order Country  :  Destination country of the order 

Order Customer Id  :  Customer order code 

Order date (DateOrders)  :  The date on which the order is made 

Order Id | :  Order code 

Order Item Cardprod Id  :  Product code generated through the RFID reader 

Order Item Discount:  Order item discount value 

Order Item Discount Rate  :  Order item discount percentage 

Order Item Id  :  Order item code 

Order Item Product Price  :  Price of products without discount 

Order Item Profit Ratio:  Order Item Profit Ratio 

Order Item Quantity :  Number of products per order 

Sales  :  Value in sales 

Order Item Total  :  Total amount per order 

Order Profit Per Order  :  Order Profit Per Order 

Order Region  :  Region of the world where the order is delivered:  Southeast Asia,South Asia , Oceania ,Eastern Asia, West Asia, West of USA , US Center, West Africa, Central Africa,North Africa,Western Europe ,Northern , Caribbean , South America ,East Africa ,Southern Europe , East of USA ,Canada , Southern Africa , Central Asia ,  Europe , Central America, Eastern Europe , South of  USA 

Order State  :  State of the region where the order is delivered 

Order Status  :  Order Status : COMPLETE , PENDING , CLOSED , PENDING_PAYMENT ,CANCELED , PROCESSING ,SUSPECTED_FRAUD ,ON_HOLD ,PAYMENT_REVIEW 

Product Card Id  :  Product code 

Product Category Id  :  Product category code 

Product Description  :  Product Description 

Product Image  :  Link of visit and purchase of the product 

Product Name  :  Product Name 

Product Price :  Product Price 

Product Status  :  Status of the product stock :If it is 1 not available, 0 the product is available 

Shipping date (DateOrders) :  Exact date and time of shipment 

Shipping Mode  :  The following shipping modes are presented: Standard Class , First Class , Second Class , Same Day 
## 2. Access Logs Dataset: -
Product: Name of the product.

Category: Category of the product.

Date: Date and time of the access.

Month: Month of the access.

Hour: Hour of the day when the access occurred.

Department: The department to which the product belongs.

ip: IP address of the user accessing the website.

Url: Specific URL that was accessed on the website.

# Data Preprocessing : 

Imported both datasets into Power BI and performed an initial review to identify data quality issues or inconsistencies. Address any missing values, duplicate entries, and irrelevant data points to maintain data integrity. Convert columns to appropriate date formats and made some calculations using new measure and quick measure. Used DAX queries to get some other information and data to create charts and graphs for dashboard.

# Dashboards : 
![Dashboard_Image](https://github.com/user-attachments/assets/70990424-77b1-4d35-aaae-b8aa6436efe7)








