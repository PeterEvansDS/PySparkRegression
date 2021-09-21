# PySpark Regression

The problem with using standard Python data science libraries like NumPy and Pandas is that they operate in the main memory of the system. This can become a problem when the datasets start getting large, as in common with the advent of big data.

PySpark is the Python interface for Apache Spark, an engine for distributed processing. It enables data science applications to be run on network clusters, thus giving them access to much greater memory and computing power.

This notebook takes a dataset of used car sales (1.45GB) and builds a basic regression model to predict the sales price using PySpark. Although this is not that large, the methods used are as they would be for a much larger dataset.

<div align = center>
  <img src="./images/spark.png" width="350">
</div>
