# 1 Lecture 1
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
# 2 BI Examples
## 2.1 Example 1
- A hotel manager uses BI analytical applications to gather statistical information regarding average occupancy and room rate
- It helps to find aggregate revenue generated per room
- It also collects statistics on market share and data from customer surveys from each hotel to decides its competitive position in various markets
- By analyzing these trends year by year, month by month and day by day, the manger can choose the best strategy for offering discounts on room rentals.
## 2.2 Example 2
- A bank gives branch managers access to BI applications.
- It helps branch manager to determine who are the most profitable customers and which customers they should work on. 
- The use of BI tools frees information technology staff from the task of generating analytical reports for the departments. 
- The use of BI tools gives department personnel access to a richer data source.
## 2.3 Example 3
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
## 2.4 Types of BI users
**1. Professional Data Analyst:**
- The data analyst is a statistician who always needs to drill deep down into data. 
- BI system helps them to get fresh insights to develop unique business strategies
**2. IT users:**
- The IT user also plays a dominant role in maintaining the BI infrastructure
**3. The head of the company:** 
- CEO can increase the profit of their business by improving operational efficiency in their business. 
**4. The Business Users:** 
- Business intelligence users can be found across the organization.
# 3 BI Architecture
## 3.1 A High-Level BI Architecture
![[Pasted image 20240918092146.png]]
## 3.2 BI Architecture
- BI architecture varies in each enterprise but there are some common components of BI architecture, which are found in all BI solutions. 
- The component of a BI architecture is driven by the goals and requirements of your enterprise
![[Pasted image 20240918092227.png]]
## 3.3 Detailed level BI Architecture
![[Pasted image 20240918092414.png]]
## 3.4 Source Systems
- There are many possible data sources
- The data can be generated by many platforms - IBM, Oracle, Microsoft, Sybase, SAS
- The data can have many formats - Relational, Hierarchical, Multi-dimensional, Big data MapReduce, Unstructured
## 3.5 BI Service Components
 - ***Integration Services*** (ETL, Operational Data Feeds, Enterprise Application Integration, Enterprise Information Integration) 
 - ***Data Management Services*** (data warehouse, data marts, federated data marts, OLAP cubes, etc.) 
 - ***Reporting and Analytical Services*** (Analytical Reporting, ad-hoc query and batch reporting, dashboards/scorecards, predictive and prescriptive modeling, data & text mining/forecasting) 
 - ***Information Delivery and Consumption Services*** (Web portals, subscription, direct user access, internal portals, etc.)
# 4 Business Decision Types
- Business intelligence systems are used for decision making. 
- Business decisions can be categorized into three main types: 
	- Strategic Decisions 
	- Tactical Decisions 
	- Operational Decisions
## 4.1 Strategic Decisions
- Strategic decisions are major choices of actions and influence whole or a major part of business enterprise. 
- They contribute directly to the achievement of common goals of the enterprise. 
- They have long-term implications on the business enterprise. • They may involve major departures from practices and procedures being followed earlier. 
- Generally, strategic decision is unstructured and thus, a manager must apply his business judgement, evaluation and intuition into the definition of the problem.
- Strategic decisions are based on partial knowledge of the environmental factors which are uncertain and dynamic. 
- Strategic decisions are taken at the higher level of management. 
- Example of strategic decision: 
	- Identify new markets 
	- choose store locations
## Tactical Decisions
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
## Operational Decisions
- Operational decisions relate to day-to-day operations of the enterprise. 
- They have a short-term horizon as they are taken repetitively. 
- These decisions are based on facts regarding the events and do not require much of business judgement. • Operational decisions are taken at lower levels of management. • Example of operational decision: – Resolve order delays, – schedule employees