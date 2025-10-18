# Big Data Analytics: Naukri Job Postings Analysis

##  Project Overview

This project implements a large-scale Big Data Analytics pipeline to extract and analyze trends from over **260k+ job postings** scraped from Naukri.com. Utilizing technologies like **PySpark, Hadoop (conceptual), and Natural Language Processing (NLP)**, the system processes massive unstructured data to deliver critical insights into the Indian job market, specifically focusing on data and technology roles.

The primary goal was to process massive data efficiently and generate keyword clouds and hiring trend reports for **data-driven market visualization**.

## Key Achievements

* **Large-Scale Processing:** Developed a system using **PySpark** and **Hadoop** principles to efficiently process **260K+** job postings.
* **Deep Insights:** Extracted valuable, market-relevant insights on **in-demand skills, typical salary ranges, necessary qualifications, and location-based hiring trends**.
* **NLP for Analysis:** Employed NLP techniques to analyze job descriptions and generate visualizations like **keyword clouds** to highlight prominent skills.

## TechStack

| Category | Tools / Libraries | Purpose |
| :--- | :--- | :--- |
| **Big Data Processing** | **PySpark** | Distributed and scalable processing of all job records. |
| **Data Scraping** | Python, Selenium | Automated extraction of raw job posting data. |
| **Analysis** | NLP (Text Preprocessing) | Extraction and tokenization of in-demand skills from text data. |
| **Visualization** | Matplotlib, Seaborn | Generating trend reports, salary plots, and bubble charts for market visualization. |

##  Repository Structure & Analysis Pipeline

The analysis is broken down into three stages, covered by the Jupyter Notebooks:

1.  ### `naukriscrape3.ipynb` (Data Collection)
    * **Function:** Contains the Python/Selenium logic for the initial web scraping of job posting data.

2.  ### `PreprocessingBDA.ipynb` (Data Cleaning & Preparation)
    * **Function:** Focuses on essential data cleaning tasks, including standardizing fields, handling missing values, and preparing text data for NLP.

3.  ### `BDAtext spark+visualisation.ipynb` (Big Data Analysis & Reporting)
    * **Function:** The core analytics stage where **PySpark** is initialized to perform large-scale analysis, including skills extraction and trend visualization.

## Viewing Visualizations and Results

To view all generated visualizations (keyword clouds, bubble charts, salary distribution plots, etc.) and the detailed step-by-step analysis:

###  Recommended Method (Download & Run)

1.  **Clone or Download** the entire project repository.
2.  Ensure you have **Python, Jupyter, and PySpark** environments configured.
3.  Open the notebooks (especially `BDAtext spark+visualisation.ipynb`) and run them sequentially to replicate the analysis and generate the final reports.

###  Quick Preview (View on GitHub)

* You can click on the Jupyter Notebook files (`.ipynb`) directly on GitHub to view a static rendering of the code, markdown, and **most of the final output visualizations**.
* *Note: Interactive elements or visualizations generated with libraries requiring a live kernel may not render properly in the static GitHub preview.*
