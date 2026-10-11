What Makes a YouTube Video Trend? – A Data-Driven Analysis

📌 Project Overview

YouTube is one of the most popular platforms for digital content, with millions of videos competing for audience attention. Understanding the characteristics associated with trending videos can help content creators make informed decisions about their content and publishing strategies.

This project analyses the YouTube Trending Videos Stats 2026 dataset, specifically the `IN_Trending.csv` dataset obtained from Kaggle. It explores patterns in video views, likes, comments, categories, channels, and publishing times to better understand the characteristics associated with trending videos.

The analysis is performed using Python for data processing and exploratory data analysis (EDA), while Microsoft Power BI is used to create an interactive dashboard for visualizing the results.

🎯 Objectives

- Clean and pre-process the YouTube trending videos dataset.
- Explore video performance using views, likes, and comments.
- Analyse video performance across different content categories and channels.
- Examine the relationship between views and likes.
- Analyse video publishing patterns based on publishing hours.
- Derive additional features such as engagement rate, like rate, comment rate, title length, and tag count.
- Present the analysis through an interactive Power BI dashboard.

 🛠️ Technologies Used

 Programming Language - Python 
 Data Processing - Pandas, NumPy 
 Data Visualization - Matplotlib 
 Development Environment - Google Colab / Jupyter Notebook 
 Dashboard - Microsoft Power BI 
 Dataset Format -CSV 

 📂 Dataset

Dataset Name: YouTube Trending Videos Stats 2026  
Dataset File: `IN_Trending.csv`  
Source: Kaggle

The dataset contains information about trending videos, including:

- Video title and video ID
- Channel name and channel ID
- Views, likes, dislikes, and comments
- Video category
- Publishing time and trending date
- Video tags and description

These attributes are used to explore video performance, audience engagement, category-wise trends, and publishing patterns.

⚙️ Project Workflow

 1. Data Collection
Downloaded the YouTube Trending Videos Stats 2026 dataset from Kaggle.

 2. Data Cleaning and Pre-processing
Inspected the dataset, checked for missing values and duplicate records, handled missing descriptions, and converted publishing timestamps into a suitable datetime format.

 3. Exploratory Data Analysis (EDA)
Explored video performance and audience engagement using descriptive statistics and visual analysis.

 4. Feature Engineering
Created additional features to support the analysis, including:

- Publish Hour: Hour at which a video was published.
- Publish Day: Day of the week on which a video was published.
- Publish Month: Month in which a video was published.
- Engagement Rate: Percentage based on views, likes, and comments.
- Like Rate: Likes as a percentage of views.
- Comment Rate: Comments as a percentage of views.
- Title Length: Number of characters in the video title.
- Tag Count: Number of tags associated with a video.

 5. Data Visualization
Used charts to explore relationships between views and likes, category-wise performance, channel performance, and publishing patterns.

 6. Interactive Dashboard
Developed a Power BI dashboard containing KPI cards, charts, and a category filter to make the results easier to explore and interpret.

 📊 Dashboard Features

The Power BI dashboard includes:

- Total Views: Displays the total views for the selected data.
- Total Likes: Displays the total likes for the selected data.
- Views by Category: Compares views across video categories.
- Views by Publish Hour: Examines how total views vary across publishing hours.
- Views vs Likes: Visualizes the relationship between video views and likes.
- Top 5 Channels by Views: Highlights channels with the highest total views.
- Interactive Category Filter: Allows users to explore the dashboard for selected video categories.

 🔍 Key Areas of Analysis

The project focuses on understanding:

- Which content categories receive higher view counts.
- How views and likes are related.
- How video performance varies by publishing hour.
- Which channels receive higher total views in the dataset.
- How audience engagement can be measured using likes and comments relative to views.


 📌 Conclusion

This project demonstrates how data analysis and visualization can be used to study the characteristics associated with YouTube trending videos. By examining views, likes, comments, categories, channels, and publishing times, the project provides an accessible way to explore video performance and audience engagement.

The interactive Power BI dashboard presents these patterns in a visual and understandable format, helping content creators explore the data and make more informed decisions when planning and improving their content.

📚 References

1. Kaggle — https://www.kaggle.com/
2. Pandas Documentation — https://pandas.pydata.org/docs/
3. NumPy Documentation — https://numpy.org/doc/
4. Matplotlib Documentation — https://matplotlib.org/
5. Microsoft Power BI — https://powerbi.microsoft.com/
6. Google Colab — https://colab.research.google.com/

