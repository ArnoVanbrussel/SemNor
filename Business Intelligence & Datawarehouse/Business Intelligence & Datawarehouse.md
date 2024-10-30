# 1 Lecture 1: Introduction to Business Intelligence
## 1.1 What is Data & Information?
**Data:**
- raw
- unorganized facts
- needs to be processed
- can be simple and seemingly random
**Information:**
- Organized, structured, processed data

## 1.2 Data Analytics
- Process of examining data sets in order to find trends and draw conclusions about the information they contain
- Data analytics technologies and techniques are widely used in commercial industries to enable organizations to make more-informed business decisions
![[Pasted image 20240918083501.png]]
## 1.3 What is BI?
- Business Intelligence (BI) is the set of tools used to collect **raw data** and transform it into **useful insights**
- BI allows you to collect data from different sources (multiple databases, excel files, etc.), organize it, and then perform the analytics
- BI provides companies with the most balanced view of the business
- **Definition:**
> BI is a combination of tools, technologies, applications and practices that help businesses in collecting, integrating, analyzing and presenting raw data into insightful and actionable business information

- Date Warehousing Institute defines BI as the processes, technologies and tools needed to turn data into information, information into knowledge and knowledge into plans that drives profitable business action
- BI is an umbrella term that encompasses data warehousing, analytical tools and applications
	- These are leveraged to create business intelligence
	- The BI process is based on the transformation of the data, to information then to decisions and finally to action
	- BI is the outcome from this blending process
## 1.4 How are BI Systems Implemented?
**Step 1:**
- Raw data from corporate databases is extracted. The data could be spread across multiple systems heterogenous systems
**Step 2:**
- The data is cleaned and transformed into the data warehouse. The table can be linked and data cubes are formed
**Step 3:**
- Using BI systems, the user can ask queries, request ad-hoc reports or conduct any other analysis
## 1.5 What is the purpose of BI?
- The major purpose that Business Intelligence serves for a business is helping the corporate executives take better **data driven business decisions**
- Many companies are using BI for cost-cutting, identifying better business opportunities and spotting inefficient business processes
## 1.6 What are the benefits of using BI?
- Accelerating decision-making process
- Optimizing internal business processes
- Increasing the operational efficiency
- Increasing revenues
- Gaining competitive advantages
- Identifying the market trends
- Spotting addressable business problems
## 1.7 BI Examples
### 1.7.1 Example 1
- A hotel manager uses BI analytical applications to gather statistical information regarding average occupancy and room rate
- It helps to find aggregate revenue generated per room
- It also collects statistics on market share and data from customer surveys from each hotel to decides its competitive position in various markets
- By analyzing these trends year by year, month by month and day by day, the manger can choose the best strategy for offering discounts on room rentals.
### 1.7.2 Example 2
- A bank gives branch managers access to BI applications.
- It helps branch manager to determine who are the most profitable customers and which customers they should work on. 
- The use of BI tools frees information technology staff from the task of generating analytical reports for the departments. 
- The use of BI tools gives department personnel access to a richer data source.
### 1.7.3 Example 3
- In an Online Transaction Processing (OLTP) system information that could be fed into product database could be
	- add a product line
	- change a product price
- Correspondingly, in a BI system the query that would be executed would be how much revenues increased due to
	- the addition of new product line
	- and/or the change in products prices
![[Pasted image 20240918085537.png]]
- In an advertising database of OLTP system query that could be executed
	- change in advertising options
	- increase of radio budget
- Correspondingly, in BI system the query that could be executed would be:
	- How many new clients were added due to change in radio budget
![[Pasted image 20240918085537.png]]
- In OLTP system dealing with customer demographic databases, the data that could be fed would be
	- increase customer credit limit
	- change in customer salary level
- Correspondingly in the OLAP system query that could be executed would be:
	- Can customer profile changes support higher product price?
