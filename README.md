# ClassicCarModelsDashboard
Dashboard on Classic Cars in Power BI 


# Tools used for this project was:

- Excel
- MySQL
- Power BI


# Overview of project:

Firstly I downloaded the dataset from a classic car model site from the web as a .csv file.

Opened the CSV file in Microsoft Excel then saved it as an .xlsx file because I will use the dataset to create more sheets with excel.

Made sure to visually clean the dataset using find and replace for blanks or typo errors. 

The sheets that I created were data based on:

- Product Overview
- Sales Data
- Country Overview
- Products Purchased Together
- Credit Limit Grouped
- Purchased Value Change
- Office Sales

I created a schema within mySQL, noting that this will be relational database. 

Next was retrieving that dataset from excel and using mySQL to combine, filer and sort the data, from there using SQL Commands like:

- Select statement
- From
- Order by
- Joins
- On
- As

I made a view in mySQL using the dataset. 

Afterwards I copied the desired table of data I wanted, in need to connect mySQL database and Power BI’s database.

Inside Power BI I copied my connection string from mySQL classic models server port and pasted it into Power BI. 

The connection was successful. 

 

Now the view from mySQL is within Power BI, I edited my canvas to start adding components for data visualization. 

I wanted the dashboard to show the data on sales and net profit from Customer Name, Product Line and Customer Country. 
Including a sales overview, average unique orders and count of unique sales while using dynamic pages, buttons and animations within the dashboard.

