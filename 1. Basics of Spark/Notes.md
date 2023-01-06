# getting-stated-with-pyspark
# PySpark


### DAG
Directed Acyclic Graph

Spark created agraph wehn we enter code in spark console <br>
when an action is callled on Spark RDD, Spark submits graph to DAG schedular <btr>
Operations are divided into Stages of task in DAG scheduler <br> 


## Installing PySprk 

1. Preequiste: Java JDK and Pyhton
Check if java is already installed. Do to the cmd (admin): java -version
Get JDK from here: https://www.oracle.com/java/technologies/downloads/#jdk19-windows

2. Download and Install Apache Spark
Get Apache Spark here:  https://spark.apache.org/downloads.html

3. Setting Java and Spark path

-Java path
JAVA_HOME = C:\Program Files\Java\jdk19 

-Spark path 
SPARK_HOME  = C:\Programs\spark-3.3.1-bin-hadoop3

4. Start interactive shell of pyspark 

Go to cmd (admin). Enter command 'pyspark' -- Not working for me. 
Try this:
a. Executing in manually from  C:\Programs\spark-3.3.1-bin-hadoop3\bin\pyspark
or
b. cmd -> cd '%SPARK_HOME% -> bin\pyspark

FYI: Interatice shell is best way to learning. It is not avalible for java. 

Getting Started 

###  Creating session 

import pyspark
from pyspark.sql import SparkSession
from pyspark import SparkContext

-- Starting Spark Context 
sc = SparkContext()
// only one Spark Context at a time
sc.stop()
sc = SparkContext()

Creating RDD 
x = {2,3,4,5,6,7}
rdd.collect() -- To get results. 

--------------------------------------------------------------------------------------------------------------
