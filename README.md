# Products and Orders Project
Project Overview

This project explores customer purchasing behavior using the Order dataset. The objective is to understand ordering patterns, product popularity, reorder behavior, and data quality issues through Exploratory Data Analysis (EDA).

Dataset Description

The analysis uses the following datasets:

Orders
Products
Aisles
Departments
Order-Product Relationships

These datasets were merged to create a comprehensive view of customer purchases and product characteristics.

Objectives
Understand the structure and quality of the data
Identify missing values and duplicate records
Validate duplicate observations before removal
Analyze product ordering frequency
Investigate customer reorder behavior
Explore relationships between departments, aisles, and products
Visualize insights using Plotly
Data Preparation
Data Merging

Multiple datasets were combined using outer joins to preserve all available information and investigate unmatched records.

Data Quality Assessment

The following checks were performed:

Dataset shape inspection
Data type verification
Missing value analysis
Duplicate detection
Duplicate validation
Duplicate removal when appropriate
Missing Value Investigation

Rather than immediately removing missing values, their causes were investigated to determine whether they represented genuine business scenarios or data quality issues.

Exploratory Data Analysis

The analysis included:

Product Analysis
Most frequently ordered products
Distribution of product orders
Product popularity ranking
Reorder Analysis
Reorder frequency by product
Proportion of reordered items
Customer purchasing patterns
Department Analysis
Most popular departments
Product distribution across departments
Aisle Analysis
Most active aisles
Product concentration by aisle
Visualizations

Interactive Plotly visualizations were created to explore:

Product popularity
Department performance
Aisle distributions
Reorder behavior
Frequency distributions
Key Findings
Certain products dominate customer purchases.
Reordering behavior is concentrated among frequently purchased products.
Product demand varies significantly across departments and aisles.
