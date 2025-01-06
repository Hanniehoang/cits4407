# FIFA 2014 Player Graph Database

## Authors
- Thi Ngoc Han Hoang (23432313)
- Yunhui Zhang (23839202)
## Overview
This project involves the creation of a **graph database** to analyze data from the **2014 FIFA World Cup**, focusing on 736 players. The data includes player attributes such as position, age, international goals, and club affiliation. The database allows for efficient querying of player relationships, club connections, and national team trends.

## Key Features
- **Graph Database Structure:** Designed using **Neo4j**, creating nodes for players, clubs, countries, and club countries.
- **ETL Processes:** Extract, transform, and load (ETL) processes were implemented to clean and organize the dataset for efficient querying.
- **Optimized Queries:** Supports complex queries such as:
  - Identifying player paths between clubs.
  - Analyzing trends in player age, international goals, and club affiliation.
  - Listing players by position, age, or caps.

## Technologies Used
- **Neo4j** for graph database management and Cypher querying.
- **Python** for ETL processing and data manipulation.
- **Cypher** for writing and executing graph queries.

## Getting Started

### Prerequisites
To get started with this project, you’ll need:
- **Neo4j** installed (or you can use a Neo4j cloud service).
- Python and necessary libraries for running ETL scripts:
  - `neo4j`
  - `pandas`
