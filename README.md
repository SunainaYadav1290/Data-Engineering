
# Data Engineering Projects
## 1. NASA Patent Analytics Dashboard 
Live App: https://nasa-innovation-insights.streamlit.app/

•	API-Driven Dashboard: Built a live application that fetches real-time data directly from the NASA Technology Transfer API, ensuring the dashboard is always synchronized with the latest patent filings.
•	YAML Configuration: Used YAML files to manage app settings and API metadata, making the code modular, easy to update, and more secure.
•	Data Analysis with Pandas: Cleaned and processed raw JSON data into structured tables to power a "Patent Expiry Lookup" tool for 900+ active cases.
•	Automated Visualization: Created interactive charts and KPI cards in Streamlit to track innovation trends across different NASA research centers (Langley, Goddard, etc)

 

## 2. GitHub Logs ETL Pipeline using PySpark 
GitHub: https://github.com/SunainaYadav1290/Github_logs_etl_pipeline



• Built an ETL pipeline using PySpark to extract real-time issue data from the GitHub API.

• Implemented retry handling, logging, and preprocessing to clean nested JSON data, remove duplicates, and handle null values.

• Applied PySpark transformations to extract time-based features and aggregate logs for analytical reporting.

• Stored processed data in partitioned Apache Parquet format for optimized querying and reduced storage usage.

• Managed a Linux-based development environment using WSL (Ubuntu), virtual environments, and Git for version control.
