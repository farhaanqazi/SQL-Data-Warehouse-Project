
# SQL Data Warehouse Project

## Overview

Welcome to the **SQL Data Warehouse Project**! This repository contains all the resources for setting up a data warehouse designed for business analytics, reporting, and decision-making. The project utilises **Medallion Architecture**, consisting of three layers: **Bronze**, **Silver**, and **Gold**, to organise raw, cleansed, and business-ready data for analysis.

The goal of this project is to create a comprehensive data model and provide detailed insights into business-critical metrics like customer behavior, product performance, and sales trends.

---

## 📊 Objective

The primary objective of this project is to develop a SQL-based solution that enables in-depth analysis of business data to produce valuable insights on:

- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights are essential for empowering stakeholders and enabling strategic decision-making.

---

## 🏗️ Data Architecture

The data architecture follows a **Medallion Architecture** with three layers that structure the data pipeline:

![Data Architecture]

![High Level Data Architecture drawio](https://github.com/user-attachments/assets/3d9089ab-ed0e-48ad-b76e-943109d1acc8)


1. **Bronze Layer**: Raw data from source systems is stored here. Data is ingested into the SQL Server Database from CSV files.
2. **Silver Layer**: This layer involves data cleansing, standardisation, and normalisation to prepare the data for analysis.
3. **Gold Layer**: The final business-ready layer, which contains data modeled into a star schema, optimised for reporting and analytics.

---

## 📂 Repository Structure

Here’s an overview of the repository structure:

```
sql-data-warehouse-project/
│
├── datasets/                           # Raw datasets (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Diagram showing different ETL techniques
│   ├── data_architecture.drawio        # Diagram illustrating project architecture
│   ├── data_catalog.md                 # Catalog of datasets with metadata
│   ├── data_flow.drawio                # Data flow diagram
│   ├── data_models.drawio              # Diagram of the data models (star schema)
│   ├── naming-conventions.md           # Guidelines for consistent naming
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating business models
│
├── tests/                              # Test scripts and quality assurance files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information
├── .gitignore                          # Files and directories ignored by Git
└── requirements.txt                    # Dependencies for the project
```

---

## 📄 Documentation

- **ETL Process**: Detailed documentation on ETL techniques used for extracting, transforming, and loading the data.
- **Data Architecture**: A comprehensive breakdown of the Medallion Architecture, including the Bronze, Silver, and Gold layers.
- **Data Models**: The data models used in this project, especially the star schema, for efficient querying and analysis.
- **Naming Conventions**: Ensures consistency in the naming of tables, columns, and files across the repository.

For more details, refer to the [docs/requirements.md](docs/requirements.md).

---

## 🛠️ Technologies Used

- **SQL Server**: For data storage and processing.
- **ETL Tools**: For extracting and transforming data (SQL scripts).
- **Data Modeling**: Using star schema for efficient reporting and analytics.

---

## 🛡️ License

This project is licensed under the **MIT License**. You are free to use, modify, and share this project with proper attribution. See [LICENSE](LICENSE) for more details.

---

## 🌟 About Me

Hi! I'm **Farhaan Qazi**, a passionate data science and project management enthusiast with a Master's in Data Science from Heriot-Watt University. I aim to bridge the gap between data analysis and actionable insights to drive business decisions.

Feel free to connect with me on the following platforms:

- [LinkedIn](https://www.linkedin.com/in/farhaanqazi)
- [GitHub](https://github.com/farhaanqazi)
- [Portfolio](https://www.farhaanqazi.com)
