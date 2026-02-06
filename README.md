# Sales Analytics - Automated Data Pipeline

An automated sales analytics system built on cloud infrastructure that processes retail sales data through ETL workflows and delivers insights via interactive dashboards and executive reports.

## Overview

This project demonstrates a complete data pipeline architecture. Raw sales data stored in AWS S3 flows through Alteryx for automated cleaning and transformation, loads into MySQL for storage, and feeds both Tableau dashboards and SSRS reports. The system handles data from an online superstore covering 2014-2017 transactions.

## Architecture
```
AWS S3 → Alteryx ETL → MySQL → Tableau Dashboard
                              → SSRS Reports
```

## Technologies

- **AWS S3** - Cloud storage with versioning and lifecycle policies
- **Alteryx Designer** - ETL automation and data transformation
- **MySQL** - Relational database
- **Tableau** - Interactive visualization
- **SSRS** - Executive reporting

## Key Features

The pipeline performs:
- Multi-source data integration (orders, returns, regional data)
- Automated data cleaning and quality checks
- Business calculations (profit margins, return flags, processing times)
- Dual output for different stakeholder needs

## Business Insights

- Total revenue: $2.3M across analysis period
- Regional breakdown: Central ($501K), East ($679K), West ($726K), South ($392K)
- Top categories: Accessories, Binders, Paper
- Overall profit: $286K with healthy margins

## Project Structure
```
├── data/               # Raw and processed files
├── alteryx/            # ETL workflow files
├── sql/                # Database schema and queries
├── tableau/            # Dashboard files
├── ssrs/               # Report templates
└── screenshots/        # Documentation
```

## What This Demonstrates

Cloud-based data architecture  
ETL workflow automation  
Database design and optimization  
Interactive and static reporting  
End-to-end pipeline thinking  
