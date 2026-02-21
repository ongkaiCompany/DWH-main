# Designed a Data Warehouse based on Star Schema for a Retail Business
Hi there! Welcome to this repository!<br/>

My team and I designed a data warehouse based on star-schema for a retail database called Northwind.
The Northwind database is a sample database that was originally created by Microsoft and used as the basis for their tutorials in a variety of
database products for decades. The Northwind database contains the sales data for a fictitious company called “Northwind Traders”, which
imports and exports specialty foods from around the world.

Several tables were designed as Type 2 Slowly Changing Dimension tables as required by our tutor. 
In this repository, you will find SQL code for:
<ul>
  <li>Creation of the OLTP System</li>
  <li>Creation of the Data Warehouse</li>
  <li>Both the initial and subsequent loading of the Data Warehouse</li>
  <li>Business Intelligence Reports</li>  
</ul>

If you are interested in the documentation, you may refer to the pdf report that was uploaded into this repository. You will find the star schema in it. The outputs of the SQL queries and visualisations from Microsoft Excel can be found in there as well.  

Analysis
1. Sales Trend Analysis
https://github.com/ongkaiCompany/DWH-main/blob/85b12f0fb75c454b40220370c5fdf182c212b3e8/bar%20Chart.png
Insight: Identified a significant 41% sales peak in Dec 2023 ($350K). This visualization helps stakeholders understand seasonal demand and plan year-end inventory.

2. Product Contribution (Pareto Analysis)
https://github.com/ongkaiCompany/DWH-main/blob/85b12f0fb75c454b40220370c5fdf182c212b3e8/Line%20graph.png
Insight: The Top 10 products drive 40% of total revenue, with "Côte de Blaye" alone contributing 12%.
Actionable Advice: Recommended prioritized inventory management and targeted marketing for these high-velocity items to maximize ROI.


3. Employee Performance (YoY)
https://github.com/ongkaiCompany/DWH-main/blob/85b12f0fb75c454b40220370c5fdf182c212b3e8/bar%20Chart.png
Insight: Performed Year-over-Year (YoY) comparisons (2022 vs 2023) to evaluate individual sales growth and productivity trends across the sales team.