### 1.7.4 Types of BI users
**1. Professional Data Analyst:**
- The data analyst is a statistician who always needs to drill deep down into data. 
- BI system helps them to get fresh insights to develop unique business strategies
**2. IT users:**
- The IT user also plays a dominant role in maintaining the BI infrastructure
**3. The head of the company:** 
- CEO can increase the profit of their business by improving operational efficiency in their business. 
**4. The Business Users:** 
- Business intelligence users can be found across the organization.
## 1.8 BI Architecture
### 1.8.1 A High-Level BI Architecture
![[Pasted image 20240918092146.png]]
### 1.8.2 BI Architecture
- BI architecture varies in each enterprise but there are some common components of BI architecture, which are found in all BI solutions. 
- The component of a BI architecture is driven by the goals and requirements of your enterprise
![[Pasted image 20240918092227.png]]
### 1.8.3 Detailed level BI Architecture
![[Pasted image 20240918092414.png]]
### 1.8.4 Source Systems
- There are many possible data sources
- The data can be generated by many platforms - IBM, Oracle, Microsoft, Sybase, SAS
- The data can have many formats - Relational, Hierarchical, Multi-dimensional, Big data MapReduce, Unstructured
### 1.8.5 BI Service Components
 - ***Integration Services*** (ETL, Operational Data Feeds, Enterprise Application Integration, Enterprise Information Integration) 
 - ***Data Management Services*** (data warehouse, data marts, federated data marts, OLAP cubes, etc.) 
 - ***Reporting and Analytical Services*** (Analytical Reporting, ad-hoc query and batch reporting, dashboards/scorecards, predictive and prescriptive modeling, data & text mining/forecasting) 
 - ***Information Delivery and Consumption Services*** (Web portals, subscription, direct user access, internal portals, etc.)
## 1.9 Business Decision Types
- Business intelligence systems are used for decision making. 
- Business decisions can be categorized into three main types: 
	- Strategic Decisions 
	- Tactical Decisions 
	- Operational Decisions
### 1.9.1 Strategic Decisions
- Strategic decisions are major choices of actions and influence whole or a major part of business enterprise. 
- They contribute directly to the achievement of common goals of the enterprise. 
- They have long-term implications on the business enterprise. • They may involve major departures from practices and procedures being followed earlier. 
- Generally, strategic decision is unstructured and thus, a manager must apply his business judgement, evaluation and intuition into the definition of the problem.
- Strategic decisions are based on partial knowledge of the environmental factors which are uncertain and dynamic. 
- Strategic decisions are taken at the higher level of management. 
- Example of strategic decision: 
	- Identify new markets 
	- choose store locations
### 1.9.2 Tactical Decisions
- Tactical decisions relate to the implementation of strategic decisions. 
- Focus on analyzing short-term initiatives within specific line-of-business domains, such as marketing, sales, purchasing or customer service. 
- Tactical decisions are directed towards 
	- developing divisional plans, 
	- structuring workflows, 
	- establishing distribution channels, 
	- acquisition of resources such as employees, materials and money.
- These decisions are taken at the middle level of management. 
- Progress is measured against a preset goal, such as a budget or a certain target. 
- Example of tactical decision: 
	- Choose suppliers, 
	- forecast sales
### 1.9.3 Operational Decisions
- Operational decisions relate to day-to-day operations of the enterprise. 
- They have a short-term horizon as they are taken repetitively. 
- These decisions are based on facts regarding the events and do not require much of business judgement. 
- Operational decisions are taken at lower levels of management. 
- Example of operational decision: 
	- Resolve order delays, 
	- schedule employees
### 1.9.4 BI Business Value
- BI can add value to: 
	- Management Processes: 
		- Planning budgeting, performance monitoring/assessment, process improvement, cost analysis, optimization, etc. 
	- Revenue Generating Processes: 
		- Customer segmentation, campaign management, channel management, sales management, etc. 
	- Resource Consumption Processes: 
		- Product/service development, order management, manufacturing/operations, supply chain, purchasing, etc
# 2 Lecture 2: Data Warehouse Concepts
## 2.1 Basic Data Warehouse Concepts
### 2.1.1 Business Intelligence and Data Warehouse
- Business Intelligence (BI) is the act of transforming raw/operational data into insightful and actionable business information. 
- How Does BI Works? 
	- BI systems collect information from several data sources (the company operational DBs). 
	- This data is transformed (cleaned and integrated) and loaded into a Data Warehouse. 
	- Since the data in DW is credible, it is used for business insights
