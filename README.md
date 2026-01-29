# Data-Engineering
Projects
1.Project : NASA Patent Analytics Dashboard 
Live App: https://nasa-innovation-insights.streamlit.app/

•	API-Driven Dashboard: Built a live application that fetches real-time data directly from the NASA Technology Transfer API, ensuring the dashboard is always synchronized with the latest patent filings.
•	YAML Configuration: Used YAML files to manage app settings and API metadata, making the code modular, easy to update, and more secure.
•	Data Analysis with Pandas: Cleaned and processed raw JSON data into structured tables to power a "Patent Expiry Lookup" tool for 900+ active cases.
•	Automated Visualization: Created interactive charts and KPI cards in Streamlit to track innovation trends across different NASA research centers (Langley, Goddard, etc)

 

2.Project : Automated GitHub Log Aggregator & ETL Pipeline  Link:https://github.com/SunainaYadav1290/Logs_Aggregator_Project
	 
•	Engineered an automated ETL pipeline using Apache Airflow to extract real-time event logs from the GitHub API.
•	Implemented data transformation logic using Pandas to clean raw JSON data, extract key metrics (actor, event type, repo), and generate time-based partitions (Year/Month/Day).
•	Optimized storage efficiency by converting raw data into Apache Parquet format, leveraging columnar storage for faster analytical queries and reduced disk usage.
•	Managed a local Linux environment via WSL (Ubuntu) to orchestrate tasks, handle environment variables, and manage python virtual environments.
