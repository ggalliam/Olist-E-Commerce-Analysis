# Olist E-Commerce Analysis

<img width="363" height="228" alt="Screenshot 2026-04-23 at 9 02 08 PM" src="https://github.com/user-attachments/assets/1642f5a6-0674-40ea-b4a0-84ed38df1aa9" />


## Objective

Olist is a Brazilian e-commerce platform that connects businesses to customers across Brazil. It is a marketplace, where merchants can list their products and services and customers can browse and purchase them online. E-commerce landscape in Brazil can be observed through looking at a company like Olist to identify opportunities for growth and optimization.

In order to optimize growth, this analysis is looking closer into specific sales, customer profiles, and individual shop performance to improve revenue and customer satisfaction.

## Dataset

Olist E-commerce dataset contains over 100k+ rows of information from September of 2016 to October of 2018. During this time period 99,441 products were sold. The dataset is divided in 8 files: orders, payments, reviews, items, products, sellers, customers, geolocation.

<img width="983" height="584" alt="Screenshot 2026-04-24 at 10 26 15 PM" src="https://github.com/user-attachments/assets/dcee3534-85d5-47fc-b36a-022958951e7f" />


## Business Problem 

Some key quations will navigate further optimization strategies for the company. 

- Which product is the all time bestseller? Which category of products is bringing in the most profit?
- What is thw overall revenue of Olist? What can be implemented in the future to icrease sales? 
- How do customers influnce the revenue of the company? Which factors are essential and determine future profits? 

This project evaluates how revenue is distributed across sellers and product categories. It identifies top-performing products and examines marketplace concentration. These insights inform strategies to improve platform resilience and seller diversification. Individualistic factors generate different revenues, those findings will immensely support targeted optimization of supply chain operations.

## Methodology 
  
The analysis involves data cleaning, transformation, and integration across multiple relational datasets. 
SQL is used for querying and aggregation, while Python (pandas) supports data manipulation and exploratory analysis. 
Data visualization techniques are applied to communicate insights effectively.

## Insights 

**Selling Permornace**
------------------------

- In 2016, the top-selling product by category was furniture (decor). 
- In 2017 it was bed_bath_tables. 
- Between 2016 and 2018, computer accessories were selling the most growth rate withing a two year span. 

<img width="787" height="483" alt="Screenshot 2026-04-24 at 10 28 48 PM" src="https://github.com/user-attachments/assets/a9a1586b-ad7f-4d27-bad0-54d37ba2f42c" />



However, it is important to look closer into the average order value (AOV) for a more detailed picture. 
- Computers category has the biggest average order value. Therefore, computers are the most expensive items offered on the website. 
- Even though bed_bath_table category has the biggest amount of orders, it did not show up for the AOV ratio.
- By marketing high revenue categories better, overall revenue will increase. This means implementation of targeted sales, discounts and offers.

  
<img width="999" height="573" alt="Screenshot 2026-04-24 at 10 28 18 PM" src="https://github.com/user-attachments/assets/f34d69af-0109-470c-8735-0025109f8a4a" />



The highest profit margin of 79% is home_comfort_2. The lowest is small home_appliances_2. Since the margin between the categories is pretty big, about 10%, then Olist can implement strategies for low-profit margin products, like home appliances like promotions and discounts. 


<img width="1009" height="574" alt="Screenshot 2026-04-24 at 10 27 53 PM" src="https://github.com/user-attachments/assets/4cd792ac-3056-440a-b86a-68e499902c3a" />


**Revenue**
---------------

In order to undertand how revenue is effected, it is crucial to look at the revenue data first. Overall, timeline is reperesenting a consistent growth thoughout the years besides September of 2018 but it could be explained by the end of transaction period of the dataset. However, it is still visisble a clear trend of revenue growth. 


<img width="1194" height="581" alt="Screenshot 2026-04-24 at 10 27 14 PM" src="https://github.com/user-attachments/assets/3dd6ddea-3df8-49fc-be1b-41a7b1ec28ed" />


**Customer Profile**
---------------------

Multiple interesting observations are seen after looking at customer reviews and how they are correlated to the frequency of purchases. Highly rates items are ordered the most, this is representing a great performance of sales. 
<img width="785" height="476" alt="Screenshot 2026-04-24 at 10 29 49 PM" src="https://github.com/user-attachments/assets/7ffe0a25-600b-4687-8c7e-c11f66de0b64" />


Looking further, highly rated products have a lower average order value compared to the low-rated products. This may mean that the most expensive products are actually low-rated items. Customers care about more quality excellent rating products with lower cost. 


Moreover, in order to implenment new strategies, it is useful to undertand geographical locations where most of the customers reside. In Brazil, the biggest number of clients, almost 50% are located in Sao Paolo. Other top locations include Rio de Janeiro and Minas Gerais. Top locations can be prioritized through free or discounted shipping deals, returns and other promotions. 

<img width="512" height="277" alt="Screenshot 2026-04-24 at 10 30 29 PM" src="https://github.com/user-attachments/assets/ce6102ae-6d59-4ced-aaad-f53118b709b0" />



## Recommendations 

> Looking at more data, only 6% of the customers are making repeated purchases. Even thogh data is showing progress and consistent rise in numbers, it is importnat to notice small details and that may cause huge differences in the long run. Marketing strategies can include a variety of options.

> To sustain already existing customers and create a broader client base, it would be useful to create optional subscription plans, email newsletter options and other deals to keep customers coming back to the website. By offering referral links and discounts would also open up a new word of mouth advertising tool. 

> Since the most sold items are not the biggest revenue providers, other categories with bigger price tags should be promoted. By doing so, more revenue will be generated from lower amount of sales faster.

> Overall, customer experience should be more personalized. By offering shipping and return deals in popular locations, there is more incentive that the platform will become accessible and popular, growing more popularity across more locations across the country and worldwide later on. 
