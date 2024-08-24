# Customer Segmentation Project

## Overview

Customer segmentation is a critical element in modern business strategy, allowing companies to target specific customer groups more effectively. This project focuses on segmenting customers based on their behavioral data using clustering techniques. By identifying distinct customer segments, businesses can tailor their marketing efforts, improve customer satisfaction, and enhance overall engagement.

## Project Definition
The primary goal of this project is to perform customer segmentation using clustering algorithms such as KMeans and Agglomerative Clustering. The project includes analyzing customer data, determining the optimal number of segments, and visualizing the results to gain insights into customer behavior.

## Analysis
The analysis involves the following steps:

## Data Preprocessing:
Clean and normalize the data to ensure all features contribute equally to the clustering process.

## Clustering:
Apply KMeans and Agglomerative Clustering to identify distinct customer segments.
Use silhouette scores to evaluate the performance of the clustering algorithms and determine the optimal number of clusters.

## Visualization:
Visualize the clustering results using bar plots and scatter plots to understand customer segments and their characteristics.

## Libraries Used
- pandas: Data manipulation and analysis
- numpy: Numerical computing
- matplotlib: Data visualization
- seaborn: Statistical data visualization
- scikit-learn: Machine learning and clustering algorithms

## Dataset Descriptions

### df_reloads
This dataset contains information on customer reloads with the following columns:

Subs ID: Unique identifier for the subscriber (int64)
Reload Date: Date of the reload (int64)
Reload ($): Amount reloaded in dollars (int64)


### df_app
This dataset includes details on customer social media logins and usage:

subs_id: Unique identifier for the subscriber (object)
total_data_mb: Total data usage in megabytes (float64)
other_app_(mb): Data usage in megabytes for other apps (float64)
facebook_login_(day_count): Number of logins to Facebook per day (float64)
twitter_login__(day_count): Number of logins to Twitter per day (float64)
instagram_login_(day_count): Number of logins to Instagram per day (float64)
youtube_login_(day_count): Number of logins to YouTube per day (float64)
whatsapp_login_(day_count): Number of logins to WhatsApp per day (float64)
facebook_monthly_data_mb: Monthly data usage on Facebook (float64)
twitter_monthly_data_mb: Monthly data usage on Twitter (float64)
instagram_monthly_data_mb: Monthly data usage on Instagram (float64)
youtube_monthly_data_mb: Monthly data usage on YouTube (float64)
whatsapp_monthly_data_mb: Monthly data usage on WhatsApp (float64)
facebook_monthly_upload_mb: Monthly upload data on Facebook (float64)
twitter_monthly_upload_mb: Monthly upload data on Twitter (float64)
instagram_monthly_upload_mb: Monthly upload data on Instagram (float64)
youtube_monthly_upload_mb: Monthly upload data on YouTube (float64)
whatsapp_monthly_upload_mb: Monthly upload data on WhatsApp (float64)

## Repository Structure
- **Customer_segmentation_project.ipynb:**   Jupyter Notebook containing the code for data preprocessing, clustering, and visualization.
- **README.md:**  This file, providing an overview of the project, its motivation, and instructions for running the analysis.
- **data:** Directory containing the raw datasets (df_reloads and df_app).
  
- ## Project Repository
The full project is hosted on GitHub: [Customer-Segmentation Project](https://github.com/asliyalcin/Customer-Segmentation)

### Installation

 **Clone the Repository:**
    ```bash
    git clone https://github.com/asliyalcin/Customer-Segmentation
    cd your_repository
    ```

## Results Summary
The analysis successfully identified distinct customer segments based on behavioral data. The segments were visualized and profiled to provide actionable insights for targeted marketing strategies. The optimal number of clusters was determined using silhouette scores, and the final segments were characterized by unique patterns in customer behavior.

## Acknowledgements
https://medium.com/towards-data-science/mastering-customer-segmentation-with-llm-3d9008235f41
https://github.com/damiangilgonzalez1995/Clustering-with-LLM/blob/main/kmeans.ipynb
