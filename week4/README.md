
# Datawarehouse data modelling

Dimentional data  modelling:

A dimensional data model is a type of database model designed for data warehousing and business intelligence applications. It organizes and structures data in a way that facilitates easy reporting and analysis. In a dimensional data model, there are two main types of elements: dimensions and facts. Let's explore each with real-life examples:

Dimensions:
Dimensions are the descriptive attributes or characteristics by which you want to analyze and categorize your data. They provide context to the measurements (facts) in a data model. Here are some common examples:

Time Dimension:

Example: Consider a sales database where you want to analyze sales performance over time. The time dimension could have attributes like Year, Quarter, Month, and Day.
Product Dimension:

Example: In a retail database, the product dimension might include attributes like ProductID, ProductName, Category, and Brand.
Customer Dimension:

Example: In a customer relationship management (CRM) system, the customer dimension could include attributes such as CustomerID, CustomerName, Address, and CustomerType.
Facts:
Facts are the numerical, measurable data points that you want to analyze. They represent business metrics and performance indicators. Here are some common examples:

Sales Fact:

Example: In a sales database, the Sales fact might include measures such as QuantitySold, Revenue, and Profit.
Inventory Fact:

Example: In a supply chain database, the Inventory fact might include measures like QuantityOnHand, ReorderPoint, and DaysInStock.
Web Analytics Fact:

Example: For a website analytics database, the fact table could include measures such as PageViews, UniqueVisitors, and BounceRate.
In a dimensional data model, these dimensions and facts are typically organized into a star schema or snowflake schema. In a star schema, the fact table is at the center, surrounded by dimension tables. In a snowflake schema, the dimension tables are normalized into multiple related tables.

For instance, using a star schema, you might have a central Sales fact table surrounded by Time, Product, and Customer dimension tables. This structure allows for efficient and intuitive querying and reporting, making it easier for business users to analyze and understand the data.






