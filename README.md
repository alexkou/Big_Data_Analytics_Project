Our task was to implement 10 queries for the MovieLens dataset and execute them in **PySpark**, with the following configurations for Apache Spark.
- Single node local machine
- Virtual cluster machine (1 master + 2 worker nodes)
- Livy server virtual cluster (1 master + 2 worker nodes)

We measured and compared the performance for each configuration using **spark-measure**. For the queries implementation we used **Spark SQL** module. 
