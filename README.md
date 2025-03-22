# Retail_Revenue_Analysis  
## analysis Report  
### ADD PHOTO HERE  
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

#### Top 10 Countries By Revenue - bar chart 📊
![countries bar chart](https://github.com/user-attachments/assets/ebf68d99-4920-4da0-8ea9-ce721e012bab)

#### Top 10 Customers By Revenue - Column chart - 📊
![Screenshot 2025-03-21 141421](https://github.com/user-attachments/assets/473e8aa8-8882-4047-a152-ee2365de2509)

#### All Countries And Regions With High Product Demand - Map chart 🗺️
![Screenshot 2025-03-21 141508](https://github.com/user-attachments/assets/7856f91b-516b-4e87-bc17-ec812a94286a)


