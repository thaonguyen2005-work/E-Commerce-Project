# E-Commerce Project

## [Slide deck for The E-Commerce Case Study Project](https://docs.google.com/presentation/d/1hfMyddgi850zMUkGgIOyqTZ6-R6xMRsQTxrX0VR96RQ/edit#slide=id.g2e3f8de059b_2_133)

## About Olist Store Case Study
Olist is an e-commerce site of Brazil which provides a better platform to connect merchants and their product to the main marketplace of Brazil. It provides good services for the merchants to sell their products through the Olist Store and ship them directly to the customers using Olist logistics partners. Its business is based on interaction between consumer, Olist store and the seller. At first an order is made by the consumer on the olist site. This order is received by olist store, based on the information of the order (like product category, geolocation, mode of payment e.t.c) a notification is forwarded to the sellers. After that product is received from the seller and delivered to the consumer within the estimated delivery time. Once the customer receives the product, or if the estimated delivery date is due, the customer gets a satisfaction survey by email where he/she can give a note for the purchase experience and write down some comments. 

The data-set has information of 100k orders from 2016 to 2018 made at multiple marketplaces in Brazil. Its features allow viewing an order from multiple dimensions: from order status, price, payment and freight performance to customer location, product attributes and finally reviews written by customers. A Geo-location data-set that relates Brazilian zip codes to lat/long coordinates has also been released.

The objective of Olist this year is to grow total sales revenue (Olist has no control over the prices and shipping charges set by its partners).

**Dataset Model View**:

