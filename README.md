# Sales-Analysis-Dashboard

# Introduction

Sales performance analysis involves evaluating various metrics and key performance indicators (KPIs) to understand how well sales activities are performing. understanding sales performance is key to strategic decision-making and business growth. In this project I used Microsoft-BI to create a dashboard for a retail store to see how it’s performing and how healthy its finances are. Using basic data analysis, I find useful insights about sales trends, strengths, and areas that need improvement.

# 

# About the Analysis
My goal is to assess sales performance and understand the financial health of the business. These are some of the problems we need to solve for strategic decision making and business growth: 

**Regional Disparities**: Identifying and addressing variations in sales performance across different regions in the U.S.

**Profitability Metrics**: Gaining clarity on profit percentages and understanding the factors influencing profitability.

**Segmented Insights**: Uncovering patterns in sales and quantity sold by segments to optimize marketing and product strategies.
 
# About Dataset
A retail transaction dataset over six years (2018-2023).
The dataset was in different format
1.	**Sales Data** – Divided into two parts
 
• Sales before 1st Jan 2023 – Kept as a CSV data dump

• Sales after 1st Jan 2023 – Kept in an SQL database 

3. 	**Customer Data** – Divided into four files region wise kept in a single folder
4. 	**Product Data** – Saved as an XML file

# Data Exploration & cleaning
In this project I performed some data transformation and data cleaning using power query in powerBI to made our data ready for analysis. 

This is diagram showing the model view after transformation.


![image](https://github.com/user-attachments/assets/a888de74-9b23-4213-b205-962a86992710)

 
# Dashboard component 
For this analysis, I explored different charts to ensure they are easy for users to understand.I also incorporated filters for year and month to allow for more detailed insights. 

**1.	Filters for Precision**

Customized my analysis by selecting the specific year(s) of interest.

**2.	Vital Key Performance Indicators (KPIs)**

**Profit margin (Percentage)**: Understand the profit margins with a clear visualization of profit percentage.

**Total Customers**: Track the overall orders to know the total customer.

**Total Sales:** Quantify the total revenue generated through sales.

**Total Profit:** Gained insights into the overall profitability of the Retail store operations.


![image](https://github.com/user-attachments/assets/2a775293-5696-4125-9dbb-39123dd8cc75)


**3. Top customers by sales**


**Table**: Visualized the top 10 customers by sales

![image](https://github.com/user-attachments/assets/bd883bc5-c6e2-4b85-92cb-3d9e94834e94)


**4.	Category-wise Sales & Profit**

**Bar Chart:**: Visualized the sales and profit breakdown across different product categories.

![image](https://github.com/user-attachments/assets/a8f66c8a-d0ed-44ca-9be5-062e60ff6a52)
 
**5. Sales Distribution by Shipment Mode & Order type**

**Donut chart**: Visualized the total sales distribution by ship mode and also the total sale by order type

![image](https://github.com/user-attachments/assets/40c0513e-5682-4a42-88bb-c88091ca8e25)


![image](https://github.com/user-attachments/assets/27fa05e2-761d-47a8-951d-c27168503681)


**6.	Regional & Monthly Sales Dynamics**

**Top 10 Sales by region**: Identified the top-performing region in terms of sales volumes

![image](https://github.com/user-attachments/assets/3b4d1282-706a-40db-9d05-73a184d802d0)


**Profit by State, Category & Sub-category:**: identified the top performing state, category & sub-category in terms of profit volume

![image](https://github.com/user-attachments/assets/adba5b29-09d4-4505-82e5-579692bc2d67)

**7.	Net sale year to year (2019 – 2023)**

![image](https://github.com/user-attachments/assets/6d2ad076-6071-4c8b-a2bd-b91da5d5699e)

 # Findings and Insight
 
1.	The total sales is 2.30 million
	
2.	The total quantity sold is 38 thousand
	
3.	Total Profit is 286.74 thousand
	
4.	Total customers is 793
	
5.	Customers bought the three categories of products but technology brought in the most sales.

6.	Office Supplies Lead in Quantity Sold Among Product Categories

7.	Phone generated the highest net sales among all sub-categories of products.

8.	Office supplies are the most frequently purchased product category, followed by technology and furniture.
	
9.	Sales showed a marked upward trend from 2019 to 2022, indicating a steady year-over-year increase. However, this upward trajectory underwent a shift in 2023, as sales experienced a notable decline.
	
10.	Sean Miller and Tamara Chand are the top 5 customer, purchased the highest quantity of products.

11.	Our analysis indicates that offline orders constitute the highest volume of total sales compared to other order types.
	
12.	There is a strong positive correlation between profit and net sales. 2019 to 2022 exhibits a steady growth trend in both sales and profit, with 2022 being the most successful year. However, 2023 shows a significant decline in both metrics.
    
# Recommendations

1.	Given that furniture accounts for over 37% of total sales, it is crucial to invest in targeted marketing campaigns to further boost its performance.
  
2.	The notable decline in sales and profit in 2023 warrants a thorough investigation. Identify the underlying causes, such as market conditions, competitive actions, or internal factors, and develop strategies to mitigate these issues. This may include diversifying product offerings, improving customer service, or enhancing sales channels.
   
3.	With the West region leading in sales, analyze the strategies that have led to its success and apply similar approaches to other regions. Tailor marketing and sales efforts to the unique characteristics and preferences of each region to maximize sales potential.

5.  understand their needs and preferences better. Engage with customers through surveys, social media, and other platforms to build strong relationships and foster loyalty.

6.	Stay agile and adaptable to market changes by continuously innovating. Keep an eye on industry trends, technological advancements, and competitor actions to remain competitive and relevant in the market.
7.	

**Click https://app.powerbi.com/groups/me/reports/dbed92c5-5752-49e6-b925-fb3d8e6b657c/3c972c1ce4a230180020?ctid=7ea7688f-ae82-4587-ab44-ee56ade38051&experience=power-bi to see the dashboard.**



