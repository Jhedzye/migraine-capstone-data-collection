# Capstone Project – Step 2: Data Collection  
Machine Learning Engineering Bootcamp  
UMass Global | Jhedzye

## Overview

This repository contains the datasets, code, and documentation for Step 2 of the Capstone project. The goal was to collect and explore relevant datasets for a machine learning use case focused on operations efficiency and decision-making. Two datasets were selected based on relevance to supply chain and productivity analysis.

## Datasets Explored

### 1. Worker Productivity Dataset
- Source: Kaggle - Multi-category E-commerce Behavior  
  https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store
- Original Size: Over 8 million rows (~8GB uncompressed)
- Current Size Used: 1,099 rows (subset for exploration)
- Purpose: Used to simulate worker productivity by analyzing user activity sequences, session timing, and top performers based on event frequency.
- File: `worker_productivity_data.csv`

### 2. Shipment and Delivery Dataset
- Source: Kaggle - Customer Analytics (Train.csv)  
  https://www.kaggle.com/datasets/prachi13/customer-analytics
- Size: 10,999 records
- Purpose: Used to explore delivery delay patterns based on shipment method, weight, discount, and customer interaction.
- File: `Train.csv`

## Data Collection Process

Both datasets were collected from Kaggle using publicly available sources. The e-commerce dataset was downloaded in full and then trimmed to a focused subset for performance and clarity during initial exploration. The shipment dataset was used as-is. The code for data loading, cleaning, and exploration is included in the notebook.

## Files in This Repository

- `Mini_Project-4.ipynb`: Jupyter Notebook with data loading, cleaning, visualizations, and summary insights.
- `worker_productivity_data.csv`: Trimmed sample of large e-commerce user behavior dataset.
- `Train.csv`: Shipment and logistics dataset with delivery performance features.
- `README.md`: Project documentation and dataset details.

## Summary

The datasets chosen are relevant to business operations, fulfillment efficiency, and behavioral analysis. This step demonstrates the ability to collect large datasets, trim and explore them, and prepare for further modeling and analysis in later steps of the capstone project.
