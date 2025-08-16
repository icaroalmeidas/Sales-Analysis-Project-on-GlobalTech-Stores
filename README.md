# Sales-Analysis-Project-on-GlobalTech-Stores
## Data-driven analysis of GlobalTech Stores' sales (2011-2014) using Excel. Aims to provide actionable insights for performance &amp; marketing.
Let's find out how to get this result.

<img width="1145" height="689" alt="image" src="https://github.com/user-attachments/assets/41aa6ca2-d568-492c-ad69-9f3d986f7130" />


The first goal it is to make a analysis on the dataset to identify columns, types of data and data problems.

We have 29 columns on the dataset. Obviosly that we don't need all of them the get some conclusions.
These are the columns:

<img width="560" height="1000" alt="ai-image-1755353682558" src="https://github.com/user-attachments/assets/062c1fd9-1009-43e0-9350-056d277fef16" />

There are 51291 rows on the DataSet and 1.238.840 cells.

Let's look for blanks datas on the dataset, using a tool on Excel called "Go to Special". Take a look on the image.
<img width="1903" height="522" alt="image" src="https://github.com/user-attachments/assets/0396095e-3762-4082-90c6-726484b22110" />

<img width="1916" height="625" alt="image" src="https://github.com/user-attachments/assets/5794edb0-d0b5-44a3-a776-2a6857fcdc53" />


We Identified some blank cells on the columns Postal code, that's not a problem to our analisys, so live them alone.
But, we have some blank cells on the column manager, that's a problem to us.
<img width="1906" height="826" alt="image" src="https://github.com/user-attachments/assets/478601f2-5733-427c-945e-3f4048620e65" />
So, to show this instead of let the cells empty we can fill then with "No Manager". This way we can notife the data engennir to correct the problem. 

I don't figue out any other ptoblem on the data set. But, we need to create some columns to get all the information to our DashBoard.

Creating Month and year columns:

<img width="340" height="111" alt="image" src="https://github.com/user-attachments/assets/f3859e7f-3b43-47f8-9792-bafbea31f39a" /> <img width="410" height="120" alt="image" src="https://github.com/user-attachments/assets/bbdc94f1-ee60-4db0-b878-8fb2504cc832" />

Result:
With these 2 columns it is going to be posible to us look up on the information by Year or month.
<img width="345" height="297" alt="image" src="https://github.com/user-attachments/assets/1bd86ba2-76b0-44c6-a127-feda1a794711" />

We have these 3 columns that we can use to get some main data to our analyse.

<img width="413" height="225" alt="image" src="https://github.com/user-attachments/assets/95e3f6be-d7ba-4161-95c8-a5c6faa1fa6a" />

Let's Create two Columns: Total Sales and Profit.
Total Sales = Sales * Quantity
Profit = Total Sales - Discount - Shipping Cost

<img width="170" height="225" alt="image" src="https://github.com/user-attachments/assets/ddbe5ce5-847e-4fc5-bb66-a67f8a477e93" />

That's it. Let's work on the DashBoard.

Lets use a Pivot Table in Excel is a powerful tool that allows you to summarize and analyze large datasets. It extracts significant information from a table and organizes it, letting you see patterns and trends that might not be obvious otherwise.
We can use it for:

Summarizing Sales Data: Calculate total sales by region, product category, or sales representative. Find the top-selling products. Analyze sales trends over time (e.g., by month or year).
Analyzing Customer Data: Identify your most valuable customer segments. See which products are most popular with different customer groups. Analyze customer demographics.
Financial Reporting: Create income statements or balance sheets. Analyze expenses by category.
Inventory Management: Track inventory levels by product. Identify slow-moving inventory.
General Data Exploration: Quickly get counts, sums, averages, or other calculations for different groups within your data. Identify outliers or anomalies in your data.
Creating Reports and Dashboards: Pivot Tables are a great foundation for building interactive reports and dashboards that can be easily updated as your data changes.

On our project we will use these tool not only to summarize but, to build the DashBoard. Let's see it!

I created these 4 simple cards using Pivot Tables.
<img width="1911" height="391" alt="image" src="https://github.com/user-attachments/assets/b127c623-63b7-4c86-8244-b50989d61be3" />

We use a Text Box with a reference to the sheet Panel = PANEL!A2
<img width="1131" height="174" alt="image" src="https://github.com/user-attachments/assets/53505e50-cb59-46c2-8684-50fbf84523a8" />


The final view.
<img width="1142" height="120" alt="image" src="https://github.com/user-attachments/assets/717c96bc-8171-43c3-a8bb-387d8cd15124" />

To build the Graphics we are going to do 3 Pivot Tables.
<img width="1914" height="1022" alt="image" src="https://github.com/user-attachments/assets/78cd9e42-de26-40ee-9d3b-7c52cb9ce20f" />

By clicking on the Pivot Table you can insert a Slicer.
<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/cc13a09b-e639-42de-bc2d-1b38cafecedb" />

These are the slicers.

<img width="237" height="572" alt="image" src="https://github.com/user-attachments/assets/05045065-3209-4315-9614-2c6b4e9ebf41" />

With the Slicer selected click on Report Connections and choose what are the items on your Dashboard that the slicer have to interract. 
<img width="1919" height="1026" alt="image" src="https://github.com/user-attachments/assets/813469a0-aa95-4279-aa9f-3d0ca88cdd58" />

Excel it is an amazing tool. 

https://github.com/user-attachments/assets/6351ca15-0bec-4719-8c34-7f9e2bd070a0












