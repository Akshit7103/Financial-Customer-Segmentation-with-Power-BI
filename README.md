# InsightMax: Financial Customer Segmentation with Power BI

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## Project Overview

**InsightMax** is a project aimed at enhancing targeted marketing strategies and personalized financial services recommendations through advanced customer segmentation. This project leverages various clustering techniques and a Decision Tree model to classify and analyze customer behaviors. Additionally, it integrates Power BI for comprehensive data visualization and insights.

![Project Overview](image.png)

## Table of Contents
- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Clustering Techniques](#clustering-techniques)
- [Decision Tree Model](#decision-tree-model)
- [Model Deployment](#model-deployment)
- [Power BI Integration](#power-bi-integration)
- [Installation](#installation)
- [Usage](#usage)
- [Files Included](#files-included)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In the competitive financial services industry, understanding customer behavior is crucial for developing effective marketing strategies and personalized services. This project uses clustering and decision tree techniques to segment customers and gain actionable insights. The integration of Power BI allows for dynamic visualizations that help in making data-driven decisions.

## Data Preprocessing

**Data preprocessing** involves the following steps:
1. **Data Cleaning:** Removing any missing or inconsistent data to ensure the quality of the dataset.
2. **Normalization:** Scaling numerical features to have a mean of 0 and a standard deviation of 1 to improve the performance of clustering algorithms.
3. **Encoding:** Converting categorical variables into numerical format using techniques such as One-Hot Encoding.

## Feature Engineering

**Feature engineering** is used to create additional features that may improve the performance of the clustering and decision tree models. This includes:
1. **Derived Features:** Creating new features from existing data, such as calculating the average transaction value or the number of transactions per customer.
2. **Interaction Features:** Combining features to capture interactions between them, which might be predictive of customer behavior.

## Clustering Techniques

Various **clustering techniques** are used to segment the customers, including:
- **K-Means Clustering**
- **Hierarchical Clustering**
- **DBSCAN**

## Decision Tree Model

A **Decision Tree model** is used to classify customer behaviors based on the clustered data. This model helps in understanding the factors influencing customer segmentation by:
1. **Training:** Using the clustered data to train the decision tree, learning the decision rules that classify the customers into different segments.
2. **Evaluation:** Assessing the performance of the model using metrics such as accuracy, precision, and recall.
3. **Feature Importance:** Identifying the most important features that influence the segmentation, which can provide insights for targeted marketing.

## Model Deployment

The models are deployed using **Streamlit**, providing an interactive web application for users to explore the segmentation results and insights. The steps involved are:
1. **Building the Streamlit App:** Creating a user-friendly interface to input data, preprocess it, apply clustering and decision tree models, and visualize the results.
2. **Interactive Visualizations:** Displaying the segmentation results using interactive charts and graphs that allow users to explore the data dynamically.

## Power BI Integration

**Power BI** is used to create dynamic dashboards and visualizations for the segmented customer data. These visualizations help in deriving actionable insights and enhancing data-driven decision-making by:
1. **Connecting to Data Sources:** Importing the processed data into Power BI.
2. **Creating Dashboards:** Designing interactive dashboards that display key metrics and trends.
3. **Drill-Down Analysis:** Allowing users to drill down into specific segments to gain deeper insights.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/InsightMax.git


## Usage
1. **Load the customer data into the application.**
2. **Perform data preprocessing and feature engineering.**
3. **Apply clustering techniques to segment the customers.**
4. **Use the Decision Tree model to classify customer behaviors.**
5. **Visualize the results using Power BI dashboards.**

## Files Included
kmeans_Model.pkl: Pre-trained K-Means model.
final_model.sav: Pre-trained Decision Tree model.
Customer Data.csv: Raw customer data.
Custemer segmentation.ipynb: Jupyter notebook with data preprocessing and clustering code.
Clustered_CustomerData.csv: Clustered customer data.
requirements.txt: List of required Python packages.
**Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License.
