# E-Commerce Sales -Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/d75d843d-2f5a-49da-a37b-f0328730f236/40e8f2180ee5813b0af1?experience=power-bi&clientSideAuth=0

## Problem Statement

This dashboard provides a comprehensive analysis of e-commerce sales data. It helps businesses understand sales trends across different product categories, markets, and shipping methods. Key insights include regional sales performance, preferred shipping modes, and the contribution of various product categories to overall revenue. The dashboard is designed to empower businesses with actionable insights, enabling them to optimize operations, reduce shipping costs, and target high-performing markets.

The dashboard reveals that sales are concentrated in a few key markets, and shipping preferences are largely focused on standard and second-class services. By identifying patterns in customer preferences and operational performance, businesses can refine their strategies to improve profitability and customer satisfaction.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Set the column profiling to be based on the entire dataset to ensure accurate analysis.
- Step 4 : Analyzed the dataset for any missing or null values. Specifically, columns like "Sales," "Profit," and "Shipping Cost" were reviewed.
- Step 5 : Since missing values were minimal (less than 1%), they were excluded from the analysis.
- Step 6 : Applied a theme in the report view to ensure a clean, professional visual presentation.
- Step 7 : Added visuals, including bar charts and card visuals, to represent key metrics like total sales, profit margins, and sales by product category.
- Step 8 : Slicers were added for categories such as "Product Category", "Market" and "Ship Mode" to allow users to interact with and filter the data. 
- Step 9 : Two card visuals were added to show total sales and total profit across all regions, filtering out null values where necessary.
- Step 10 : A bar chart was added to show sales by category (e.g., "Technology," "Furniture," "Office Supplies"), and another to display sales by market, with regions such as "APAC," "EU," "US," and "LATAM" being represented.
- Step 11 : The "Sales by Ship Mode" visual was used to show the breakdown of sales by shipping class (e.g., "Standard Class," "First Class," "Second Class," "Same Day")​(E-Commerce Sales Report). 
- Step 12 : Created calculated columns for segmentation by customer demographics (e.g., age group).
- Step 13 : Calculated measures to derive key performance indicators (KPIs) such as total sales, profit percentage, and sales percentage by category.
- Step 14 : Published the report to Power BI Service for real-time collaboration and sharing.

        


# Snapshots


# Snapshot of Total Sales by Country: 
Donut chart highlighting the sales performance in different countries.


![SalesByCountry](https://github.com/user-attachments/assets/7010e2df-f693-49dd-8ec7-ff442a8fda38)


# Snapshot of Total Sales by State:
Tree map chart highlighting the sales performance in different states.


![SalesByState](https://github.com/user-attachments/assets/b9cd6df8-057a-4c05-affb-b9c04ad75cb4)


# Snapshot of Total Sales by Category:
Stacked Column chart visualizing sales figures by category.


![SalesByCategory](https://github.com/user-attachments/assets/22a9b74e-58b4-4bd8-a3bf-1724c0a6913b)


# Snapshot of Total Sales by Market:
Pie chart showcasing sales distribution by market.


![SalesByMarket](https://github.com/user-attachments/assets/4826d6f1-a9f2-47eb-953f-d41b2398bba4)


# Snapshot of Total Sales by Ship Mode:
Funnel chart visual showing how sales break down by different shipping modes.


![SalesByShipmode](https://github.com/user-attachments/assets/bca7af8f-5f9a-4ee2-9c57-68a0ab11981f)


 # Report Snapshot (Power BI APP)

 
![PowerBI Dasboard](https://github.com/user-attachments/assets/590275e1-b8fe-4ff3-bd97-fd99d1143b68)



# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Sales by Category

   Technology: $4.7M

   Furniture: $4.1M

   Office Supplies: $3.8M

      
### [2] Sales by Market:

    a) APAC: $3.59M (28.36%)
    b) EU: $2.94M (23.24%)
    c) US: $2.3M (18.17%)
    d) LATAM: $2.16M (17.12%)
    e) EMEA: $0.81M (6.38%)
    f) Africa: $0.78M (6.2%)
 
  
  ### [3] Sales by Ship Mode:
  ### Class
  
      a) Standard Class: $7.58M
      b) Second Class: $2.57M
      c) First Class: $1.83M
      d) Same Day: $0.67M


  ### [4] Sales by Country:
 
    1.1) United States: $2.3M (29.01%)
 
    1.2) Australia: $0.93M (11.69%)
 
    1.3) France: $0.86M (10.85%)
 
    1.4) China: $0.7M (8.85%)

    1.5) Germany: $0.63M (7.94%)

    1.6) Mexico: $0.62M (7.86%)
 
 
  ### [5] Shipping Cost and Quantity:
 
    2.1)  Total Sales: $12.64M
 
    2.2)  Total Profit: $1.47M
 
    2.3)  Total Quantity Sold: 178K units
 
    2.4)  Total Shipping Cost: $1.35M
         
        
  ### [6] Customer and Location Information:

    3.1) Total Countries: 147

    3.2) Total States: 1,094

    3.3) Total Cities: 3,636
