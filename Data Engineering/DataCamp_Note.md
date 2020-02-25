## Tools of data engineer:
* **Databases**
  * Relational Database
    * Example
      * MySQL
      * PostgreSQL
    * Star Schema: consist one or more fact tables referencing any number of dimension tables
      * Fact table: things that happened
      * Dimension table: information on the world
  * NoSQL
    * MongoDB
    * Redis
    
* **Processing (Parallel Computing)**
  * Hadoop
    * HDFS
    * MapReduce
    * Hive: runs on hadoop, HiveSQL
   * Spark a fast and general engine for large-scale data processing
    * RDD(Resilient Distributed Datasets
    * PySpark: Python API to Spark
    
* **Scheduling**
  * Airflow
    * DAG(Directed Acyclic Graph)
    
## ETL
* **Extract**: get data from several sources

* **Transform**: perform transformation using parallel computing

* **Load**: load data into target databases
  * Analytics
    * Online analytical processing(OLAP), aggregate queries
    
  * Applications:
    * Online transaction processing, lots of processing
