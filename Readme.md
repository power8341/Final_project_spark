# IMDb Data Analysis with Apache Spark

This project is a comprehensive data analysis of IMDb datasets using Apache Spark, implemented in a Databricks notebook environment.

## 📊 Project Overview

The notebook loads multiple IMDb datasets (in TSV format) from DBFS, performs transformations, and executes insightful queries to explore and understand the data. The project highlights the use of distributed data processing techniques using PySpark.

## 📁 Datasets Used

The following IMDb datasets (TSV files) were used:
- `title.basics.tsv.gz`: Contains information about movies and TV titles.
- `name.basics.tsv.gz`: Information about people (actors, directors, etc.).
- `title.crew.tsv.gz`: Details about directors and writers.
- `title.ratings.tsv.gz`: IMDb ratings for titles.
- `title.principals.tsv.gz`: Principal cast/crew for titles.
- `title.akas.tsv.gz`: Alternate names for titles.
- `title.episode.tsv.gz`: Episode-level details for TV series.

## 🛠️ Technologies

- Apache Spark (PySpark)
- Databricks Platform
- Python
- DBFS (Databricks File System)

## 📌 Key Analyses Performed

1. Loading datasets from DBFS into Spark DataFrames.
2. Counting total number of people in the dataset.
3. Identifying unique actors, directors, and writers.
4. Exploring movie ratings distribution.
5. Analyzing popular genres and title trends.
6. Linking titles with principal cast and crew data.

## ⚙️ How to Run

To run this project:
1. Upload the datasets to DBFS (e.g., `/FileStore/shared_uploads/...`).
2. Import the notebook into your Databricks workspace.
3. Make sure the file paths in the notebook match your DBFS locations.
4. Run the cells sequentially to load and process the data.

## 🧾 Output

The notebook includes a series of Spark SQL and DataFrame operations that output statistics and visualizations (if enabled) directly in the Databricks environment.

## 📚 License

This project is open-source and available under the [MIT License](LICENSE).

---
