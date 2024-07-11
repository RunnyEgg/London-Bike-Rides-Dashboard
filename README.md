
# London Bike Rides Data Analysis Project

This project demonstrates my journey in data analysis, Python programming, and data visualization through the creation of a dashboard that highlights key performance metrics of bike rides in London. 

## Table of Contents

- [Introduction](#introduction)
- [Project Motivation](#project-motivation)
- [Technologies Used](#technologies-used)
- [Project Steps](#project-steps)
  - [Data Collection](#data-collection)
  - [Data Processing](#data-processing)
  - [Data Visualization](#data-visualization)
- [Key Learnings](#key-learnings)
- [What I Would Like To Do In The Future](#what-i-would-like-to-do-in-the-future)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

## Introduction

The goal of this project was to create a comprehensive dashboard that effectively showcases important metrics and insights about bike rides in London, including their correlation with temperature and wind speed.

## Project Motivation

I wanted to create a project that would showcase my skills in data analysis and visualization. Analyzing bike rides in London provided a perfect opportunity to explore various tools and techniques in the process.

## Technologies Used

- **Python**: For data processing and manipulation.
- **Pandas**: For data manipulation and analysis.
- **Excel**: For data storage and preliminary analysis.
- **Tableau**: For creating an interactive dashboard for data visualization.

## Project Steps

### Data Collection

I started with the idea of making a project that showcases some of my skills. To gather data on bike rides in London, I obtained a dataset from Kaggle. 

### Data Processing

I used a Python script to process the raw data, which was then saved as an Excel file. The script processes the data to prepare it for visualization. The Python script is included in this repository as `london_bikes.ipynb`.

### Data Visualization

With the data ready, I moved on to creating the dashboard in Tableau. The dashboard includes:

- **Total Bike Rides**: Displays the total number of bike rides within a specified date range.
- **Moving Average of Bike Rides**: Shows the 10-day moving average of bike rides.
- **Heat Map**: Illustrates the relationship between temperature and wind speed with respect to bike rides.

The Tableau dashboard can be viewed [here](https://public.tableau.com/app/profile/andrew.skomra/viz/LondonBikeRides-MovingAverageandHeatmapDashboard/LondonBikeRides-MovingAverageandHeatmap).

![image](https://github.com/user-attachments/assets/47970d7f-4f3d-45e4-b944-039db28b0c8a)


## Key Learnings

Through this project, I gained a deeper understanding of:

- **Data Cleaning Techniques**: Learned various techniques for cleaning and preparing raw data for analysis, including handling missing values and outliers.
- **Tableau Skills**: Enhanced proficiency in Tableau, including advanced features like calculated fields, parameters, and dashboard actions.
- **Problem-Solving Skills**: Developed problem-solving skills by overcoming challenges such as my entire Tableau dashboard crashing and having to restart from the beginning.
- **Project Management**: Developed a systematic approach to planning and executing data analysis projects.

## What I Would Like To Do In The Future

- **Data Enrichment**: Explore other data sources and APIs to enrich the analysis further.
- **Integration with Real-time Data**: Implement a system that continuously updates the dashboard with real-time bike ride data.
- **Geospatial Analysis**: Incorporate geospatial data to analyze bike rides with respect to different locations in London.
- **Weather Impact Studies**: Perform detailed studies on how various weather conditions impact bike ride frequencies and patterns.

## Project Structure

```
├── london_bikes.ipynb        # Python script for data processing
├── london_bikes_final.xlsx   # Excel file with the processed data
├── london-bike-sharing-dataset.zip # Zip file that I recieved from Kaggle
├── README.md                 # Project documentation
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
