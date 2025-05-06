# music_the_brain
This project simulates a complete data pipeline for building a music recommendation system, showcasing skills in data engineering, machine learning, and cloud infrastructure (AWS).
# Music Recommendation Pipeline

This project simulates a complete data pipeline for building a music recommendation system, showcasing skills in data engineering, machine learning, and cloud infrastructure (AWS).

> Technologies: PySpark, AWS (S3, Glue, Redshift, QuickSight), Python, Collaborative Filtering

---

## Project Overview

The goal is to simulate a user-song interaction dataset, build an ETL pipeline using PySpark, train a recommendation model, load the data into Redshift, and create an interactive dashboard with AWS QuickSight.

---

## Project Structure

music-recommendation-pipeline/
│
├── data/
│ ├── raw/ # Synthetic CSV data
│ └── processed/ # Cleaned and transformed data
│
├── notebooks/
│ ├── EDA.ipynb # Exploratory data analysis
│ └── recommendation.ipynb # ALS collaborative filtering model
│
├── spark_jobs/
│ ├── etl_job.py # PySpark ETL job
│ └── load_to_redshift.py # Redshift loading script (optional)
│
├── dashboard/
│ └── quicksight_design.md # Dashboard design and screenshots
│
├── scripts/
│ └── simulate_data.py # Script to generate synthetic user-song data
│
├── requirements.txt
├── config/
│ └── aws_config.env # AWS credentials & Redshift parameters
