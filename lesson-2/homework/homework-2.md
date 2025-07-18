1. List three data sources Power BI can connect to.

Answer:

- Excel
- SQL Server
- Web

1. What is the first step to import data into Power BI Desktop?

Answer:

Click on Get Data and choose your data source.

1. How do you refresh imported data in Power BI?

Answer: Click Refresh in the toolbar, it reloads updated data from source.

1. What file formats can Power BI Import directly? (Name two)

Answer: csv and excel

1. What does the “Navigator” window show after selecting a data source? 

Answer: It shows a preview of tables or sheets you can load. 

1. Import Sales_Data.csv and load only the “Product” and “Price” columns.

Answer: Click Get Data then choose csv then check only product and price columns then click load.

1. How would you change OrderDate to a date format during import? 

Answer: Click Transform Data then select OrderDate column then use Data Type then date.

1. What is the difference between Load and Transform Data in the import dialog? 

Answer: 

- Loads: brings data into Power BI as-is
- Transform Data: opens Power Query to clean or edit data first.

1. Why might you see an error when connecting to a SQL database? (Name one reason)

Answer: Wrong server name or no permission to access the database. 

1. How do you replace a data source after importing it? 

Answer: Go to Transform data then data source settings then click change source. 

1. Write the M-code to import only rows where Quantity > 1. 

= Table.selectRows(Source, each [Quantity] > 1)

1. How would you chnage the data source if Sales_Data.csv changed?

Answer: Got to Transform data, data source settings, browse to the new file. 

1. Troubleshoots: Your CSv import fails due to a mixed data type error - how do you fix it? 

Answer: Go to Power Query and set the correct data type for each column manually. 

1. Connect to a live SQL database with parameters (e.g. filter by year)

Answer: Use get data, sql server, enter a parameter in the query like where year = 2023

1. How would you automate data imports using Power BI and Power Automate? 

Answer: Use power automate to trigger a refresh in Power BI based on schedule or events.
