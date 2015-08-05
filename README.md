# SparkLyte
##Very light weight aproximation to [Apache Spark](https://spark.apache.org/) without RDD support

SparkLyte provides a highly optimized environment to explore and analyze the data without the overhead of Spark's RDDs (Resilient Data Sets)  and cluster coordination/communication.

Since most of so called "big data" doesn't need a cluster to process and easily fits a good single machine, SparkLyte offers a streamlined environment for your data processing needs.

Once you reach the limits of your hardware, you can go ahead and almost seamessly transition to a full Spark cluster

## Requirements
Any [Scala](wwww.scala-lang.org) distribution 

Disclaimer: this is just a wrapper that does nothing but call the Scala REPL
