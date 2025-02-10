---
title: "Coffedia - The Encyclopaedia to Coffee"
image: /images/coffedia.png
description: "An interactive Shiny app exploring coffee trends and feedback worldwide."
url: /portfolio/coffedia/
date: 2025-01-15
tags: [R, Shiny, Visualisation]
---

## **Project Summary**
Coffedia is an **interactive R Shiny application** designed to empower coffee enthusiasts and businesses by providing insights into coffee brand popularity, outlet distribution and customer feedback. By combining user-friendly interfaces with advanced analytics, it simplifies exploring the coffee market and understanding trends across the globe.

## **Problem Statement**
The coffee industry is rich in data but lacks a centralised, accessible platform for meaningful exploration. Consumers struggle to find detailed insights on coffee brands and outlets, while businesses face challenges in analysing customer preferences and market trends. Coffedia addresses these challenges by delivering an intuitive tool that combines analytics, feedback storage and interactive visualisations to bridge the gap between data and actionable insights.

## **Key Features & Functionality**

### **1. About Tab**
- Provides an overview of **Coffedia’s mission, features and the inspiration** behind its development.

### **2. Popularity Tab**
- Visualise the **popularity of coffee brands** across different countries.
- Includes **dynamic filtering options** for in-depth brand and country-specific analysis.

### **3. Outlets Tab**
- Explore **coffee outlet locations** in various cities using an easy-to-navigate table.
- Filter results by **country, city and brand** to find specific coffee spots.

### **4. Feedback Tab**
- Collect and store user feedback on coffee brands and outlets, including ratings and reviews.
- Visualise feedback through an engaging **word cloud** and explore detailed individual reviews.

## **Tech Stack**
- **Framework:** R Shiny
- **Libraries Used:** shiny, plotly, ggplot2, DT, readxl, bslib, shinycssloaders, tidyverse, shinyWidgets, wordcloud2

## **How It Works**
1. **Data Requirements**:
   - Input data includes coffee outlet information (country, city, brand) and customer feedback.
   - Excel was used to compile and organise data from multiple brands into a uniform structure for analysis.

2. **Setup Instructions**:
   - Install necessary R libraries for running the app.
   - Place the prepared dataset and feedback files in the designated `data/` folder.

3. **Launch the App**:
   - Run the app script in RStudio with the command:
     ```r
     shiny::runApp()
     ```
     
4. **Explore**:
   - Use the app’s intuitive tabs to visualise brand popularity, locate outlets and analyse feedback trends.

## **Results & Impact**
- Integrated Excel for **data compilation and manipulation**, bringing together data from multiple brands into a standardised format for analysis.
- Delivered a comprehensive tool for **trend analysis, market insights and feedback exploration**, empowering businesses to make informed decisions.
- Designed and implemented **feedback storage functionality** to facilitate continuous collection and analysis of user preferences.
- Enabled **feedback analysis** through dynamic word clouds, helping highlight customer preferences.
- Provided businesses with tools for **customised market analysis** and decision-making.

## **Challenges & Learnings**
- **Data Standardisation**: Combining data from multiple brands into a consistent format required significant preprocessing in Excel to ensure compatibility with the app's analysis workflows.
- **Feedback Handling**: Designing a robust system to store and visualise user feedback was challenging, particularly when accommodating various review formats and ratings.
- **User Experience**: Striking the right balance between functionality and simplicity in the app interface required iterative design and testing to meet user expectations.

## **Future Improvements**
- **Enhanced Visualisations**: Develop advanced and interactive maps for outlet exploration.
- **Sentiment Analysis**: Integrate sentiment analysis into the feedback functionality for deeper insights.
- **Mobile-Friendly Design**: Optimise the app’s interface for seamless use on mobile devices.

## **Shiny App Link**
The Coffedia Shiny app is live and can be accessed here: [Coffedia App](http://parnikakhattri.shinyapps.io/Coffedia1)

