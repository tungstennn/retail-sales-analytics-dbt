# Retail Sales Analytics with dbt

## Overview
This project simulates a retail company's sales data pipeline and demonstrates how to use **dbt (Data Build Tool)** to transform raw data into analytics-ready models. The goal is to build a mini data warehouse that supports insights into sales performance, customer behavior, and product trends.

## Architecture
Raw data (e.g. `sales`, `products`, `customers`) is ingested into a data warehouse (Snowflake/Redshift).  
dbt then performs transformations following a layered approach:

raw → staging → intermediate → marts


Each layer cleans/dedupes, joins, and aggregates data to produce fact and dimension tables for reporting.

## Tech Stack
- **dbt Core** — SQL-based data transformation and modelling  
- **Snowflake / Redshift** — data warehouse  
- **Python / Pandas** — data loading into the warehouse  
- **Tableau / Streamlit (optional)** — dashboard or data visualization  


## Next Steps
1. Create mock retail datasets (sales, customers, products).  
2. Load raw data into the warehouse.  
3. Develop dbt models for each layer.  
4. Run and test transformations.  
5. Visualize insights using a BI tool.

---

*This project serves as a hands-on introduction to modern data transformation workflows using dbt in an ELT pipeline.*
