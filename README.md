# Iris Dataset Analysis with Apache Spark

This project demonstrates the use of **Apache Spark** and **PySpark** for processing and analyzing the Iris dataset. The main objectives are:

- Learn **MapReduce** operations with Spark RDDs
- Implement **Machine Learning** (Decision Tree Classifier) using PySpark MLlib
- Apply **SQL queries** on Spark DataFrames
- Gain practical experience with distributed data processing

## 📁 Dataset

The dataset used is the classic [Iris Dataset](https://www.kaggle.com/datasets/uciml/iris) from Kaggle.  
It contains 150 samples with 4 features each (sepal length, sepal width, petal length, petal width) and a target column (`Species`).


## 🚀 Features & Implementations

### 1. MapReduce
- Count the number of samples per species using RDD operations
- Key functions: `map()`, `reduceByKey()`, `filter()`

### 2. Machine Learning
- Multi-class classification problem
- Algorithm: **Decision Tree Classifier**
- Feature engineering: `VectorAssembler` for input features, `StringIndexer` for label encoding
- Metric: Accuracy

### 3. SQL Analysis
- Perform SQL queries on Spark DataFrames
- Examples: `SELECT *`, `WHERE`, `AVG()`, `GROUP BY`

---

## 📌 How to Run

1. Install **Apache Spark** and **PySpark** in your environment.
2. Download the `iris.csv` dataset into your working directory.
3. Open the corresponding Jupyter notebooks (`.ipynb`) and run cells sequentially.
4. For SQL analysis, use `spark.sql()` after creating a DataFrame and registering it as a temp view.

---

## ⚡ Requirements

- Python 3.12.3
- Apache Spark 3.5.3
- PySpark
- Jupyter Notebook
- Ubuntu

## 📝 Notes

- The project was done as part of a course assignment to learn Spark’s core functionality.
- MapReduce implementation shows **parallel processing using RDDs**.
- Machine learning part demonstrates **classification using Decision Trees**.
- SQL part shows how to query Spark DataFrames efficiently.

## 📚 References
- [Iris Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/iris)
- [Apache Spark Official Documentation](https://spark.apache.org/docs/latest/)
- [PySpark MLlib Guide](https://spark.apache.org/docs/latest/ml-guide.html)


## 👩‍💻 Author
**Nur Hayat Yavuz**  
Computer Engineering Graduate |  MSc in Intelligent Systems Engineering   
[GitHub](https://github.com/ynurhayatyavuz)

