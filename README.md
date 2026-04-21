# Olist E-Commerce-Analysis

## Objective
Analyze sales, customer behavior, and delivery performance to improve revenue and customer satisfaction.

## Dataset
Olist E-commerce dataset (100k+ rows) Filtered for electronics categories (Sep 2016 – Oct 2018).

## Business Problem and Methodology

- **Identifying drivers of customer satisfaction**  
The analysis aims to isolate the key factors influencing customer review scores and overall experience. Variables such as delivery timeliness, pricing, and service quality are evaluated. The goal is to prioritize operational improvements that enhance customer satisfaction.

- **Assessing revenue distribution and seller performance**  
This project evaluates how revenue is distributed across sellers and product categories. It identifies top-performing sellers and examines marketplace concentration. These insights inform strategies to improve platform resilience and seller diversification.

- **Evaluating logistics performance across regions**  
The study analyzes regional variations in delivery times and shipping costs. It highlights inefficiencies and disparities in logistics performance across geographic areas. The findings support targeted optimization of supply chain operations.

- **Methodology and technical skill set**  
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
