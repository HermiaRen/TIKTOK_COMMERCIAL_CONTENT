# TikTok Commercial Content Analysis

## 1. Purpose of this Project

TikTok's remarkable growth in recent years has attracted businesses seeking to leverage its massive user base for targeted advertising. Social and streaming service platforms have become popular channels for businesses to connect with potential customers.
This project delves into the analysis of ads performance on TikTok in the European region, as TikTok only makes its commercial data in the EU available to the public. The goal is to gain insights into ads performance, identify factors impacting performance, and develop machine learning models for predicting ad performance.

## 2. Methods Used

### Data Preparation
As TikTok lacks an open API, data retrieval involved submitting an application for API access, generating access tokens, and making multiple API calls to overcome request limitations. The data preparation phase included fetching ad information, storing it as CSV files, and cleaning the data for both machine learning and visualization purposes.

### Data Visualization
Nine charts were created using Tableau to visualize ad performance. The charts cover various aspects, providing a comprehensive view of the data and facilitating insights into trends and patterns.
### Tableau Link: https://public.tableau.com/app/profile/jordan.kane/viz/TikTokAdTargetingAnalysis/Dashboard?publish=yes

### Machine Learning Models
Four machine learning models were designed to predict whether ads would meet business expectations. Cluster, Logistic Regression, Decision Tree, and TensorFlow models were employed, with Decision Tree yielding particularly promising results.

## 3. Structure of the Repo

### Resources:
Contains all CSV and JSON files used in the project.
### Fetch_Data.ipynb:
Code for making API calls to fetch and store data.
Code for converting JSON files into CSV files and merging CSV files.
### TikTok Data Analysis Presentation PDF.pdf:
Presentation PowerPoint file.
### ads_id_ads_videos.ipynb:
Data cleaning code for preparing data for further data visualization in Tableau.
### ads-link-clean.ipynb
Data cleaning code for ads video links for data visualization.
### ads_machine_learning.ipynb:
Code for data preparation for machine learning.
Code for all machine learning models.

## 4. Authors

### Hermia Ren:
Code author for fetching data and data cleaning.
Code author for machine learning.
Tableau Stories and Dashboard creator.
Maker of all scatter plots for data visualization.
Contributed to PowerPoint.

### Jordan Kane:
Code author for preparing data for visualization.
Author of all bar charts and maps for visualization.
Writer of data insights reports.
Contributed to PowerPoint.
