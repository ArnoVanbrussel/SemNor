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
### Competency Acquisition
![[Pasted image 20240918115023.png]]
### Salary Percentiles (US - 2018)
![[Pasted image 20240918115053.png]]
