# Movie Data Analysis with PySpark

A big data analytics project that explores movie trends and popularity using **PySpark**, **Spark SQL**, **Docker**, and **Hadoop**. The project demonstrates distributed data processing, exploratory data analysis, SQL-based analytics, and machine learning techniques on a real-world movie dataset.

---

## Project Overview

This project analyses movie datasets to identify trends in movie popularity, ratings, genres, and runtime. It combines distributed computing with machine learning techniques to extract meaningful insights from large-scale data.

The project covers:

- Data cleaning and preprocessing
- Distributed data processing using PySpark
- SQL analysis using Spark SQL
- Exploratory Data Analysis (EDA)
- Linear Regression
- K-Means Clustering
- Data visualisation

---

## Technologies

- Python
- PySpark
- Spark SQL
- Hadoop HDFS
- Docker
- Pandas
- Matplotlib
- Scikit-learn

---

## Repository Structure

```text
movie-data-analysis-pyspark
│
├── notebooks/
│   └── Movie_Data_Analysis.ipynb
│
├── data/
│   ├── data.csv
│   └── movies_tmdb_popular.csv
│
├── docker/
│   ├── docker-compose.yml
│   └── docker_command.txt
│
├── images/
│
├── requirements.txt
└── README.md
```

---

## Dataset

This project uses publicly available movie datasets including:

- TMDB Movie Dataset
- Movie metadata used for Spark SQL analysis

---

## Project Workflow

```text
Load Data
      │
      ▼
Data Cleaning
      │
      ▼
Spark SQL Analysis
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Linear Regression
      │
      ▼
K-Means Clustering
      │
      ▼
Visualisation
```

---

## Key Features

- Built a distributed analytics workflow using Docker and Hadoop.
- Performed large-scale movie data processing with PySpark.
- Used Spark SQL for querying and aggregating movie information.
- Applied Linear Regression to analyse relationships between movie variables.
- Applied K-Means clustering to identify movie groups.
- Generated visualisations to support data-driven insights.

---

### Option 1 – Local Python Environment

```bash
pip install -r requirements.txt
```

### Option 2 – Docker Environment

The project also includes a Docker Compose configuration for running a Hadoop and Spark cluster.

```bash
docker compose up
```

## Future Improvements

- Hyperparameter optimisation
- Additional machine learning models
- Interactive dashboards
- Deployment using Apache Spark Cluster

---

## Author

YuPeng Tang
