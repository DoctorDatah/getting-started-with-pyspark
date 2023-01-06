
#  Resilient Distributed Datasets
Resilient Distributed Datasets (RDD) is a fundamental data structure of Spark. It is an immutable distributed collection of objects. Each dataset in RDD is divided into logical partitions, which may be computed on different nodes of the cluster.

# Ways Of Data Processing in spark
- In-Memory Computation
- Batch Data Processing

    
# Distribution 
Distribution of data across multiple nodes

## Architecture of Directed Acyclic Graph

- DAG Scheduler
- Task Sheduler
- Stages
- Executer

# Operations In Spark
- Transformation
- Action

# Business Overview Of Airlines Industry

- https://openflights.org/
- https://developer.ibm.com/exchanges/data/all/airline/
- https://www.bts.dot.gov/topics/airlines-and-airports/quick-links-popular-air-carrier-statistics

 
# Code Description
    File Name : pyspark.ipynb , airlines.ipynb, pyspark.py and airlines.py
    DataSets : airlines1.csv
    File Description : Implement Transformations and Actions Functions on RDD
    
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
- Run Code `python airlines.py`
- Check output for all the visualization
### IPython
Follow the instructions in the notebook `pyspark.ipynb`
Follow the instructions in the notebook `airlines.ipynb`

 
