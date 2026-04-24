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

- Which product is the all time bestseller? Which products are bringing in the most profit out of all?
- What is the average profit from a singular customer? Are thre any factors that affect the amount of money a customer spends?
- Overall, what is the revenue of every shop? Why do they differ? 

This project evaluates how revenue is distributed across sellers and product categories. It identifies top-performing products and examines marketplace concentration. These insights inform strategies to improve platform resilience and seller diversification. Findings in customer and marketplace individualistic factors, that affect different revenues, will immensely support targeted optimization of supply chain operations.

## Methodology and technical skill set
  
The analysis involves data cleaning, transformation, and integration across multiple relational datasets. SQL is used for querying and aggregation, while Python (pandas) supports data manipulation and exploratory analysis. Data visualization techniques are applied to communicate insights effectively.

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
