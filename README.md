# Analyzing Uber Data Using GCP, Python, and Power BI: A Comprehensive Study
![data-analysis](https://github.com/parthdacoder/Uber-Data-Analysis/assets/88302656/63946301-ce51-4fa3-a171-acc753b9b8c0)

Authors: Parth Madaan, Palak Sahu

## Introduction
This project focuses on analyzing Uber's public datasets using a combination of cloud technology and data analytics tools. By leveraging Google Cloud Platform (GCP), Python, Mage Data Pipeline Tool, BigQuery, and Looker Studio, we aim to uncover hidden patterns and trends to facilitate strategic decision-making.

## 1. Objective of the Project
The main objective of this project is to utilize cloud technology and data analytics to explore and gain insights from Uber's public datasets. By employing GCP, Python, Mage Data Pipeline Tool, BigQuery, and Looker Studio, we aim to reveal valuable patterns and trends that can inform strategic decision-making processes.

## 2. Data Overview
The Uber dataset used in this project consists of millions of Uber pickups in New York City over a specific period. The dataset includes variables such as date/time, pickup location, and other ride-related details, which will be analyzed to extract meaningful insights.

## 3. Technologies Used
This project employs various technologies to analyze the Uber data effectively:
- Google Cloud Platform (GCP) for cloud infrastructure and services.
- Python for data manipulation and analysis.
- Mage Data Pipeline Tool for Extract, Transform, Load (ETL) processes.
- BigQuery for data storage and querying.
- Power BI for data visualization and creating interactive dashboards.

## 4. Project Overview
The project workflow can be summarized as follows:
1. Data Modeling: Designing a schema using Lucidchart to create fact and dimension tables, enabling efficient querying and aggregation.
2. Implementing the Schema: Uploading the data to GCP and aligning the data structure with the Lucidchart model using Python and GCP tools.
3. Data Ingestion and Storage: Uploading the Uber dataset to Google Cloud Storage, which provides durable and scalable object storage.
4. ETL Pipeline: Deploying Mage on the Google Compute Engine API to handle large-scale data processing tasks efficiently. Extracting, transforming, and loading the data into BigQuery for further analysis.
5. Data Cleansing in BigQuery: Uploading the transformed data into BigQuery, performing data cleansing operations such as handling missing data, removing duplicates, and standardizing data formats.
6. Data Visualization with Looker Studio and Power BI: Utilizing Looker Studio's features to create interactive dashboards and visualizations, providing detailed insights into the analyzed Uber data.
7. Conclusion: Summarizing the project, highlighting key insights and findings, and discussing potential future enhancements.

## 5. Conclusion
This project showcases the power of cloud computing and data analytics tools in analyzing large datasets. By exploring Uber's public datasets, valuable insights such as peak ride times and high-demand locations were uncovered, which can potentially assist Uber in optimizing driver allocation and improving service efficiency. Future iterations of this project can include additional data sources, such as weather or event data, to uncover more nuanced patterns and trends. Furthermore, incorporating machine learning algorithms for predictive analysis can enhance the project's capabilities.
