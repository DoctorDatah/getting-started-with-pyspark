
#  PySpark Basics
Apache Spark is an open-source parallel processing framework that supports in-memory processing to boost the performance of applications that analyze big data. Big data solutions are designed to handle data that is too large or complex for traditional databases.
# Components Of Spark
- Core Spark
- Spark SQL
- Spark Streaming
- Mlib
- GraphX
- SparkR
    
# Interactive Shell
Spark's shell provides a simple way to learn the API, as well as a powerful tool to analyze data interactively. It is available in Scala , R and Python

## Directed Acyclic Graph
Apache Spark DAG allows the user to dive into the stage and expand on detail on any stage. In the stage view, the details of all RDDs belonging to that stage are expanded. The Scheduler splits the Spark RDD into stages based on various transformation applied.

- DAG Scheduler
- Task Sheduler
- Stages
- Executer

## Resilient Distributed Dataset

RDD is a logical reference of a dataset which is partitioned across many server machines in the cluster. RDDs are Immutable and are self recovered in case of failure.
​
# Spark Architecture 
- Spark Context
- Cluster Manager
- Master Node
- Worker Node
- Jobs

​
# Featuers Of Spark

- Fault Tolerance
- Speed
- Reusability
- In memory Computation
- Lazy Evalutation
 
# Domains of Spark Application

- Banking
- Healthcare
- E-Commerce
- Telecome

​
# Support Platform for running Spark Application
- OS:- Linux , Windows and Mac.
- Cloud :- AWS, Google cloud and Azure

# Install JDK 8 in  Windows download from below link
- https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html

# Download Spark from below Link

- https://downloads.apache.org/spark/spark-3.2.1/spark-3.2.1-bin-hadoop3.2.tgz

# Install Spark on Windows 
- Follow the instructions from steps.txt file

# Install pyspark On  Jupyter Notebook

    !pip install pyspark 

# Start Session In pyspark
- Ways of start session in pyspark
- Follow the instructions from steps.txt file

# Code Description
    File Name : pyspark.ipynb, pyspark.py
    DataSets : airlines1.csv
    File Description : Import pyspark, Create Spark Context and Create RDDs.
    
## Steps to Run
There are two ways to execute the end to end flow.
- Command Prompt => python script
- spark_path spark-submit file_path
- spark_path => <path_to_spark>>
- file_path => <path_to_file>
- Data file path is same as script file path

eg. <C:\Users\admin\Desktop\spark\bin>spark-submit C:\Users\admin\Desktop\RDDs\pyspark.py>
- IPython
### Modular code
- Create virtualenv
- Install requirements `pip install -r requirements.txt`
- Run Code `python pyspark.py`
- Check output for all the visualization
### IPython
Follow the instructions in the notebook `pyspark.ipynb`

 
