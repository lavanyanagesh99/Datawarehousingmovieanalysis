# Data warehousing movie analysis
Hi!
Welcome to my GitHub repository
I created and orchestrated a data pipeline to analyze the IMDB movie data in this project.

The data pipeline was created using the following tools:

Data ingestion: Web scraping from IMDB using Python
Data storage: Google BigQuery
Data analysis: DBT
Data visualization: Power BI


## Project Overview
This project involves extracting IMDb movie data, transforming it, and loading it into a data warehouse to perform analytical queries. The primary goal is to gain insights into movie trends, ratings, and other related analytics.
![Process Diagram](https://github.com/lavanyanagesh99/Datawarehousingmovieanalysis/assets/145505542/f8905c1f-9604-464a-a964-9a6779864d84)

## Data Source
The data was sourced from IMDb (Internet Movie Database), which provides comprehensive details about movies, including titles, genres, ratings, and more.

## Repository Structure
- **Dimensional Modeling**: Contains the Star Schema model with facts and dimension tables.
- **Extract_to_Staging**: Python scripts for extracting data from IMDb and loading it into the staging area.
- **Data_Warehouse_Schema**: SQL scripts for creating the Fact & Dimension tables in the data warehouse.
- **ETL_Scripts**: Python scripts for ETL processes, transforming data, and loading into the data warehouse.

## Tools and Technologies
- **Python**: For scripting and automation.
- **BigQuery**: For database management and querying.
- **Google Cloud**: Cloud platform for hosting the data warehouse.


## Execution Order
1. `Extract_to_Staging`
2. `Data_Warehouse_Schema`
3. `ETL_Scripts`
