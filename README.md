Overview
This project analyzes retail inventory performance using Python to uncover overstock risk, stockout risk, and opportunities for optimizing replenishment decisions. Using a synthetic dataset modeled after real retail operations, the project applies forecasting, inventory metrics, and visualizations to generate insights that help reduce costs and improve product availability.

Project Goals
Predict product demand using simple forecasting techniques
Identify overstock and stockout patterns
Build an automated inventory risk classification system
Create visual dashboards for quick decision-making
Provide business-ready insights for inventory optimization

Methods & Steps
1. Data Cleaning & Preparation
Loaded the dataset using pandas
Checked for missing values, duplicates, and inconsistent fields
Created additional fields such as:
Weeks of Supply
Lead-Time Risk
Overstock / Stockout Units
Risk_Category (classification)