![[Pasted image 20240918102252.png]]
### 2.1.2 Why a Data Warehouse
- Data collected from heterogenous sources cannot be directly visualized. 
- The data first needs to be integrated and then processed before visualization takes place.
![[Pasted image 20240918102327.png]]
### 2.1.3 What is a Data Warehouse
- A central location where transformed data from multiple sources (DBs) are stored. 
- Data Warehouse is maintained separately from an organization’s operational database. 
- End users access DW whenever any information is needed. 
- Note that a Data Warehouse is not loaded every time new data is added to database. Generally, the loading process occurs automatically once per day during the night
![[Pasted image 20240918102401.png]]
## 2.2 Motivations and Characteristics
### 2.2.1 Advantages of a Data Warehouse
- A Data Warehouse can answer strategic and tactical Business questions. 
- Data Warehouse is fast and accurate in responding to queries. 
- Note that a Data Warehouse is not a product that a company can purchase. It needs to be designed and implemented according to the company business requirements
![[Pasted image 20240918102453.png]]
### 2.2.2 Decision Making Hierarchy
![[Pasted image 20240918102636.png]]
### 2.2.3 Technology and Deployment Limitations
- Why Databases are not suitable for carrying BI tasks? 
	- DB cannot be integrated with other transaction DB and other external sources. 
	- Using the same DB for transaction processing and BI tasks results in high workload for DB and lead to performance drop. 
	- DB does not offer the features requested from Datawarehouse, e.g., summary data
![[Pasted image 20240918102725.png]]
### 2.2.4 Data Warehouse Definition
- DW is an essential part of infrastructure for business intelligence 
- DW is logically centralized repository for decision making
	- Populated from operational databases and external data sources 
	- Integrated and transformed data 
	- Optimized for reporting and periodic integration
### 2.2.5 Data Warehouse Characteristics
- “A Data Warehouse is a subject-oriented, integrated, time-variant and nonvolatile collection of data in support of management’s decision-making process.” Bill Inmon, Father of Data Warehousing

	- ***Subject-oriented:*** Organized around business entities (e.g., customers, products, and employees) rather than business processes 
	- ***Integrated:*** many transformations to unify source data from independent data sources (units of measure, data formats, naming conventions) 
	- ***Time-variant:*** historical data (time stamped); snapshots of business processes captured at different points in time 
	- ***Nonvolatile:*** existing data is not changed; new data are appended periodically; warehouse data may be archived after its usefulness declines
### 2.2.6 Comparison of Processing Environments
![[Pasted image 20240918112905.png]]
### 2.2.7 Data Comparison
![[Pasted image 20240918112921.png]]
### 2.2.8 Schema Comparison
**Operational DB**
![[Pasted image 20240918112955.png]]
**Data Warehouse**
![[Pasted image 20240918113009.png]]
## 2.3 Data Warehouse Architectures
### 2.3.1 Architecture Issues
- The choice of the architecture for a DW is decided by the organization (the company), this choice is not limited by the technology 
- The choice of DW architecture depends on Data warehouse scope 
	- Number of data sources 
	- Number of organizational units
- The choice of DW architecture depends on the integration level 
	- Coordination and cooperation among business units 
	- Find common entities 
	- Enforce standards: units of measure, naming conventions 
	- Reconcile differences such as revenue and cost recognition 
	- Sometimes modify source systems
### 2.3.2 Architecture Choices
![[Pasted image 20240918113133.png]]
### 2.3.3 Data Mart
- Data mart is a smaller version of the Data Warehouse which deals with a single subject area. 
- Since Data marts focus on one area, they collect data from a limited number of sources 
- The time it takes to build a Data Mart is less compared to the time taken to build a Data Warehouse
![[Pasted image 20240918113206.png|450]]![[Pasted image 20240918113214.png|250]]
### 2.3.4 Top-Down Architecture
![[Pasted image 20240918113410.png]]
### 2.3.5 Bottom-up Architecture
![[Pasted image 20240918113429.png]]
### 2.3.6 Federated Architecture
![[Pasted image 20240918113510.png]]
- Federated data warehouse architecture is suited for decentralized or independent organizations.
- It supports two levels:
    - Each organization independently maintains its own data warehouse.
    - A shared federated data warehouse enables inter-organizational data sharing.
- Data integration and a query portal are typically used to facilitate sharing.
- Participation can be voluntary or compulsory (e.g., for government regulations).
- External stakeholders may access the federated data warehouse.
- Ideal for consortiums where multiple companies collaborate and share data.
### 2.3.7 Architecture Selection Factors
- Learning effects 
	- Project risk 
	- Intangible business value 
- Strategic view of information technology 
	- Level of sponsorship 
	- Information independence 
	- Task routineness
