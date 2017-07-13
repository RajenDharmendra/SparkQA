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
