# SmartDelivery_ProfitTrack

## Project Objective 
Visualizes the impact of delivery status (In-Transit, Delivered, Returned, Cancelled) on overall profitability. Supports payment mode analysis and monthly performance tracking.

## Question (KPIs)
-What is the total profit generated according to the dashboard, and how does it relate to the total sales?

-Which region has contributed the highest percentage to total sales, and what is that percentage?

-How is the distribution of sales between online and offline channels represented, and what insight does it provide?

-Which delivery status has the highest sales value, and what might this imply about the delivery process?

-Among the payment modes (Card, COD, UPI, Wallet), which one accounts for the largest share of sales?

-Which product sub-category appears to have the highest individual sales performance, and what could be influencing this trend?

-Looking at the monthly trend, in which month was the sales performance the highest, and what was its percentage share?

## Dataset Used

<a href="https://github.com/Rohit-Ahirwar/SmartDelivery_ProfitTrack/blob/main/Sales%20DeshBoard%20Data.xlsx">Seles DataSet</a>

<a href="https://github.com/Rohit-Ahirwar/SmartDelivery_ProfitTrack/blob/main/Sales%20Deshboard.png"></a>

 ## Sales Dashboard Process
Step 1: Data Collection

•	Gather all sales-related data:

         •	Date, Product, Region, City
         •	Sales Amount, Profit, Delivery Status
         •	Sales Channel, Payment Mode
         
Step 2: Data Cleaning

•	Remove duplicates and missing values

•	Format dates, numbers, and text fields

•	Create new fields if needed:

         •	Month, Year (from Date)
         •	Profit Percentage
         •	Net Sales
         
Step 3: Data Modeling

•	Build relationships between tables:

         •	Sales ↔ Product
         •	Sales ↔ Region
         •	Sales ↔ Date
Step 4: Visual Creation

•	Add visual elements:
      
      •	Card: Total Sales, Total Profit
      •	Bar Chart: Monthly Sales
      •	Pie Chart: Payment Mode, Sales Channel 
      •	Line Chart: Trend Over Time
      •	Treemap: Delivery Status
      •	Bar Chart: Product Sub-category wise sales
   
Step 5: Add Filters (Slicers)

•	Allow user to filter by:
       
       •	Date
       •	Region
       •	City
       •	Product Sub-Category
       •	Payment Mode
       •	Delivery Status
       •	Sales Channel

Step 6: Formatting

   •	Apply color themes and proper labels
     
   •	Use legends and data labels
     
   •	Arrange layout for clarity
     
   •	Add chart titles and KPI indicators

Step 7: Final Review & Publish

   •	Test interactions between visuals

   •	Validate data accuracy

   •	Publish the dashboard or export as needed

## Conclusion

The Sales Dashboard provides a comprehensive and interactive view of overall business performance. By integrating key metrics such as total sales, profit, regional contributions, product sub-categories, payment modes, and delivery statuses, this dashboard enables data-driven decision-making. Visual elements like bar charts, pie charts, treemaps, and cards simplify complex data, allowing users to quickly identify trends, outliers, and areas of improvement.

With real-time filtering and clear visual insights, the dashboard serves as a powerful tool for sales analysis, helping stakeholders monitor performance, optimize strategies, and drive business growth effectively.

