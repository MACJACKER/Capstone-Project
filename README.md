# Capstone-Project
Project Overview
This repository contains the analysis and predictive modeling of SpaceX Falcon 9 rocket launch success rates. The primary goal was to predict the likelihood of successful first-stage landings based on historical launch data. This analysis is crucial as reusable rockets, such as Falcon 9's first stage, play a pivotal role in reducing space travel costs, making the accurate prediction of their landing outcomes valuable for future missions.

Data Collection
The data was sourced from the SpaceX API and enriched through additional web scraping techniques to gather comprehensive details about past Falcon 9 launches. Key data points included rocket specifications, payload masses, launch outcomes, and more. Data wrangling efforts were applied to clean and format the data appropriately for analysis.

Exploratory Data Analysis (EDA)
Through various data visualization tools, the project explored relationships between multiple variables such as payload mass, launch site, and flight number, revealing insights into factors that influence launch success. This exploratory phase was crucial in understanding the data's distribution and underlying patterns before applying any predictive models.

Predictive Modeling
Several machine learning models, including Logistic Regression, Support Vector Machines, Decision Trees, and K-Nearest Neighbors, were trained on the dataset to predict the first stage landing success. Model performance was evaluated based on their accuracy, sensitivity, and specificity, using a split of 80% training data and 20% testing data.

Interactive Dashboard and Visualizations
The project features an interactive dashboard built with Plotly Dash, which dynamically displays the success and failure rates of launches and visualizes how different factors affect launch outcomes. This tool serves as both an analytical instrument for deeper insights and a practical demonstration of the data's applications.

Repository Structure
Data/: Contains all datasets used and generated during the project.
Notebooks/: Jupyter notebooks detailing the data collection, cleaning, EDA, and modeling phases.
Scripts/: Python scripts for automated data collection and processing.
README.md: Project overview, setup instructions, and usage guide.
This project is designed to be a comprehensive analysis suite for SpaceX Falcon 9 launch data, providing all necessary tools and documentation for replicating the analysis or extending it further.
