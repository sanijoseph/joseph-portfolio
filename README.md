# joseph-portfolio
Analytics portfolio
# [Project 1: data extraction from datasets]

this is the first project done during my certification course, where i extract some data from the datasets.

- I had to Extract the first name and last name from the Full Name column using appropriate text functions.
- I Created a column that shows the email address for each employee in this format:firstname.lastname@dame.com
- I Created a column that shows the length of each full name.
- I was instructed to Convert the department name to:
All uppercase (UPPER)
All lowercase (LOWER)
Proper case (PROPER)
 and also Remove any extra spaces in names using the TRIM function.
using Basic Aggregations
- i found the
   -Total Salary using SUM
   -Average Salary using AVERAGE
   -Total number of employees using COUNTA
- finally i Calculated:
  -Total Salary for only Sales Department using SUMIF
  -Average Salary for only HR Department using AVERAGEIF
  -Total Salary for Lagos employees with more than 3 years of experience using SUMIFS
  -Average Salary for Female employees in Lagos using AVERAGEIFS
  -Count the number of Male employees in Lagos using COUNTIFS
  -Find the Maximum Salary for employees in IT Department using MAXIFS

 EXCEL INTERFACE
<img width="1215" height="511" alt="image (1)" src="https://github.com/user-attachments/assets/7e04387a-07ed-4a77-b026-c2bbe12c8022" />



# {Project 2: sales analysis dashboard}
this was my second project and i had to visualize a sales analysis on a dashboard


- i had to Calculate the KPIs(Revenue, COGS, Profit and Customer) from my datasets

Then i Created my Pivot tables and found the following:

- i Visualized Product by Profit (To find the most profitable Product)

- i Visualized Sales Rep by Revenue (To find the most profitable Sales Rep)

- i Visualized City by COGS

- Visualize Monthly Customer (To find the worst performing month)

These were all arranged in the dashboard

finally i added 2 slicers to my dashboard: Region and Category slicers

DASHBOARD


<img width="704" height="434" alt="image (3)" src="https://github.com/user-attachments/assets/e6458718-2661-483e-8fcb-0058af2cec95" />


# (project 3: sales and customer demographic powerbi dashboard)
1. Project OverviewThe objective of this project was to transform raw, multi-table business data into an interactive, high-level executive dashboard. By connecting sales transactions with product details and customer demographics, this dashboard empowers business leaders to analyze revenue drivers, track customer acquisition trends, and evaluate product profitability at a glance.

2. Data Architecture & Transformation (ETL)The foundational data was extracted from a multi-sheet workbook named t2ugdXCRGGkWmsN5aMEH_Power BI project TSA (1) (1).xlsx, consisting of three primary relational tables:
   Sales: Transactional ledger tracking SaleID, quantities, transaction dates (SaleDate), SalesAmount, and Unit Cost.
   Products: Product dimension containing ProductID, names, categories, Brand, and Color.
   Customers: Demographic dimension capturing CustomerID, Region, Gender, IncomeLevel, and SignupDate

   Data Engineering Actions:
   Data Modeling: Established a Star Schema in Power BI by creating One-to-Many ($1 \rightarrow *$) relationships from the Products and Customers dimension tables to the central Sales fact table.
   Calculated Measures (DAX): Formulated essential business metrics to track performance, including:
   Revenue: Sum of SalesAmount ($\approx \$3\text{M}$)
   Total Cost: Based on unit costs and quantities ($\approx \$2\text{M}$)
   Profit: Net margin derived from Revenue minus Total Cost ($\approx \$932\text{K}$)
3. Dashboard Design & Key InsightsThe final interactive application—visualized in image (5).png—features a sleek, dark-themed user interface optimized for executive scannability.
 A. High-Level KPIs (Executive Summary)
   Financial Health: The business brought in $3M in total revenue, yielding $932K in net profit against a cost overhead of $2M.
   Customer Base: The business actively serves 251 unique customers.
 B. Breakdown AnalysesBrand Profitability (Horizontal Bar Chart): Apple stands out as the most profitable brand, generating nearly $200K in profit, closely followed by Lenovo and Samsung, while Dell anchors the lower tier.
Demographic & Product Drivers (Bar Charts):
  Color Preferences:Products with the color White generated the highest sales volume, outperforming Gray and Black variants.
  Income Tier Profiles: Customers classified in the Medium income bracket generated the highest profit margins, followed by High and Low tiers.
C. Trends & ProportionsCustomer
 Sign-up Velocity (Line Chart): Tracks the monthly intake of customers (Count of CustomerID), highlighting seasonal sign-up activity dipping from May through July.
 Revenue Split (Donut Chart): Breaks down yearly revenue distributions to easily monitor annual financial scaling ($77.18\%$ vs $22.82\%$).
4. Interactive Features for End Users
 To ensure the dashboard functions as an exploratory tool rather than a static report, I integrated targeted filtering components:
  Regional Slicers: Allows stakeholders to filter all visual metrics by specific geographic territories (North, East, South, West).
  Demographic Slicers: Enables cross-filtering by customer Gender (Male/Female) to instantly discover targeted purchasing habits across different brands and product colors.
5. Portfolio TakeawaysThis project showcases my ability to clean disjointed data tables, engineer robust relational data models, translate raw data into key business performance indicators (KPIs), and present information through professional, user-centric dashboard design.

   DASHBOARD
   <img width="766" height="428" alt="image (5)" src="https://github.com/user-attachments/assets/b7a14c69-cd42-4b67-9874-6a37f7ba2df8" />


