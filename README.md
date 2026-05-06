# brazil-ecommerce-data-funnel
This repository contains an end-to-end data analytics pipeline built on a real-world Brazilian e-commerce dataset. The project covers data ingestion, transformation, and visualization to generate actionable business insights using Python, BigQuery, DBT, and Tableau.

🚀 Project Overview

This project simulates a real-world business scenario where a company needs to understand its revenue performance, customer behavior, and operational efficiency.

The goal is to design and implement a complete data workflow that transforms raw transactional data into actionable insights for decision-making.

🎯 Objectives

Build a modern data pipeline from raw data to analytics-ready datasets
Analyze revenue trends, customer behavior, and sales performance
Deliver insights through an interactive Tableau dashboard
Apply best practices in data modeling using DBT
Showcase end-to-end data analytics skills for real business use cases

🧰 Tech Stack

Python → Data ingestion, cleaning, and preprocessing
BigQuery → Cloud data warehouse
DBT → Data transformation and modeling
Tableau → Data visualization and dashboarding
SQL → Analytical queries and data exploration
(Optional) Airflow → Pipeline orchestration

🏗️ Architecture

Raw Data (CSV - Olist Dataset)
        ↓
Python (Cleaning & Preprocessing)
        ↓
Google Cloud Storage
        ↓
BigQuery (Raw Layer)
        ↓
DBT (Staging → Intermediate → Marts)
        ↓
Analytics Tables
        ↓
Tableau Dashboard

📂 Repository Structure

brazil-ecommerce-data-funnel/
│
├── data/                # Raw and processed datasets
├── notebooks/           # Python EDA & analysis
├── sql/                 # Analytical queries
├── dbt_project/         # DBT models
│   ├── staging/
│   ├── intermediate/
│   └── marts/
├── dags/                # Airflow DAGs (optional)
├── tableau/             # Dashboard assets/screenshots
├── images/              # README visuals
└── README.md

📈 Key Business Questions

How is revenue evolving over time?
Which customers generate the highest value?
What factors impact delivery performance?
How does customer behavior influence repeat purchases?
Which regions and sellers drive the most revenue?

📊 Dashboard Features

Revenue trends (daily / monthly)
Customer segmentation (RFM)
Sales performance by region and category
Delivery time analysis
Customer satisfaction insights

🔍 Key Insights (example — cámbialo luego)

A small percentage of customers drives a large portion of total revenue
Delivery delays negatively impact customer satisfaction
Certain regions show higher repeat purchase rates
Revenue growth is concentrated in specific product categories

🧠 What I Learned

Designing scalable data models using DBT
Building cloud-based data pipelines with BigQuery
Translating business questions into analytical queries
Creating impactful dashboards for stakeholders

📌 Future Improvements

Add revenue forecasting using Python
Implement automated pipelines with Airflow
Enhance customer segmentation with machine learning
Optimize query performance in BigQuery
📎 Dataset
Source: Olist Brazilian E-commerce Dataset (Kaggle)
