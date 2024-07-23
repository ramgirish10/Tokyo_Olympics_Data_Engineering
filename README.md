# 🏅 Tokyo 2021 Olympics Data Engineering Project

## 📝 Overview
This project is focused on analyzing data from the 2021 Tokyo Olympics. Utilizing Azure services, we ingest, transform, and analyze the data to generate insightful visualizations. The dataset includes details of over 11,000 athletes, 47 disciplines, and 743 teams, along with entries by gender and coach information.

## 📊 Architecture
The architecture for this project is as follows:

![Architecture Diagram](data/architecture_diagram.png)

### Components
- **Data Source**: Raw data from the 2021 Tokyo Olympics.
- **Data Factory**: Integrates and orchestrates data workflows.
- **Data Lake Gen 2 (Raw Data Store)**: Stores raw data.
- **Azure Databricks**: Transforms and processes data.
- **Data Lake Gen 2 (Transformed Data Store)**: Stores transformed data.
- **Azure Synapse Analytics**: Performs data analytics and reporting.
- **Visualization Tools**: Power BI, Looker Studio, and Tableau for dashboard creation and data visualization.

## 🛠️ Tools and Steps

### Data Ingestion
- **Azure Data Factory**: Ingests raw data from the Tokyo Olympics dataset and stores it in Data Lake Gen 2.

### Data Transformation
- **Azure Databricks**: Transforms raw data into a structured format suitable for analysis. The transformed data is then stored back in Data Lake Gen 2.

### Data Analysis
- **Azure Synapse Analytics**: Executes complex queries and analytics on the transformed data to generate insights.

### Data Visualization
- **Power BI / Looker Studio / Tableau**: Connect to Azure Synapse Analytics to create interactive dashboards and visualizations.

## 📊 Dataset Details
- **Source**: [Tokyo 2021 Olympics Dataset on Kaggle](https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo)
- **Contents**:
  - Athlete details (names, countries represented, disciplines, gender).
  - Coach details (names, teams, countries represented).
  - Team details (names, countries represented, disciplines).
  - Entries by gender.

The dataset will be updated with details about medals (gold, silver, bronze) and more athlete details in the future.

## 🔗 Additional Resources
- **Azure Data Factory Documentation**: [Link](https://docs.microsoft.com/en-us/azure/data-factory/)
- **Azure Databricks Documentation**: [Link](https://docs.microsoft.com/en-us/azure/databricks/)
- **Azure Synapse Analytics Documentation**: [Link](https://docs.microsoft.com/en-us/azure/synapse-analytics/)
- **Power BI Documentation**: [Link](https://docs.microsoft.com/en-us/power-bi/)

## 📝 Conclusion
This project sets up a comprehensive data pipeline using Azure services for ingesting, transforming, analyzing, and visualizing Tokyo 2021 Olympics data. The setup enables users to gain insights and create detailed reports and dashboards to understand the athletes' performances, team compositions, and other critical aspects of the Olympics.

## 📷 Architecture Diagram
![Azure Olympics Data Architecture](data/architecture_diagram.png)
