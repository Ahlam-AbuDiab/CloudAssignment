# CloudAssignment
# Cloud-Based Distributed Data Processing Service (Apache Spark / Databricks):
A cloud-based data processing service that allows users to upload datasets and run distributed analytics and machine learning tasks using **Apache Spark** on **Databricks**. The program loads data from cloud storage, computes descriptive statistics, runs multiple Spark ML jobs, and displays/exports results.
## Features

### 1) Data Upload & Validation
- Supports uploading datasets (e.g., **CSV**, **JSON**, **Text**).
- Basic validation (file type, empty file check, schema preview).
### 2) Descriptive Statistics (Spark)
The program computes and displays at least 4 statistics such as:
- Number of rows and columns
- Column data types
- Missing/null values percentage per column
- Min/Max/Mean for numeric columns
- Unique value counts (for selected columns)
### 3) Distributed Machine Learning (Spark MLlib)
The program performs machine learning analytics tasks using Spark ML, for example:
- Logistic Regression (classification).
- Linear Regression (prediction).
- KMean Clustring.
- Decision Tree Classifier.
### 4) Results Output
- Results are displayed in the notebook output.
- Outputs I saved it a screenshot in pdf file
## Tech Stack
- **Databricks** (Cloud execution environment)
- **Apache Spark / PySpark**
- **Spark SQL**
- **Spark MLlib**
- Python
