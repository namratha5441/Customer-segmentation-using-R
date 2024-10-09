# Customer-segmentation-using-R
This project implements customer segmentation using machine learning, specifically k-means clustering, to group customers into different segments based on their demographic and purchasing data. The objective is to assist businesses in understanding customer behavior to optimize marketing strategies, improve customer retention, and offer tailored product recommendations.

## Features
**Clustering Algorithm**: K-means clustering is used to segment customers based on age, annual income, and spending score.<br/>\
**Data Visualization**: Utilizes R’s data visualization libraries such as ggplot2 and Plotrix to generate plots like bar charts, pie charts, histograms, and scatter plots, helping visualize customer distributions.<br/>\
**Data Processing**: The dataset is pre-processed, and key features are selected to improve clustering accuracy.<br/>\
**Packages Used**:<br/>
Plotrix: For enhanced plotting features.<br/>
ggplot2: For high-quality data visualizations.<br/>
Cluster: To perform clustering algorithms like k-means.<br/>
dplyr: For efficient data manipulation.<br/>
## Dataset
The dataset, Mall_Customers.csv, consists of 400 records of mall customers, each containing the following fields:<br/>

Customer ID<br/>
Gender<br/>
Age<br/>
Annual Income (k$)<br/>
Spending Score (1-100)<br/>
## Workflow

**Data Pre-processing**: Cleaning and transforming the dataset for consistency and usability.\
**Exploratory Data Analysis (EDA)**: Visualizing customer demographics, income distribution, and spending patterns.\
**K-Means Clustering:** Using the elbow method to determine the optimal number of clusters, followed by the application of k-means clustering to group customers.\
**Visualization of Clusters:** Results are visualized using PCA to understand the distribution of customer segments.
## Results
The model segments customers into six distinct clusters, which can be used to:\
Personalize marketing campaigns.\
Tailor product offerings based on customer needs.\
Identify high-value customers and improve retention strategies.
