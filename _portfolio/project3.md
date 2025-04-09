---
title: "Retail Recovery Trends - Time Series Dashboard"
image: /images/retail-dashboard-thumbnail.png
description: "A Power BI dashboard exploring long-term industry trends and recovery patterns in the Australian retail sector."
url: /portfolio/retail-dashboard/
date: 2025-04-08
tags: [Power BI, Time Series, Forecasting, Seasonality, Retail Analytics, DAX]
---

## **Project Summary**
This interactive **Power BI dashboard** explores long-term sales trends across retail industries in Australia using time series decomposition. It enables users to assess industry-specific behaviour over time and evaluate how different sectors have recovered post-2020.

## **Problem Statement**
**How do long-term retail trends differ across industries, and what can we learn from their post-pandemic recovery patterns?**

This dashboard helps decision-makers understand growth patterns, seasonal behaviours and the pace of recovery in different retail sectors. It enables exploration of time series trends (original, seasonally adjusted and trend) to identify which industries are thriving and which are lagging, informing investment, marketing and policy decisions.

## **Key Features & Functionality**
- **Time Series View Toggle**: Switch between *Original*, *Trend* and *Seasonally Adjusted* views
- **Interactive Industry Filtering**: Analyse specific industries or their combinations using slicers
- **Area Chart by Industry**: Understand the share of each retail sector over time
- **Monthly Sales Bar Graph**: Compare sales volumes across different months to analyse seasonal effects
- **Line Graph - Change Over Time**: Visualise multi-decade trends and compare recovery speed across industries  

## **Tech Stack**
- **Tool Used**: Power BI  
- **Techniques**: Time Series Decomposition, DAX Measures, Slicers, Power Query  
- **Data Modelling**: Relationship management and dynamic visual interactivity

## **Live Dashboard**

<iframe title="retail_insights" width="1140" height="541.25" src="https://app.powerbi.com/reportEmbed?reportId=cf08789b-1730-4411-916c-2c42784319ec&autoAuth=true&ctid=ef7a487a-77ca-410a-803d-e426b62a587f" frameborder="0" allowFullScreen="true"></iframe>

## **Results & Impact**

### 1. Food Retail Leads Recovery  
Across all time series views, Food Retail shows the highest sales and fastest growth post-2020. This suggests that food-related purchases remained a top priority for consumers even during economic downturns. Its essential nature and continued demand made it more resilient to disruption, contributing to a rapid recovery.

### 2. Household Goods Growth Surge  
Post-2020, Household Goods experienced a sharp upward trend. This likely reflects a behavioural shift during lockdown, where people invested more in home improvement, comfort and remote work setups. The increased time spent at home led to greater spending in this category.

### 3. Struggles for Department Stores  
Clothing & Department Stores show slower recovery trends and flatter long-term growth. These sectors were more affected by reduced in-store traffic during lockdowns and the rise of e-commerce. Their non-essential nature during a crisis further delayed their recovery.

### 4. December Sales Spike  
Monthly sales patterns show a consistent peak in December, emphasising the strong influence of holiday shopping on retail performance. This seasonal trend suggests that businesses in all retail categories rely heavily on end-of-year consumer activity.

### 5. Long-Term Industry Shifts  
“The "Change Over Time" line graph shows diverging growth trajectories. Essential categories like Food Retail and Household Goods have steadily grown, while Department Stores and Clothing have plateaued. This reflects a larger shift in consumer priorities — from fashion and variety to practicality and necessity.

## **Analytical Focus**
The *“Change Over Time”* line graph revealed how each industry evolved from 1980 onwards:
- **Diverging growth paths** indicating changing consumer behaviours
- Clear identification of **pandemic impact and recovery slopes**
- **Food and Household Goods** emerged as resilient sectors with accelerated post-2020 growth

## **Challenges & Learnings**
- Designing visuals that clearly separate *trend*, *seasonality* and *actuals*  
- Aligning industry comparisons across multi-decade timelines  
- Creating interactivity without overwhelming the viewer

## **Future Improvements**
- Add **forecast projections** using statistical models  
- Integrate **external economic factors** for deeper correlation analysis  
- Expand dashboard scope to include **state-wise breakdowns** or demographic filters

## **Download the Report**
You can download the full `.pbix` file from GitHub here:  
[Download RetailDashboard.pbix](https://github.com/parnikakhattri/parnikakhattri.github.io/raw/main/RetailDashboard.pbix)


