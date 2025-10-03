# retail_customer_segmentation.ipynb
Customer segmentation project using RFM and K-Means.

Project Title:	Retail Customer Segmentation using RFM Analysis & K-Means Clustering.

Objective: The main goal of this project was to take raw sales data and organize our customers into distinct, meaningful groups (segments). By knowing who our customers are and how they spend, we can design specific, budget-friendly marketing campaigns instead of sending the same generic email to everyone. This is all about making our marketing smarter and more effective.

How I Built It? (Methodology):

I used a common data science approach for this, combining a popular marketing model with machine learning:

// Data Cleanup: First, I focused on cleaning the retail transaction data. This involved removing incomplete records (like transactions with missing Customer IDs) and invalid entries (like negative quantities for returned items).

// RFM Feature Creation: I engineered three essential customer metrics:

// Recency: How recently a customer bought (in days).

// Frequency: How often a customer buys (total orders).

// Monetary: How much money a customer spent (total revenue).

// Data Prep for Clustering: Since RFM data is often heavily skewed, I applied a logarithmic transformation to normalize the values. Then, I used Standard Scaling to ensure R, F, and M were all weighted equally for the clustering process.

// K-Means Clustering: I used the Elbow Method to determine that K=4 was the ideal number of segments. The K-Means algorithm then sorted all 4,338 unique customers into these four distinct groups.

// Segment Profiling: Finally, I analyzed the average RFM values for each group to define their characteristics and assign clear names.



[RetailProject.pdf](https://github.com/user-attachments/files/22677401/RetailProject.pdf)