## 2.4 Employment Opportunities
![[Pasted image 20240918114927.png]]
### 2.4.1 Skill-Position Mapping
![[Pasted image 20240918114943.png]]
### 2.4.2 Competency Acquisition
![[Pasted image 20240918115023.png]]
### 2.4.3 Salary Percentiles (US - 2018)
![[Pasted image 20240918115053.png]]
# 3 Lecture 3: Multidimensional Data Representation and Manipulation
## 3.1 Dimensional Modelling
- Methods of organising data
![[Pasted image 20240925081951.png]]
![[Pasted image 20240925082011.png]]
- Unique technique of structuring data
- Commonly used in DWH
- Optimized for faster data retrieval
- Oriented around performance and usability
- Designed for reporting / OLAP (Online Analytical Processing)
### 3.1.1 Facts
- Foundation of DWH
- Key measurements
- Aggregated and analyzed
- Fact table: PK, FK, Facts
### 3.1.2 Dimensions
- Categorizes facts
- Supportive and descriptive
- Filtering, grouping and labeling
- Non aggregable
- Static
## 3.2 Representation of Data in DW
- **Dimensional Modeling**
	- Retrieval based system that supports high-volumen query access
- **Star Scheme**
	- Most commonly used and simplest style of dimensional modeling
	- contain a **fact table** surrounded by and connected to several **dimension tables**
![[Pasted image 20240925082952.png]]
- **Snowflake scheme**
	- extension of star scheme
![[Pasted image 20240925083006.png]]
## 3.3 Data Cube Concepts
### 3.3.1 Business Analyst Perspective
![[Pasted image 20240925101721.png]]
### 3.3.2 Data Cube Basics
- Business analyst model
	- Factors or influencing variables of interest
	- Quantitative variables
	- Multidimensional arrangement
- Terminology
	- Dimension: subject label for a row or column
	- Member: value of dimension
	- Measure: quantitative variables stored in cells
### 3.3.3 Notes on Dimensions and Measures
- Hierarchical dimensions with sub members 
- Sparsity 
	- Many cells do not have values 
	- Increases with dimension detail and number of dimensions 
- Measures 
	- Derived measures 
	- Multiple measures in cell
### 3.3.4 Measure Aggregation Properties

- Additive 
	- Summarized by addition across all dimensions 
	- Common measures such as sales, cost, and profit 
- Semi-Additive 
	- Summarized by addition in some but not all dimensions such as time 
	- Periodic measurements such as account balances and inventory levels 
- Non-Additive 
	- Cannot be summarized by addition through any dimension 
	- Historical facts such as unit price for a sale
### 3.3.5 Measure Aggregation Example
- Dimensions 
	- Course: course id, degree, department, and college – Student: student id, major, department, and college 
	- Time: semester, academic year, academic decade 
- Measures: 
	- Credit hours 
	- Grade 
	- Unit tuition – Tuition 
- Aggregation properties for measures: ?
## 3.4 Data Cube Operators
### 3.4.1 Slice Operator
- Subset of dimensions
- Set of dimension to specific value

**Slice Summarize Variation**
- Replace a dimension with a summary of its values across all members
### 3.4.2 Dice Operator
- Replace dimension with subset of values
- Dice operation often follows slice
![[Pasted image 20240925103611.png]]
### 3.4.3 Navigation Operators
- Operators for hierarchical dimensions 
- Drill-down: add detail to a dimension 
- Roll-up: remove detail from a dimension 
- Distribute or recalculate measure values
### 3.4.4 Drill-down example
![[Pasted image 20240925103701.png]]
### 3.4.5 Pivot Operator
- Rotate or rearrange dimensions
![[Pasted image 20240925103725.png]]
### 3.4.6 Operator Summary
![[Pasted image 20240925103750.png]]
# 4 Lecture 4: The ETL Process
## 4.1 Why do we need a Data Warehouse
- All information is in one place
- Up-to-date information
- Quick access
- No size limits
- All history available
- Easy to understand
- Clear and uniform definitions
- Standardized data
## 4.2 Data Marts
- To meet the specific needs of an organisation, a data mart may cover only a particular process and be limited to the boundaries of that process.
	- You won't find employee absence information in a sales data mart, because a sales analyst doesn't need that information
- However, there is no limitation to the amount or type of data that may be included in a data mart.
## 4.3 Start Schema Designing Principles
### 4.3.1 Surrogate Keys (primary key)
- Single column key for each dimension table
- Integer indexes are faster than char or datetime indexes
- Enable the storage of multiple versions of an item where the item retains its original source key but is allotted a new surrogate key
- Allow for dealing with optional relations, unknown values and irrelevant data
### 4.3.2 Naming and Type Conventions
- All tables get a prefix
	- STG_ = staging tables
	- HIS_ = historical archive tables
	- DIM_ = dimension tables
	- FCT_ = fact tables
	- AGG_ = aggregate tables
	- LKP_ = lookup tables
- Meaningful names for columns
- Avoid use of reserved words for database objects as tables
### 4.3.3 Granularity

