A data warehouse is a type of data management system that is designed to enable and support business intelligence (BI) activities, especially analytics. 
Data warehouses are solely intended to perform queries and analysis and often contain large amounts of historical data. 
The data within a data warehouse is usually derived from a wide range of sources such as application log files and transaction applications.
A data warehouse centralizes and consolidates large amounts of data from multiple sources. 
Its analytical capabilities allow organizations to derive valuable business insights from their data to improve decision-making. 
Over time, it builds a historical record that can be invaluable to data scientists and business analysts. 
Because of these capabilities, a data warehouse can be considered an organization’s “single source of truth.” 
A typical data warehouse often includes the following elements:
 A relational database to store and manage data
 An extraction, loading, and transformation (ELT) solution for preparing the data for analysis
 Statistical analysis, reporting, and data mining capabilities
 Client analysis tools for visualizing and presenting data to business users
 Other, more sophisticated analytical applications that generate actionable information by applying data science and artificial intelligence (AI) algorithms, or graph and spatial features that enable more kinds of analysis of data at scale
 Data warehouses offer the overarching and unique benefit of allowing organizations to analyze large amounts of variant data and extract significant value from it, as well as to keep a historical record.
Four unique characteristics (described by computer scientist William Inmon, who is considered the father of the data warehouse) allow data warehouses to deliver this overarching benefit. 
According to this definition, data warehouses are
 # Subject-oriented. They can analyze data about a particular subject or functional area (such as sales).
 # Integrated. Data warehouses create consistency among different data types from disparate sources.
 # Nonvolatile. Once data is in a data warehouse, it’s stable and doesn’t change.
 # Time-variant. Data warehouse analysis looks at change over time.
A well-designed data warehouse will perform queries very quickly, deliver high data throughput, and provide enough flexibility for end users to “slice and dice” or 
reduce the volume of data for closer examination to meet a variety of demands—whether at a high level or at a very fine, detailed level. 
The data warehouse serves as the functional foundation for middleware BI environments that provide end users with reports, dashboards, and other interfaces.
# Data Warehouse Architecture
The architecture of a data warehouse is determined by the organization’s specific needs. Common architectures include
Simple. All data warehouses share a basic design in which metadata, summary data, and raw data are stored within the central repository of the warehouse. The repository is fed by data sources on one end and accessed by end users for analysis, reporting, and mining on the other end.
Simple with a staging area. Operational data must be cleaned and processed before being put in the warehouse. Although this can be done programmatically, many data warehouses add a staging area for data before it enters the warehouse, to simplify data preparation.
Hub and spoke. Adding data marts between the central repository and end users allows an organization to customize its data warehouse to serve various lines of business. When the data is ready for use, it is moved to the appropriate data mart.
Sandboxes. Sandboxes are private, secure, safe areas that allow companies to quickly and informally explore new datasets or ways of analyzing data without having to conform to or comply with the formal rules and protocol of the data warehouse.
