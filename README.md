# Twitter ETL with Airflow and PySpark

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Twitter ETL with Airflow and PySpark**
| :label: Tecnologias | Apache Airflow, PySpark, Spark, Python

![](/twitter.jpg#vitrinedev)


Process of scheduled data extraction, transform and load is done using Apache Airflow in a tweet simulator website (the API became paid).

Data lake is divided into 3 Categories: Bronze, silver and gold. Raw extrated data is stored in bronze folder. Silver is the data with some treatment to ease viasualization and statistical/machine learning model creation. Gold has more automated data organization.

Airflow is used to schedule and order the processes. Although this is a small data project, Spark is used for educational and training purposes. This is a simple version of a data engineering task with big data and automated pipelines.

Airflow pipeline is divided into 3 folders: Hook, operator and insight. Hook has the script in witch the connection with API is stablished data is obtained. The operator script makes the data cleaning and treatment. Insight is responsible for the loading process.

'src' has also a notebooks folder that contains short data analyses of each category of data lake groups.