> The level of detail at which the data is stored in the data warehouse.

- Store the data at the lowest level of detail possible
### 4.3.4 Fact table
1. Identify the business process for analysis
	- Sales
	- Order processing
2. Declare the grain
	- Transaction
	- Order
	- Order Lines
	- Daily
	- Daily + location
3. Identify dimensions that are relevant
	- What, when, where, why?
	- Time, location, products, customers
	- Filtering, grouping
4. Identify facts for measurements
### 4.3.5 Two-Column Table Methodology
- Check if star schema is correct
	- *Imaginary table* of our view to the fact measure from one particular dimension angle
- First column represents category or dimensions
- Second column represents fact
- Consists of two types:
	- One fact measure
	- Multiple fact measure
### 4.3.6 One Fact Measure
- First column contains a category
- Second column contains a statistical numerical figure
![[Pasted image 20241009083628.png]]
### 4.3.7 Multiple Fact Measure
- Second column contains multiple facts F={F1, F2, F3, ...}
- All F's must exist in all tables
![[Pasted image 20241009083724.png]]
### 4.3.8 A College Star Schema Tutorial
| **E/R Diagram**                                                                                                                                                                    | **Star Schema**                                                                                                                                                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Used as operational system to support operational procedures                                                                                                                       | Used for analysis purposes                                                                                                                                                                                                                                 |
| Example:<br>- As the college is a multi-campus university, some courses are offered in a different campus. The admission office handles international students of all campuses<br> | Example:<br>- How many students come from certain countries<br>- What is the total income for certain postgraduate courses?<br>- How many students are handled by certain agents?<br>- How does the number of enrolment courses fluctuate during the year? |

