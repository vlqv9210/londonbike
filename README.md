# London Bike Sharing Dataset Analysis

This repository contains a dataset and analysis of bike-sharing data in London. The dataset was sourced from Kaggle and consists of historical data on bike usage, weather conditions, and other relevant factors.

## Dataset Overview

The London Bike Sharing Dataset includes hourly data on the number of bikes rented, along with related features such as temperature, humidity, and season. The dataset is designed to provide insights into how various factors affect bike usage in London.

### Dataset Features

- **Season**: The season in which the data was recorded (e.g., spring, summer, autumn, winter).
- **Year**: The year the data was collected.
- **Month**: The month the data was recorded.
- **Hour**: The hour of the day when the data was recorded.
- **Temperature**: The temperature at the time of recording.
- **Humidity**: The humidity level during the recording.
- **WindSpeed**: The speed of the wind at the time.
- **Weather**: Weather conditions (clear, cloudy, etc.).
- **Bike Rentals**: Number of bikes rented in a given hour.

## Project Overview

In this analysis, I used Python and the pandas library to clean, transform, and analyze the dataset. Key operations included:

1. **Loading the Dataset**: I loaded the dataset using pandas `read_csv()` method.
2. **Data Cleaning**:
   - Renamed columns for clarity.
   - Changed data types for some columns (e.g., converting the `season` and `weather` columns to string).
   - Mapped numeric values to actual season and weather labels.
3. **Exporting the Cleaned Data**: The cleaned dataset was exported to a CSV file for further analysis in Tableau.
4. **Visualization**: The final dataset was used to create visualizations in Tableau to explore trends in bike rentals based on various factors like weather and season.

## Tableau Dashboard

You can explore the final data and visualizations in my Tableau dashboard by following the link below:

[Tableau Dashboard - London Bike Sharing](https://public.tableau.com/shared/QT6WQJZ2M?:display_count=n&:origin=viz_share_link)

## Acknowledgments

- Dataset sourced from Kaggle: [London Bike Sharing Dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset/data)
- Inspiration for the analysis and visualizations was influenced by the following tutorial: [YouTube Video](https://www.youtube.com/watch?v=nl9eZl1IOKI)