![Image](https://github.com/user-attachments/assets/f1942f14-71fc-4d4a-aac0-30407ab28f0b)

## 1. Analysis Approach/ Framework:
Objective: Increase Olist's total sales revenue by 10% (Olist has no control over the prices and shipping charges set by its partners)

**Analyze**:
**Sales Revenue ($) = # of Units Sold x Avg.Selling Price**

![Image](https://github.com/user-attachments/assets/bc4f2993-04a6-4399-8643-4a48e0ec0fdb)

## 2. Opportunity 1: More Customers (New Customers + Retaining Existing Customers)
**2.1 Increasing New Customers:**

**Situation:** 

The number of new customers grew strongly and reached its peak in December 2017, and then remained stable.

![Image](https://github.com/user-attachments/assets/a51106b2-b944-4500-bb7d-18cc331647c8)

**Insights:**

From January 2017 to December 2017, the number of new customers grew steadily, with a sharp spike in November 2017 (possibly due to Black Friday).

From January 2018 to August 2018, the number of new customers slightly decreased but remained stable at around 6,000 to 7,000 customers.

**Recommendation:**

Olist needs to implement additional marketing strategies to attract more new customers in order to achieve a 10% revenue growth in the next year.

**Analyze top cities with the highest performance and top best-selling products**


Strengthen marketing and promotional strategies in Sao Paulo (the area with the highest demand) for bath table and health beauty products to attract new customers.

![Image](https://github.com/user-attachments/assets/1424d139-a801-4429-b4e9-b4f4c6e7d33f)

![Image](https://github.com/user-attachments/assets/eefcadac-dc19-4633-8690-2a2b52b18c7c)

**Insights:**

Sao Paulo is the city with the highest concentration of Olist customers. The product lines that are most in demand in this area are bed bath tables and health beauty products.

**Recommendation:**

Since Sao Paulo is the area with the highest concentration of customers and strong demand for bed bath tables, it is important to leverage the current momentum by developing a marketing/promotion strategy targeting Sao Paulo with bath table and health beauty products to attract more new customers.

**2.2: Retaining existing customers:**

**Situation:**

Only about 0.4% of customers want to return to make a purchase after their first purchase. 

**Customer Retention Rate Over Time**

![Image](https://github.com/user-attachments/assets/7c7ca1fe-6f4f-41a7-8b26-c2d41751fe16)

Olist is not doing well in retaining customers and needs to take measures to improve the customer experience, including:

- Dispatch time & Delivery time
- Payment process

**Lead Time Performance:**

![Image](https://github.com/user-attachments/assets/c71cb1de-a765-4e60-b7b0-5709fbf0a8f9)

![Image](https://github.com/user-attachments/assets/0f63a90a-830d-4800-ab98-6ece98eeed3a)

**Insights:**
From 2016 to 2018, Olist made improvements in total time (dispatch time & delivery time), with a relatively low rate of late deliveries compared to expectations. However, the average delivery time remains as long as 10 days per order, falling short of customer expectations for speed.

**Recommendation:**

To enhance customer satisfaction, Olist needs to further reduce order processing time by:

- Optimizing the order preparation process

- Improving delivery efficiency

**Analyze the reasons for the long order dispatch times in MA, RN, and MS, and issue warnings to high-revenue merchants with a high rate of late orders to reduce order dispatch time.**

![Image](https://github.com/user-attachments/assets/de6ec6ff-7994-44bd-aac7-83634fd36214)

**Top 5 Sellers with Highest Rate Late and Orders**

![Image](https://github.com/user-attachments/assets/1b66ebe8-218d-4f0f-b621-0a8d5d11307c)

**Insights:**

The three states with long order dispatch times are MA, RN, and MS(because some orders take 10-20 days to prepare).

Some merchants have good revenue and order volume but have 30-60% of their orders with dispatch times longer than expected.

**Recommendation:**
In some states with order dispatch times longer than the average, particularly MA, RN, and MS, Olist should investigate the reasons behind this to implement measures to reduce dispatch times.

Additionally, for merchants with good revenue and order volumes but a high rate of delayed order preparation, Olist should issue warnings to help them improve customer satisfaction.

**Prioritize allocating shipper resources to areas with long delivery times (RR, AP, AM, AL, PA) and high late delivery rates (CR, PI, SE, MA, AL) to reduce delivery times and improve transportation efficiency.**

![Image](https://github.com/user-attachments/assets/932e7ce6-aa87-4bff-b1fd-fd32f18ff50a)

![Image](https://github.com/user-attachments/assets/d8209c70-cad4-4100-8bb9-52bca526dbe0)

**Insights:**

The average delivery time for Olist is 15 days, with five states having long delivery times: RR, AP, AM, AL, and PA.

Some states have a late delivery rate of up to 20.5% compared to the expected time: CR, PI, SE, MA, and AL.

**Recommendation:**

In regions with long delivery times and high late delivery rates, Olist needs to prioritize allocating shipper resources to reduce delivery times and enhance delivery efficiency.

**Payment Process**

Optimize the credit card payment method, the most preferred option, to ensure a smooth experience and minimize errors to below 0.5%

![Image](https://github.com/user-attachments/assets/afd348d8-d465-48c4-87e4-1091b9bc25c6)

**Payment Method Failure Rate**

![image](https://github.com/user-attachments/assets/3fbcd9c2-e123-4ff7-8de4-41538a5baca4)

**Insights:**

Most orders are paid for with credit cards, and the second most used payment method is boleto, which has a relatively low error rate, below 0.5%.

**Recommendation:**

Since Credit Card is the most preferred payment method, Olist should focus on optimizing this payment option to ensure customers can use it easily and with minimal errors.

## 3. Opportunity 2: Increase Order Frequency

**3.1: Situation About Orders Quantity Distribution:**

The number of orders per day mainly ranges from 50 to 200 orders. Improvements are needed to achieve a 10% revenue growth.

![Image](https://github.com/user-attachments/assets/5bb67d75-0952-4d8a-817e-88e7b8161df6)

**Insights:**

The number of orders per day ranges from 0 to 1,200 orders, but the focus is mainly on the range of 50 to 200 orders.

**Recommendation:**

Olist needs to encourage customers to make more purchases in order to achieve the goal of a 10% revenue growth in the coming year.

**Enhance email/push notification campaigns during peak hours (10 AM - 4 PM and 8 PM - 9 PM) and optimize the customer support team to drive more orders.**

**Heatmap of Order Frequencies by Hour:**

![Image](https://github.com/user-attachments/assets/b95f3a76-d271-4709-8d9e-a11e0652cab6)

**Insights:**

The order volume tends to be higher during two time slots: 10 AM - 4 PM (slightly decreasing at 12 PM) and 8 PM - 9 PM.

Saturdays and Sundays have fewer orders compared to other days.

**Recommendation:**

To take advantage of the time periods when customers tend to place the most orders, Olist should send emails/push notifications during those times to encourage users to make additional purchases.

Additionally, the customer support team should be optimized during peak hours.

**3.2: Segment customers using RFM:**

**Recency**: How recently did the customer place their last order?

**Frequency**: How often does the customer place orders?

**Monetary value**: How much does the customer spend on average?

![Image](https://github.com/user-attachments/assets/f606a91a-b5a6-47ad-ae53-f7b4f7c3c5ea)

**Insights and Recommendations:**

The "Promising" and "New Customers" segments make up over 50% of the customer base, highlighting opportunities to nurture and convert these groups into loyal customers. Retention efforts should focus on the "Cannot Lose Them" group with rewards and personalized engagement, while reactivation strategies can target "Hibernating" and "About to Sleep" customers. The small "Champions" segment can be leveraged as brand advocates, and churn risks in the "Lost" and "At Risk" segments need immediate attention to reduce losses.

## 4. Opportunity 3: Increase # items/Order

**Encourage customers to purchase more products per order by offering volume discounts and suggesting relevant product bundles.**

![Image](https://github.com/user-attachments/assets/6de029bc-3f23-41b2-9580-b111df23d273)

**Insights and Recommendations:**


As 91% of customers purchase fewer than 2 products with most users currently buying only 1 product per order, Olist should create incentives for customers to buy more items through offers and promotions to increase the number of items sold per order. For example, "Buy 3 products, get X$ off."

Additionally, product suggestions or bundles can be offered to encourage customers to purchase additional products once they have already chosen a specific item.

# Key Recommendation:

**1.Increase Customers (Increasing New Customers and Retaining Existing Customers):**

- Strengthen marketing and promotional strategies in Sao Paulo (the area with the highest demand) for bath table and health beauty products to attract new customers.
 
- Analyze the reasons for long order dispatch times in MA, RN, and MS, and issue warnings to high-revenue merchants with a high rate of late orders to reduce dispatch times.

- Prioritize allocating shipper resources to regions with long delivery times (RR, AP, AM, AL, PA) and high late delivery rates (CR, PI, SE, MA, AL) to reduce delivery times and improve transportation efficiency.
  
- Optimize the credit card payment method, the most preferred option, to ensure a smooth experience and minimize errors to below 0.5%.

**2. Increase Order Frequency:**

Enhance email/push notification campaigns during peak hours (10 AM - 4 PM and 8 PM - 9 PM) and optimize the customer support team to drive more orders.

**3. Increase # Item/Order:**

Encourage customers to purchase more products per order by offering volume discounts and suggesting relevant product bundles.