![[Pasted image 20241009084259.png]]
![[Pasted image 20241009092432.png]]
![[A College Star Schema Tutorial.pdf]]
### 4.3.9 Case Study Summary
- 3 ways to create dimension tables:
	- Use create table as `select *
	- this directly copies from the table in the operational database
- Choose selected attributes from the table in the operational database
- Create the dimension table manually, followed by `insert into insert` new records into the table
### 4.3.10 Summary on facts and dimensions
- Fact: Fact is numerical and aggregated value
- Dimension: Point of view
- Creating Dimension Tables:
	- Direct copy
	- Extracting some relevant attributes
	- Manually created
- Creating Fact Tables:
	- -Direct retrieval from the tables in the operational database
- To validate, the two-column method can be used
## 4.4 ETL Process
![[Pasted image 20241009091853.png]]
### 4.4.1 ETL Process
- ETL stands for:
	- Extraction: Collect the data from heterogenous data sources 
	- Transformation: transform, clean, and standardize the data such that it can be integrated in the same data warehouse 
	- Loading: consists of loading the data to the data warehouse
- Data staging area: the part of the data warehouse where transformations happen
- Staging area should not be available for querying
### 4.4.2 General Data Warehouse Architecture
![[Pasted image 20241009092847.png]]
### 4.4.3 Data Integration and the Extraction, Transformation and Load Process
![[Pasted image 20241009092923.png]]
### 4.4.4 ETL (Extract, Transform, Load)
- Issues affecting the purchase of an ETL Tool
	- expensive
	- steep learning curve
- Important criteria
	- Ability to read/write to unlimited number of data sources/architectures
	- Automatic capturing and delivery of metadata
	- History of conforming to open standards
	- Easy-to-use interface
### 4.4.5 Staging Area
- Where extracted data is stored and possibly transformed before loading the data into the central warehouse
	- source system load times should be kept to minimum
	- using separate staging area enables you to work on a specific subset of the data
	- dedicated schema allows for specific sorting or indexing to further optimise and support the ETL process
	- safety net: process can fail before completing
## 4.5 Tutorial on Spoon
### 4.5.1 Objective: Building coffeemerchant Data Warehouse Using Spoon PDI
![[Pasted image 20241009103043.png]]
## 4.6 Assignment
### 4.6.1 Creating the Data Warehouse Using Spoon

# 5 There's a little gap...

# 6 OLAP - OLTP
## 6.1 OLAP
> “The dynamic synthesis, analysis, and consolidation of large volumes of multi- dimensional data”

- There are five OLAP operations: 
	- Slicing 
	- Pivoting 
	- Dicing 
	- Drilling
	- Roll up
### 6.1.1 A Data Journey: from operational to analytics
![[Pasted image 20241030082529.png]]
### 6.1.2 Data cube:
- Dimensional model, but often presented as a cube
### 6.1.3 Star schema and data cube
- Data cube:
![[Pasted image 20241030082639.png]]
- Same model as star scheme:
![[Pasted image 20241030082658.png]]
### 6.1.4 Slicing
- Slicing = filtering
![[Pasted image 20241030082743.png]]
> Slice. A slice is a subset of a multidimensional array (usually a two-dimensional representation) corresponding to a single value set for one (or more) of the dimensions not in the subset
### 6.1.5 Pivoting
> Pivot. This is used to change the dimensional orientation of a report or ad hoc query-page display

![[Pasted image 20241030082828.png]]
### 6.1.6 Dicing
![[Pasted image 20241030082905.png]]
### 6.1.7 Drill Down/Up
> Drilling down or up is a specific OLAP technique whereby the user navigates among levels of data ranging from the most summarized (up) to the most detailed (down).

![[Pasted image 20241030083002.png]]
### 6.1.8 Roll-up
![[Pasted image 20241030083040.png]]
### 6.1.9 Implementation of OLAP
- **MOLAP**: Based on data in «multidimensional» database 
	- IBM Cognos 
	- Oracle Database OLAP Option 
	- Microsoft Analysis Services 
- **ROLAP**: Based on data in a relational database 
	- Mondrian OLAP Server 
- **HOLAP**: A combination of the two previous types(Hybrid OLAP) – some data can be represented multidimensionally and others relasionally 
	- Most products today supports HOLAP
#### 6.1.9.1 MOLAP - Multidimensional OLAP
- The «classic» type of OLAP 
	- Data stored in multidimensional arrays 
	- Typically contains summarized and calculated data 
	- Very quick for queries that are already calculated 
	- Can use a lot of time to update • Do not use SQL
#### 6.1.9.2 ROLAP - Relational OLAP
- Data in a relational database 
- Can use special tables for summarized data 
- Data can be accessed with SQL 
- Queries not limited to existing summarizations 
- The database system should be adapted for OLAP 
	- Some database systems are optimized for OLTP only 
	- Database systems like Oracle Enterprise Server, SQL Server and IBM DB2 are optimized both for OLTP and OLAP 
- Loading usually much faster than for MOLAP databases
#### 6.1.9.3 HOLAP - Hybrid OLAP
- Vertical partitioning: 
	- Detailed data stored in a relational database 
	- Aggregated data stored in a multidimensional database
- Horizontal partitioning: 
	- A selection of data, typically the most recent, are stored multidimensionally 
	- Older data are stored relationally
## 6.2 OLTP (Online Transaction Processing)
- OLTP is a type of data processing that consists of executing a number of transactions occurring concurrently - online banking, shopping, order entry, or sending text messages, for example. 
- These transactions traditionally are referred to as economic or financial transactions, recorded and secured so that an enterprise can access the information anytime for accounting or reporting purposes.
### 6.2.1 OLTP vs OLAP
- OLTP (Online Transaction Processing) 
	- Capturing and storing data from ERP, CRM, POS, 
	- The main focus is on efficiency of routine tasks 
- OLAP (Online Analytical Processing) 
	- Converting data into information for decision support 
	- Data cubes, drill-down/rollup, slice & dice, 
	- Requesting ad hoc reports 
	- Conducting statistical and other analyses 
	- Developing multimedia-based applications
### 6.2.2 OLAP vs OLTP
![[Pasted image 20241030085034.png]]
## 6.3 SQL CUBE Operator
### 6.3.1 CUBE Operator Characteristics
![[Pasted image 20241030085733.png]]
### 6.3.2 CUBE / Group By Comparison
![[Pasted image 20241030085759.png|250]]![[Pasted image 20241030085814.png|250]]
### 6.3.3 CUBE Operator Calculations
- GROUP BY CUBE(Col1, Col2) 
	- M unique values in Col1 
	- N unique values in Col2 
- Result rows 
	- Maximum of M × N rows: GROUP BY Col1, Col2 
	- Maximum subtotal rows of M + N + 1 (CUBE) 
- Subtotal groups 
	- Three groups of subtotal rows (Col1, Col2, grand total) 
	- Derive CUBE operation with UNION operations
### 6.3.4 CUBE Calculations with 3 columns
- GROUP BY Col1, Col2, Col3
- Result rows 
	- Maximum GROUP BY rows: M × N × P 
	- Maximum subtotal rows: M + N + P + M × N + M × P + N × P + 1 
- Subtotal groups 
	- Normal GROUP BY totals (1) 
	- Combinations of 2 columns (3) 
	- Combinations of 1 column (3) 
	- Grand total (1) 
	- Number of subtotal groups: 8 (2³)
### 6.3.5 Cube
- In OLAP, it is typical to produce a matrix visual or table which crosses two pieces of categorical information and contains sub-totals
![[Pasted image 20241030092028.png]]
### 6.3.6 CUBE Example
- Summarize sales in 2006 in Orlando and Chicago by product type
![[Pasted image 20241030092100.png]]
![[Pasted image 20241030092120.png]]
#### 6.3.6.1 Group by Roll up
- GROUP BY ROLLUP (itemtype, city)
![[Pasted image 20241030092208.png]]
- GROUP BY ROLLUP (city, itemtype)
![[Pasted image 20241030092330.png]]
## 6.4 Decision Making
### 6.4.1 Business Pressures–Responses–Support Model
![[Pasted image 20241030092532.png]]
### 6.4.2 Decision Making
- Is a process of 
	- choosing among two or more alternative courses of action for the purpose of attaining one or more goals
- It is influenced by
	- behavioral and scientific disciplines
### 6.4.3 Managerial Responsibilities
- Planning
- Organizing
- Commanding
- Controlling
- Coordinating
### 6.4.4 Decision Making Steps
- Define the problem 
- Construct a model 
- Identify & Evaluate possible solutions 
- Compare, choose, and recommend a potential solution to the problem
### 6.4.5 Decisions Making Scenarios
- Structured Decisions
- Unstructured Decisions 
- Semi-structured decisions
### 6.4.6 Decision Making Constraints & Complexities
- Evaluating what-if scenarios 
- Experimentation with a real system 
- Changes in the decision-making environment may occur continuously 
- Time pressure on the decision maker 
- Analyzing a problem takes time/money 
- Insufficient or too much information 
- Accuracy versus speed 
- Effectiveness versus efficiency
### 6.4.7 Decision Making Support
- Group communication and collaboration 
- Improved data management 
- Giant data warehouses and big data
- Analytical support 
- Overcoming cognitive limits in information processing and storage 
- Knowledge management 
- The ability to access information anywhere, anytime
### 6.4.8 Common Approaches of Decision Makers
- Left brain approach
- Right brain approach
- Accommodation
- Integrated
### 6.4.9 Simon's Decision-Making Process
![[Pasted image 20241030103029.png]]
### 6.4.10 DM Process Phases

#### 6.4.10.1 DM Process Intelligence Phase

- Problem Identification
- Problem Ownership
- Problem Classification
- Problem Decomposition
- Outcome of intelligence phase is a formal problem statement
- Scan the environment, either intermittently or continuously
- Identify problem situations or opportunities
- Monitors the results of the implementation

#### 6.4.10.2 DM Process Design Phase
- Determine alternatives
    - Finding/developing and analyzing possible courses of actions
- Predict and measure outcomes
    - A model of the decision-making problem is constructed, tested and validated
#### 6.4.10.3 DM Process Choice Phase
- Making the actual decision and the commitment to follow a certain course of action
    - Search
        - Evaluation
        - Recommendation
- Search approaches
    - Analytic techniques (solving with a formula)
        - Algorithms (step-by-step procedures)
        - Heuristics (rule of thumb)
        - Blind search (truly random search)
- Model manipulation
    - Sensitivity analysis
        - What-if analysis
        - Goal seeking
#### 6.4.10.4 DM process Implementation Phase
- Implementation
    - The initiation of a new order of things
        - The introduction of change
        - Putting a recommended solution to work
- Issues
    - Resistance to change
        - Degree of support of top management
        - User training
### 6.4.11 Common strategies of decision makers
- Optimizing versus satisfying
- Elimination by aspects vs incrementalism
- Mixed scanning
- Minimizing risk and uncertainty

## 6.5 Decision Support Systems
### 6.5.1 Decision Support Systems (DSS)
- DSS describes any computerized system that supports decision making in an organization. 
- DSS is to support managerial decisions in semi-structured and unstructured decision situations that middle-level managers typically face; 
	- attempt to combine the use of models or analytical techniques with traditional data access and retrieval functions; 
	- focus on features which make them easy to use in an interactive mode; 
	- emphasize flexibility and adaptability to accommodate changes in the environment and decision-making approach of the user
### 6.5.2 Components of DSS
![[Pasted image 20241030105151.png]]
### 6.5.3 DSS Classifications
- Data-driven 
- Document-driven 
- Knowledge-driven 
- Model-driven 
- Communications driven
### 6.5.4 Evolution of DSS Applications
- Executive Information Systems (EIS) 
- Group Support Systems (GSS) 
- Geographic Information Systems (GIS) 
- Expert Systems (ES) 
- Knowledge Management Systems (KMS) 
- Enterprise Resource Planning Systems (ERP), Customer Relationship Management Systems (CRM), Supply Chain Management Systems (SCM)
### 6.5.5 How decisions are supported in practice
![[Pasted image 20241030111006.png]]
## 6.6 Data Visualization
> “The use of visual representations to explore, make sense of, and communicate data.”
- Data visualization versus. Information visualization 
	- Information = aggregation, summarization, and contextualization of data 
- Related to information graphics, scientific visualization, and statistical graphics 
- Often includes charts, graphs, illustrations,
### 6.6.1 A Brief History of Data Visualization
- Data visualization can date back to the second century A D 
- Most developments have occurred in the last two and a half centuries
- Until recently it was not recognized as a discipline 
- Today’s most popular visual forms date back a few centuries
### 6.6.2 The First Line/Area Chart Created by William Playfair in 1801
> William Playfair is widely credited as the inventor of the modern chart, having created the first line and pie charts
![[Pasted image 20241030111215.png]]
### 6.6.3 Decimation of Napoleon’s Army During the 1812 Russian Campaign
![[Pasted image 20241030111240.png]]
### 6.6.4 Different types of charts and graphs
- Basic Charts and Graphs 
	- Line chart 
	- Bar chart
	- Pie chart 
		- Donut chart 
	- Scatter plot 
		- Bubble chart 
- Specialized charts 
	- Histogram, Gantt chart, PERT chart, Geographic charts, Buller chart, Hear map, Highlight table, Tree map
### 6.6.5 Which chart to use?
![[Pasted image 20241030111354.png]]
### 6.6.6 An Example Gapminder Chart Wealth and Health of Nations
![[Pasted image 20241030111437.png]]
### 6.6.7 The Emergence of Data Visualization and Visual Analytics
- Many data visualization companies represented 
- There is a continuous move towards visualization in analytics
- Magic Quadrant for Business Intelligence and Analytics Platforms
![[Pasted image 20241030111544.png]]
### 6.6.8 Technology Insights 4.4
- Telling Great Stories with Data and Visualization 
- Why story? 
- What Is a Good Story? 
- Story telling best practices: 
	- Think of your analysis as a story—use a story structure. 
	- Be authentic—your story will flow. 
	- Be visual—think of yourself as a film editor. 
	- Make it easy for your audience and you. 
	- Invite and direct discussion.
### Visual Analytics
- A recently coined term
	- Information visualization + predictive analytics
- Information visualization
	- Descriptive, backwards focused
	- "what happened", "what is happening"
- Predictive analytics
	- predictive, future focused
	- "what will happen", "why will it happen"
- Strong move toward visual analytics
### Visual Analytics by SAS Institute
- SAS Visual Analytics Architecture
![[Pasted image 20241030112144.png]]
- SAS Viya for Education – Analytics on the Cloud
![[Pasted image 20241030112226.png]]
### Information Dashboards
- Information dashboards are commonly used in Business Process Management (BPM) software suites and BI platforms
- Dashboards provide visual displays of important information that is consolidated and arranged on a single screen so that information can be digested at a single glance and easily drilled in and further explored
### Performance Dashboards
![[Pasted image 20241030112533.png]]
- Dashboard design
	- The fundamental challenge of dashboard design is to display all the required information on a single screen, clearly and without distraction, in a manner that can be assimilated quickly
- Three layer of information
	- Monitoring
	- Analysis
	- Management
- What to look for in a dashboard
	- Use of visual components to highlight data and exceptions that require action
	- Transparent to the user, meaning that they require minimal training and are extremely easy to use
	- Combine data from a variety of systems into a single, summarized, unified view of the business
	- Enable drill-down or drill-through to underlying data sources or reports 
	- Present a dynamic, real-world view with timely data
	- Require little coding to implement, deploy and maintain
### Best Practices in Dashboard Design
- Benchmark KPIs with Industry Standards
- Wrap the metrics with contextual metadata
- Validate the Design by a usability specialist
- Prioritize and rank alerts and exceptions
- Enrich dashboard with business-user comments
- present information in three different levels
- pick the right visual constructs
- provide for guided analytics
### Analytics in Action
> Increasing the Efficiency of Social Media Campaign Reporting to get Insights Quicker

- Motivation
- Implementation
	- Blending technologies for an automated, bespoke and branded reporting solution
- Results
	- Automatic data processing and increased reporting frequency