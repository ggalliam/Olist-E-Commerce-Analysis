# Olist E-Commerce Analysis

<img width="363" height="228" alt="Screenshot 2026-04-23 at 9 02 08 PM" src="https://github.com/user-attachments/assets/1642f5a6-0674-40ea-b4a0-84ed38df1aa9" />


## Objective

Olist is a Brazilian e-commerce platform that connects businesses to customers across Brazil. It is a marketplace, where merchants can list their products and services and customers can browse and purchase them online. E-commerce landscape in Brazil can be observed through looking at a company like Olist to identify opportunities for growth and optimization.

In order to optimize growth, this analysis is looking closer into specific sales, customer profiles, and individual shop performance to improve revenue and customer satisfaction.

## Dataset

Olist E-commerce dataset contains over 100k+ rows of information from September of 2016 to October of 2018. During this time period 99,441 products were sold. The dataset is divided in 8 files: orders, payments, reviews, items, products, sellers, customers, geolocation.

<img width="665" height="403" alt="Screenshot 2026-04-23 at 9 00 32 PM" src="https://github.com/user-attachments/assets/20d75e3c-c2f3-427d-a1c4-7ae480e84f84" />


## Business Problem 

Some key quations will navigate further optimization strategies for the company. 

- Which product is the all time bestseller? Which category of products is bringing in the most profit?
- How do customers influnce the revenue of the company? Which factors are essential and determine future profits?
- Overall, what is the revenue of every shop? Why do they differ?
- What is the revenue of Olist as a whole? 

This project evaluates how revenue is distributed across sellers and product categories. It identifies top-performing products and examines marketplace concentration. These insights inform strategies to improve platform resilience and seller diversification. Findings in customer and marketplace individualistic factors, that affect different revenues, will immensely support targeted optimization of supply chain operations.

## Methodology 
  
The analysis involves data cleaning, transformation, and integration across multiple relational datasets. 
SQL is used for querying and aggregation, while Python (pandas) supports data manipulation and exploratory analysis. 
Data visualization techniques are applied to communicate insights effectively.

## Insights 

**Selling Permornace**

In 2016, the top-selling product by category was furniture (decor). 
In 2017 it was bed_bath_tables. 
Between 2016 and 2018, computer accessories were selling the most growth rate withing a two year span. 

<img width="1089" height="484" alt="Screenshot 2026-04-23 at 9 38 00 PM" src="https://github.com/user-attachments/assets/3ca704a9-dcff-4468-91db-e7fd5c335f92" />


The highest profit margin of 79% is home_comfort_2. The lowest is small home_appliances_2. Since the margin between the categories is pretty big, about 10%, then Olist can implement strategies for low-profit margin products, like home appliances like promotions and discounts. 

<img width="1043" height="429" alt="Screenshot 2026-04-23 at 9 53 44 PM" src="https://github.com/user-attachments/assets/3ff11d73-e191-4d03-878c-f3e64c5aafc7" />


**Customer Profile**

In order to undertand how revenue is effected, it is crucial to look at the revenue data first. Overall, timeline is reperesenting a consistent growth thoughout the years besides September of 2018 but it could be explained by the end of transaction period of the dataset. However, it is still visisble a clear trend of revenue growth. 


<img width="845" height="450" alt="Screenshot 2026-04-23 at 11 03 03 PM" src="https://github.com/user-attachments/assets/3ff775c3-df25-441d-9472-7ba9f22e8c7b" />


Multiple interesting observations are seen after looking at customer reviews and how they are correlated to the frequency of purchases. 


## Key Findings

### Sales
R$15.8M total revenue across 99K orders (Sep 2016 – Oct 2018) with strong month-over-month growth peaking in late 2017
Health & beauty, watches, and bed/bath/table are the top revenue categories
Credit cards dominate (~74% of payment value); boleto (bank slip) is a distant second
### Customer Behaviour
Extremely low repeat rate (3.1%) — nearly all customers are one-time buyers, signaling a major retention opportunity
Weekdays drive volume — orders drop ~30% on weekends; peak hours are 10 AM – 4 PM
São Paulo accounts for ~42% of customers — heavy geographic concentration in the Southeast
### Delivery Performance
Median delivery: 10.2 days | Average: 12.6 days | 95th percentile: 29.3 days
8.1% of deliveries are late — actual delivery consistently beats estimates on average, but long-tail delays remain
Northern states (AM, RR, AP) average 20–28 day deliveries — 2× the national average
### Satisfaction Drivers
59% of reviews are 5-star, but 10% are 1-star — a polarized distribution
Late deliveries are the #1 satisfaction killer: on-time orders average 4.3★ vs 2.6★ for late orders (46% of late orders get 1★)
High freight ratios hurt: orders where shipping > 40% of total value score ~0.3★ lower
Office furniture, fixed telephony, and security/services are the worst-rated categories
