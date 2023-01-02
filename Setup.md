Todays Agenda

1. How to download Spark 
2. how to install spark on Windows
3. Install jdk 8 on Windows
4. How to set path of spark

##-----Java path
JAVA_HOME = C:\Program Files\Java\jdk1.8.0_201


##-----Spark path
SPARK_HOME  = C:\Users\admin\Desktop\spark



5. How to start interactive shell of pyspark 

6. How to run spark on jupyter notebook

command  -->  pip install pyspark

7. Read informtion about current spark running application on web GUI

url access of Spark --> localhost:4040 

8. How to start pyspark session
9. two ways to create session
--------
SparkSession.builder

import pyspark
from pyspark.sql import SparkSession
spark = SparkSession.builder.master("local[1]") \
                    .appName('sessionname1') \
                    .getOrCreate()
-----------------------------------------
--------
SparkSession.newSession.

import pyspark
from pyspark.sql import SparkSession
sparkSession = SparkSession.newSession

-----------------------------------------

How to stop spark session

spark.stop()

10. How to create spark context
---------
from pyspark import SparkContext
sc =SparkContext()
-----------------------------------------

11.How to stop spark context

sc.stop()

12. Methodes of creating rdds in spark

##---parallelize
x = [1,2,3]
y = sc.parallelize(x)


13. Apply transformation and action function on rdd