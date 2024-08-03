InsightMax: Financial Customer Segmentation with Power BI
Project Overview
InsightMax is a project aimed at enhancing targeted marketing strategies and personalized financial services recommendations through advanced customer segmentation. This project leverages various clustering techniques and a Decision Tree model to classify and analyze customer behaviors. Additionally, it integrates Power BI for comprehensive data visualization and insights.

Table of Contents
Introduction
Data Preprocessing
Feature Engineering
Clustering Techniques
Decision Tree Model
Model Deployment
Power BI Integration
Installation
Usage
Files Included
Contributing
License
Introduction
In the competitive financial services industry, understanding customer behavior is crucial for developing effective marketing strategies and personalized services. This project uses clustering and decision tree techniques to segment customers and gain actionable insights. The integration of Power BI allows for dynamic visualizations that help in making data-driven decisions.

Data Preprocessing
Data preprocessing involves cleaning and preparing the data for analysis. This includes handling missing values, normalizing data, and encoding categorical variables.

Feature Engineering
Feature engineering is used to create additional features that may improve the performance of the clustering and decision tree models. This includes creating derived features from the existing data.

Clustering Techniques
Various clustering techniques are used to segment the customers, including:

K-Means Clustering
Hierarchical Clustering
DBSCAN
Decision Tree Model
A Decision Tree model is used to classify customer behaviors based on the clustered data. This model helps in understanding the factors influencing customer segmentation.

Model Deployment
The models are deployed using Streamlit, providing an interactive web application for users to explore the segmentation results and insights.

Power BI Integration
Power BI is used to create dynamic dashboards and visualizations for the segmented customer data. These visualizations help in deriving actionable insights and enhancing data-driven decision-making.

Installation
Clone the repository
bash
Copy code
git clone https://github.com/your-username/InsightMax.git
Install the required dependencies
bash
Copy code
pip install -r requirements.txt
Run the Streamlit application
bash
Copy code
streamlit run app.py
Usage
Load the customer data into the application.
Perform data preprocessing and feature engineering.
Apply clustering techniques to segment the customers.
Use the Decision Tree model to classify customer behaviors.
Visualize the results using Power BI dashboards.
Files Included
kmeans_Model.pkl: Pre-trained K-Means model.
final_model.sav: Pre-trained Decision Tree model.
Customer Data.csv: Raw customer data.
Custemer segmentation.ipynb: Jupyter notebook with data preprocessing and clustering code.
Clustered_CustomerData.csv: Clustered customer data.
requirements.txt: List of required Python packages.
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License.

