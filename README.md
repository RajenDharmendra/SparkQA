# SparkQA
# Apache Spark Interview Question and Answers

Apache® Spark™ is a powerful open source processing engine built around speed, ease of use, and sophisticated analytics. It was originally developed at UC Berkeley in 2009. It has become one of most rapidly-adopted cluster-computing frameworks by enterprises in different industries across the globe. Expert professionals are in great demand with the rise of the importance of big data and analytics. With the rise in opportunities in big data, you need to be proficient in the tools and skills associated with it.

As a big data expert, it is expected that you should have experience in some of the prominent tools in the industry, including Apache Spark. This article will help you to crack an Apache Spark interview with some of the frequently-asked questions: 

Q1.  Mention some of the areas where Spark outperforms Hadoop in processing

 

Ans. Sensor data processing, real-time querying of data, and stream processing.
 
Q2.  What is RDD?

 

Ans. RDD (Resilient Distribution Datasets) is a fault-tolerant collection of operational elements that run parallel. The partitioned data in RDD is immutable and distributed.

 
Q3.  Name the different types of RDD

 

Ans. There are primarily two types of RDD – parallelized collection and Hadoop datasets.

 
Q4.  What are the methods of creating RDDs in Spark?

 

Ans. There are two methods –

    By parallelizing a collection in your Driver program.
    By loading an external dataset from external storage like HDFS, HBase, shared file system.

 
Q5.  What is a Sparse Vector?

 

Ans. A sparse vector has two parallel arrays –one for indices and the other for values.
 
Q6.  What are the languages supported by Apache Spark and which is the most popular one?

 

Ans. There are four languages supported by Apache Spark – Scala, Java, Python, and R. Scala is the most popular one.
 
Q7.  What is Yarn?

 

Ans. Yarn is one of the key features in Spark, providing a central and resource management platform to deliver scalable operations across the cluster.

 
 
Q8.  Do you need to install Spark on all nodes of Yarn cluster? Why?

 

Ans. No, because Spark runs on top of Yarn.
 
Q9.  Is it possible to run Apache Spark on Apache Mesos?

 

Ans. Yes.



Q10.  What is lineage graph?

 

Ans. The RDDs in Spark, depend on one or more other RDDs. The representation of dependencies in between RDDs is known as the lineage graph.

 
Q11.  Define Partitions in Apache Spark

 

Ans. Partition is a smaller and logical division of data similar to ‘split’ in MapReduce. It is a logical chunk of a large distributed data set. Partitioning is the process to derive logical units of data to speed up the processing process.

 
Q12.  What is a DStream?

 

Ans. Discretized Stream (DStream) is a sequence of Resilient Distributed Databases that represent a stream of data.

 
Q13.  What is a Catalyst framework?

 

Ans. Catalyst framework is an optimization framework present in Spark SQL. It allows Spark to automatically transform SQL queries by adding new optimizations to build a faster processing system.

 
Q14.  What are Actions in Spark?

 

Ans. An action helps in bringing back the data from RDD to the local machine. An action’s execution is the result of all previously created transformations. 

Q15.  What is a Parquet file?

 

Ans. Parquet is a columnar format file supported by many other data processing systems.
 
Q16.  What is GraphX?

 

Ans. Spark uses GraphX for graph processing to build and transform interactive graphs.
 
Q17.  What file systems does Spark support?

 

Ans. Hadoop distributed file system (HDFS), local file system, and Amazon S3.

Q18.  What are the different types of transformations on DStreams? Explain.

 

Ans.

    Stateless Transformations – Processing of the batch does not depend on the output of the previous batch. Examples – map (), reduceByKey (), filter ().
    Stateful Transformations – Processing of the batch depends on the intermediary results of the previous batch. Examples –Transformations that depend on sliding windows.

 
Q19.  What is the difference between persist () and cache ()?

 

Ans. Persist () allows the user to specify the storage level whereas cache () uses the default storage level.
 
Q20.  What do you understand by SchemaRDD?

 

Ans. SchemaRDD is an RDD that consists of row objects (wrappers around the basic string or integer arrays) with schema information about the type of data in each column.

These are some of the popular questions asked in an Apache Spark interview. Always be prepared to answer all types of questions — technical skills, interpersonal, leadership or methodology. If you are someone who has recently started your career in big data, you can always get certified in Apache Spark to get the techniques and skills required to be an expert in the field.

Q21.What is Apache Spark?

Spark is a fast, easy-to-use and flexible data processing framework. It has an advanced execution engine supporting cyclic data  flow and in-memory computing. Spark can run on Hadoop, standalone or in the cloud and is capable of accessing diverse data sources including HDFS, HBase, Cassandra and others.

Q22. Explain key features of Spark.


    Allows Integration with Hadoop and files included in HDFS.
    Spark has an interactive language shell as it has an independent Scala (the language in which Spark is written) interpreter.
    Spark consists of RDD’s (Resilient Distributed Datasets), which can be cached across computing nodes in a cluster.
    Spark supports multiple analytic tools that are used for interactive query analysis , real-time analysis and graph      processing

Q23. Define RDD?

