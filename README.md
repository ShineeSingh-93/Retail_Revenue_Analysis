# Retail_Revenue_Analysis  
## analysis Report  
![retail_analysis_report](https://github.com/user-attachments/assets/57967779-48d6-4961-8649-a17dee3599d9)
  
### Introduction  
Tata Group given a task to create visuals around four of the questions that they have requested.These Questions are:
1. The retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.
2. The top 10 countries which are generating the highest revenue. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.
3. The top 10 customers by revenue. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers.
4. All countries and see which regions have the greatest demand for their products.
  
### Skills Used

The following skills were utilized for analysis:

- **📉 Power BI**
- **🧮 Measures**
- **❎ Power Query**
- **👨‍💼 PowerPoint**

### Online Retail Dataset

The dataset used for this project contains real-world Retail information from 2010-2011. The dataset is available via my resource folder, which provides a foundation for analyzing data using Power BI. It includes detailed information on:

- **Customer ID**
- **Country**
- **Quantity**
- **UnitPrice**
- **Invoice No**
- **InvoiceDate**
- **Description**

### Buiding Report

major four steps had performed. They are as follows:
1. Data Extraction
2. data cleaning
3. Visualization
4. Insights.

#### Data Exctraction and Data Cleaning
![power query editor](https://github.com/user-attachments/assets/c0b2cccd-6ef6-4fe4-8f9d-fa7cd511860e)

Data Extraction : 
To begin, I extracted online Retail data Excel files, I imported these datasets into Power BI using the Get Data feature, selecting the Excel connector. I then loaded the data into Power Query for preprocessing.

Data Cleaning : 
In Power Query, I addressed key data quality issues:  
▶️ Create a check that the quantity should not be below 1 unit.  
▶️ Create a check that the Unit price should not be below $0  
▶️ Remove Empty values from the CustomerId field.  
After cleaning, I loaded the transformed data into Power BI for visualization.  

#### Monthly Revenue Trends - line chart 📈
![revenue line chart](https://github.com/user-attachments/assets/92d937c3-b42e-4dde-b4de-a5576940a120)  
- 🛠️ **PowerBI Features:** Utilized line chart feature to veiw the monthly revenue trend for 2011.
- 📉 **Data Organization:** Sorted data monthwise and created revenue measures.
- 🧮 **Measures created:** revenue = quantity * UnitPrice
- 💡 **Insights Gained:** Peak revenue in November due to seasonal demand(holiday shopping) and Sharp drop in December due to post-holiday drop.

#### Top 10 Countries By Revenue - bar chart 📊
![countries bar chart](https://github.com/user-attachments/assets/ebf68d99-4920-4da0-8ea9-ce721e012bab)  
- 🛠️ **PowerBI Features:** Utilized bar chart feature to veiw the top 10 countries with the highest revenue and alongside thier quantity.
- 📉 **Data Organization:** filter country based on revenue using filter pane(topN) in powerBI.
- 💡 **Insights Gained:** The insight got is that Nethrelands is the top performer and countries EIRE, germony, france are the strong performer who contributed in generating high revenue.

#### Top 10 Customers By Revenue - Column chart - 📊
![Screenshot 2025-03-21 141421](https://github.com/user-attachments/assets/473e8aa8-8882-4047-a152-ee2365de2509)  
- 🛠️ **PowerBI Features:** Utilized column chart feature to veiw the top customers who are generating highest revenue.
- 📉 **Data Organization:** Sorted data in descreasing order by sum of revenue.
- 💡 **Insights Gained:** The Insight got it that the customer with id:14646 is generating the greatest revenue.So this customer is the valuable for company.

#### All Countries And Regions With High Product Demand - Map chart 🗺️
![Screenshot 2025-03-21 141508](https://github.com/user-attachments/assets/7856f91b-516b-4e87-bc17-ec812a94286a)  
- 🛠️ **PowerBI Features:** Utilized Map chart feature to veiw all countries and the regions which has high demands for products.
- 💡 **Insights Gained:** The Insight got is that the whcih all countries need to be focus to increase the future revenue.

## Conclusion
I worked on this project to help a retail client review their revenue data to prepare for the future. I created data visuals, practiced using PowerBI to represent information,power query to cleanup the data, and built my presentation skills in a real-world context and gain experience of bussiness insights. Doing this program confirmed that I really enjoy working on strategic problems for clients and I'm excited to apply these skills on a real-world scenerio. 
