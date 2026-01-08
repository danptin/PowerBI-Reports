# **Tailwind Traders Sales Report**

## **Project Overview**

Tailwind Traders is an international retailer for hardware such as plumbing, lighting, and gardening supplies, among other home improvement products. Tailwind Traders requested a report detailing the company's recent sales and profit data.

## **Resources**

- The Countries, Purchases, and Sales Data tables were imported into Power BI from Microsoft Excel files. Excel was used to clean and transform the Sales Data table.
- The Exchange Data table was added directly to the project using a Python script in Power BI.
- A DAX expression was written in Power BI to add the Calendar table.
- Power BI Desktop was utilized to further clean, transform, and load data. The data model was designed using Power BI.
- The final report was published to a new dashboard in Power BI Service.
## **Analysis & Results**

### **Transforming Sales Data in Microsoft Excel**
Excel formulas were used to calculate Gross Revenue, Total Tax, and Net Revenue for each product. These columns were added to the Sales Data table.

### **Configuring Data in Power BI**
The Microsoft Excel Sales Data, Purchases, and Countries tables were imported into Power BI. They were examined for duplicate, null, or otherwise unexpected values. Each column was checked or altered to ensure the correct data type designation. A currency exchange table was added to the file so that the sales figures could later be homogenized.

### **Designing the Data Model**
Table relationships were configured to develop a data model. Cardinality and cross filter direction were considered for each relationship to ensure accuracy. A Calendar table was generated using a DAX formula and then marked as a Date Table. Using the Exchange Data table, the Sales Data table was duplicated with all currency converted to US dollars and named Sales in USD.

![Dashboard Preview](https://github.com/danptin/PowerBI-Reports/blob/main/DataModel.PNG)

### **Calculating Aggregations**
DAX code was used to calculate aggregations for Yearly Profit Margin, Quarterly Profit, Year-to-Date Profit and Median Sales.

### **Developing a Sales Report**
Graphs, charts, and other visuals were generated according to Tailwind Trader specifications into a Sales Report, including an overview of the company's sales and profits.
### **Sales Overview Page**
![Dashboard Preview](https://github.com/danptin/PowerBI-Reports/blob/main/Sales.PNG)

### **Profit Overview Page**
![Dashboard Preview](https://github.com/danptin/PowerBI-Reports/blob/main/Profit.PNG)

 [Download PDF Report][(report.pdf)](https://github.com/danptin/PowerBI-Reports/blob/main/TailWind%20Traders%20Report.pdf)

## **Creating an Executive Dashboard**
The finalized report was published to Power BI Service. Visuals were pinned to an Executive Dashboard where they were designed to be user-friendly via the web as well as mobile devices.

## **Summary**
Raw sales data at Tailwind Traders was cleaned, transformed, and visualized so that company executives could make data-driven decisions for their future marketing budget. Based on the high median sales distribution in the UAE yet the country's relatively low annual profit margin and total count of loyalty points, executives decided to increase marketing and promotions in the UAE to encourage more of these larger sales as well as drive customer loyalty.