RDD is the acronym for Resilient Distribution Datasets – a fault-tolerant collection of operational elements that run parallel. The partitioned data in RDD is immutable and distributed. There are primarily two types of RDD:

    Parallelized Collections : The existing RDD’s running parallel with one another.
    Hadoop datasets : perform function on each file record in HDFS or other storage system

Q24. What does a Spark Engine do?

Spark Engine is responsible for scheduling, distributing and monitoring the data application across the cluster.

Q25.Define Partitions?

As the name suggests, partition is a smaller and logical division of data  similar to ‘split’ in MapReduce. Partitioning is the process to derive logical units of data to speed up the processing process. Everything in Spark is a partitioned RDD.

Q26.What operations RDD support?


    Transformations.
    Actions

Q27.What do you understand by Transformations in Spark?

Transformations are functions applied on RDD, resulting into another RDD. It does not execute until an action occurs. map() and filer() are examples of transformations, where the former applies the function passed to it on each element of RDD and results into another RDD. The filter() creates a new RDD by selecting elements form current RDD that pass function argument.

Q28.Define Actions.

An action helps in bringing back the data from RDD to the local machine. An action’s execution is the result of all previously created transformations. reduce() is an action that implements the function passed again and again until one value if left. take() action takes all the values from RDD to local node.

Q29.Define functions of SparkCore?

Serving as the base engine, SparkCore performs various important functions like memory management, monitoring jobs, fault-tolerance, job scheduling and interaction with storage systems.

Q30.What is RDD Lineage?

Spark does not support data replication in the memory and thus, if any data is lost, it is rebuild using RDD lineage. RDD lineage is a process that reconstructs lost data partitions. The best is that RDD always remembers how to build from other datasets.

Q31.What is Spark Driver?

Spark Driver is the program that runs on the master node of the machine and declares transformations and actions on data RDDs. In simple terms, driver in Spark creates SparkContext, connected to a given Spark Master.
The driver also delivers the RDD graphs to Master, where the standalone cluster manager runs.

Q32.What is Hive on Spark?

Hive contains significant support for Apache Spark, wherein Hive execution is configured to Spark:

  hive> set spark.home=/location/to/sparkHome;
  hive> set hive.execution.engine=spark;
  
Q33. Name commonly-used Spark Ecosystems.


    Spark SQL (Shark)- for developers.
    Spark Streaming for processing live data streams.
    GraphX for generating and computing graphs.
    MLlib (Machine Learning Algorithms).
    SparkR to promote R Programming in Spark engine.

Q34. Define Spark Streaming.

Spark supports stream processing – an extension to the Spark API , allowing stream processing of live data streams. The data from different sources like Flume, HDFS is streamed and finally processed to file systems, live dashboards and databases. It is similar to batch processing as the input data is divided into streams like batches.

Q35.What is Spark SQL?

SQL Spark, better known as Shark is a novel module introduced in Spark to work with structured data and perform structured data processing. Through this module, Spark executes relational SQL queries on the data. The core of the component supports an altogether different RDD called SchemaRDD, composed of rows objects and schema objects defining data type of each column in the row. It is similar to a table in relational database.

Q36.List the functions of Spark SQL.?

Spark SQL is capable of:

    Loading data from a variety of structured sources.
    Querying data using SQL statements, both inside a Spark program and from external tools that connect to Spark SQL through standard database connectors (JDBC/ODBC). For instance, using business intelligence tools like Tableau.
    Providing rich integration between SQL and regular Python/Java/Scala code, including the ability to join RDDs and SQL tables, expose custom functions in SQL, and more.


Q37.What are benefits of Spark over MapReduce?


    Due to the availability of in-memory processing, Spark implements the processing around 10-100x faster than Hadoop MapReduce. MapReduce makes use of persistence storage for any of the data processing tasks.
    Unlike Hadoop, Spark provides in-built libraries to perform multiple tasks form the same core like batch processing, Steaming, Machine learning, Interactive SQL queries. However, Hadoop only supports batch processing.
    Hadoop is highly disk-dependent whereas Spark promotes caching and in-memory data storage.
    Spark is capable of performing computations multiple times on the same dataset. This is called iterative computation while there is no iterative computing implemented by Hadoop.

Q38. What is Spark Executor?

When SparkContext connect to a cluster manager, it acquires an Executor on nodes in the cluster. Executors are Spark processes that run computations and store the data on the worker node. The final tasks by SparkContext are transferred to executors for their execution.

Q39.Name types of Cluster Managers in Spark.

The Spark framework supports three major types of Cluster Managers:

    Standalone : a basic manager to set up a cluster.
    Apache Mesos : generalized/commonly-used cluster manager, also runs Hadoop MapReduce and other applications.
    Yarn : responsible for resource management in Hadoop

Q40. What do you understand by worker node?

Worker node refers to any node that can run the application code in a cluster.

Q41.Illustrate some demerits of using Spark.

Since Spark utilizes more storage space compared to Hadoop and MapReduce, there may arise certain problems. Developers need to be careful while running their applications in Spark. Instead of running everything on a single node, the work must be distributed over multiple clusters.

Q42.What is the advantage of a Parquet file? 

Parquet file is a columnar format file that helps –
                Limit I/O operations
                Consumes less space
                Fetches only required columns. 


Q43.What is the difference between persist() and cache()

persist () allows the user to specify the storage level whereas cache () uses the default storage level. 
