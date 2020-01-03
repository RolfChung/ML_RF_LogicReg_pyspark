# ML_RF_LogicReg_pyspark
MachineLearning (Random Forest, XGboost, logistic regression, cross validation) wit Pyspark of Apache Spark.

# Summary

<p>
This project is doing explorative data analysis using the pyspark and sql application programming interfaces (API's) of Apache spark.
</p> 

<p>
Apache Spark is an open-source engine developed specifically for handling large-scale data processing and analytics. Spark offers the ability to access data in a variety of sources. Apache Spark is designed to accelerate analytics on Hadoop with speed and efficiency.
</p> 
<a href="https://www.webopedia.com/TERM/A/apache-spark.html" target="_blank">webopedia</a> 

<p>
The airtraffic system data records consist of the tables flights, planes,
and airports. The data sources used  are csv-files stored locally. 
The functions and methods applied here include SQL-queries and
SQL-calculations and pyspark implementations like select, filter,
collect, join, and aggregate. 
</p> 

<p>
Those can of course applied to Big Data on remote machines. This is the whole point of the Apache Spark system architecture. It allows even analysing streaming data in real time. The Spark master distributes then the data as Resilient Distributed Datasets (RDD) or immutable distributed collections of objects on the remote machines (workers) using a process of mapping, sort and shuffle, and reducing. RDD's are not generated in this project, but are in others.
</p> 



<img src="spark_architecture.jpg" alt="Smiley face" align="left"  style="margin-left: 0px; margin-right: 0px; margin-top: 20px; margin-bottom: 20px; float: left; width: 800px; height: 300px"> 

<p>
The main focus of this project is prepare the data for machine learning for example by:
</p>

<ul>
  <li>joining</li>
  <li>creating labels</li>
  <li>cleaning missing values</li>
  <li>doing a train-test-split</li>
</ul> 


<p>    
and then apply Pyspark ML library alogrithms like:
</p> 

<ul>
  <li>Random Forest</li>
  <li>Random Forest in cross-validation</li>
  <li>Logistic Regression in cross-validation</li>
  <li>Gradient-Boosted Tree Classifier</li>
</ul> 
