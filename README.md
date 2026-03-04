**Project Overview**

This project demonstrates basic to intermediate PySpark filtering operations using DataFrames.
The notebook covers how to load data, apply filters using different conditions, and perform data transformations using PySpark.

This project was created for hands-on practice with big data processing concepts.

**Technologies Used**

Python

PySpark

Google Colab

Spark DataFrame API

 **Project Structure**
pyspark-filters-practice/
/README.md
/pyspark_filters1.ipynb
**Setup Instructions**

To run this notebook:

Open the notebook in Google Colab.

Install and configure PySpark (if not already installed).

Run all setup cells (Spark session creation).

Execute the filtering examples step by step.

Example Spark setup:

!pip install pyspark

from pyspark.sql import SparkSession
spark = SparkSession.builder.appName("FiltersPractice").getOrCreate()
 Concepts Covered

**This notebook includes:**

Creating SparkSession

Creating DataFrames

Using filter() and where() functions

Applying single and multiple conditions

**Using logical operators:**

AND (&)

OR (|)

NOT (~)

Filtering using comparison operators:

==

!=

>

<

>=

<=

Filtering using isin()


**Learning Outcome**

After completing this notebook, you will understand:

How to filter large datasets efficiently using PySpark

How Spark processes transformations lazily

How to write clean filtering logic for real-world datasets

**Why This Project?**

This project helps strengthen:

Big Data fundamentals

Spark DataFrame operations

Data engineering basics

Practical PySpark implementation skills
