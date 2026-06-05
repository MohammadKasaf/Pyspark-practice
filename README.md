# PySpark Practice Repository

This repository contains PySpark concepts and hands-on practice exercises organized from beginner to advanced level. The goal is to build a strong foundation in PySpark, Data Engineering, and Databricks through practical examples and projects.

## Folder Structure

```text
pyspark-practice/
│
├── 01_spark_basics
│   ├── What is Apache Spark?
│   ├── Spark Architecture
│   ├── Driver & Executors
│   ├── SparkSession
│   ├── RDD vs DataFrame vs Dataset
│   └── Basic Transformations & Actions
│
├── 02_dataframe_creation
│   ├── Create DataFrames
│   ├── Schema Definition
│   ├── Infer Schema
│   ├── Explicit Schema
│   └── Sample Data Generation
│
├── 03_reading_files
│   ├── CSV
│   ├── JSON
│   ├── Parquet
│   ├── Delta
│   ├── Text Files
│   └── Reading Options
│
├── 04_select_filter
│   ├── select()
│   ├── filter()
│   ├── where()
│   ├── distinct()
│   ├── dropDuplicates()
│   └── Conditional Filtering
│
├── 05_withcolumn
│   ├── withColumn()
│   ├── when() & otherwise()
│   ├── Column Transformations
│   ├── Derived Columns
│   └── Renaming Columns
│
├── 06_aggregations
│   ├── groupBy()
│   ├── agg()
│   ├── sum()
│   ├── avg()
│   ├── min()
│   ├── max()
│   └── count()
│
├── 07_joins
│   ├── Inner Join
│   ├── Left Join
│   ├── Right Join
│   ├── Full Join
│   ├── Cross Join
│   └── Self Join
│
├── 08_window_functions
│   ├── Window Specification
│   ├── row_number()
│   ├── rank()
│   ├── dense_rank()
│   ├── lead()
│   ├── lag()
│   └── Running Aggregations
│
├── 09_user_defined_functions
│   ├── UDF Basics
│   ├── Python UDF
│   ├── Pandas UDF
│   ├── Scalar UDF
│   └── Performance Considerations
│
├── 10_null_handling
│   ├── isNull()
│   ├── isNotNull()
│   ├── fillna()
│   ├── dropna()
│   └── replace()
│
├── 11_date_functions
│   ├── current_date()
│   ├── current_timestamp()
│   ├── datediff()
│   ├── date_add()
│   ├── date_sub()
│   └── Date Formatting
│
├── 12_string_functions
│   ├── upper()
│   ├── lower()
│   ├── trim()
│   ├── concat()
│   ├── substring()
│   └── regexp_replace()
│
├── 13_array_functions
│   ├── array()
│   ├── explode()
│   ├── size()
│   ├── array_contains()
│   └── Array Transformations
│
├── 14_struct_functions
│   ├── struct()
│   ├── Nested Columns
│   ├── Access Struct Fields
│   └── Struct Manipulation
│
├── 15_json_processing
│   ├── Parse JSON
│   ├── from_json()
│   ├── to_json()
│   ├── Nested JSON
│   └── JSON Schema Handling
│
├── 16_partitioning
│   ├── Partition Concepts
│   ├── repartition()
│   ├── coalesce()
│   ├── Partition Pruning
│   └── Performance Tuning
│
├── 17_caching
│   ├── cache()
│   ├── persist()
│   ├── Storage Levels
│   └── Performance Optimization
│
├── 18_broadcast_join
│   ├── Broadcast Variables
│   ├── Broadcast Joins
│   ├── Join Optimization
│   └── Shuffle Reduction
│
├── 19_delta_lake
│   ├── Delta Tables
│   ├── ACID Transactions
│   ├── Time Travel
│   ├── Merge
│   ├── Update
│   ├── Delete
│   └── Optimize
│
├── 20_medallion_architecture
│   ├── Bronze Layer
│   ├── Silver Layer
│   ├── Gold Layer
│   ├── Data Quality
│   ├── ETL Pipelines
│   └── Best Practices
│
├── 21_streaming
│   ├── Structured Streaming
│   ├── Streaming Sources
│   ├── Watermarking
│   ├── Checkpointing
│   ├── Trigger Types
│   └── Streaming Aggregations
│
├── 22_optimization
│   ├── Catalyst Optimizer
│   ├── Tungsten Engine
│   ├── Predicate Pushdown
│   ├── Partition Pruning
│   ├── AQE
│   └── Query Optimization
│
├── 23_unity_catalog
│   ├── Catalogs
│   ├── Schemas
│   ├── Tables
│   ├── Permissions
│   ├── Data Governance
│   └── Lineage
│
├── 24_interview_questions
│   ├── PySpark Interview Questions
│   ├── Spark Architecture
│   ├── Optimization Scenarios
│   ├── Delta Lake Questions
│   └── Databricks Questions
│
└── 25_projects
    ├── ETL Pipeline Project
    ├── Sales Analytics Project
    ├── Customer Analytics Project
    ├── Streaming Project
    ├── Delta Lake Project
    └── End-to-End Data Engineering Project
```

## Learning Path

1. Spark Fundamentals
2. DataFrame Operations
3. Data Transformations
4. Advanced Transformations
5. Performance Optimization
6. Delta Lake & Databricks
7. Streaming Pipelines
8. Production Data Engineering Projects

By the end of this repository, you will have covered PySpark concepts from beginner to advanced level along with practical Data Engineering use cases and real-world projects.
