# bd8_bd656_capstone_airflow_data_pipeline
Build a data pipeline to extract Reddit data from r/data engineering for a trend analysis in data engineering

dev by : Krongkhwan K. @DPU-BD8


 
...

1.	Technology stack should have

			● Apache Airflow

			● PostgreSQL or BigQuery

			● dbt (optional)

2.	The data pipeline should be able to

			● Extract the Reddit data from r/dataengineering daily

			● Transform the data into the proper format

			● Ensure the data quality



3.	Extracting Reddit Data

			● PRAW: The Python Reddit API Wrapper to extract the Reddit data

			● See this doc to study how to obtain a Subreddit



4.	Business Questions

			● What are the total number of authors and posts in this subreddit?

			● What is the average score?

			● How many posts are published per day?

			● What is the average number of comments per day?

			● Is there any interesting trend at this moment?



5.	Expectation

			● Be able to extract the Reddit data

			● Prepare the SQL for data transformation to answer the business questions mentioned in the previous slide

			● The data model must be easy to show on a dashboard

			● [Bonus] Use dbt to create your data model and schedule it in Airflow
