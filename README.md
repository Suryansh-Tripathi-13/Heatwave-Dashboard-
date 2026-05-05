#Heatwave Dashboard

1- Project Title / Headline:

* 🌍 Heatwave Anomalies: Global Temperature Crisis Dashboard🌡️:-

  A dynamic, interactive data visualization tool built to explore worldwide temperature anomaly data — focusing on country-wise heatwave     intensity, regional patterns, decade-over-decade trends, and global climate shifts from 1970 to 2023.

2- Short Description / Purpose:

* The Heatwave Anomalies Dashboard is a visually powerful and analytically rich Power BI report designed to help users explore and          understand temperature anomaly trends across 195+ countries and 50+ years of climate data. The dashboard highlights key metrics like      average anomaly, maximum heatwave intensity, minimum temperature deviation, and classification of heatwave severity — ranging from        Negative to Extreme. This tool is built for data analysts, climate researchers, sustainability professionals, and curious minds who       want to understand how Earth's temperature has shifted over decades — and which regions are most at risk.

3- Tech Stack:

* 📊 Power BI Desktop – Main platform used for building all visuals and reports
* 🗂️ Power Query – Used for cleaning and reshaping the raw temperature dataset into a usable format
* 🧮 DAX (Data Analysis Expressions) – Used for KPI cards, calculated measures, and aggregations
* 📅 Data Modeling – Relationships and filters set up for dynamic cross-filtering across all visuals
* 🐍 Python (Pandas) – Used for initial data cleaning and transforming wide format to long format
* 📁 File Format – .pbix for Power BI report

4- Data Source:
Source: https://www.kaggle.com/datasets/muhammadroshaanriaz/heatwave-excessive-heat-anomalies-by-year
Dataset contains surface temperature anomaly readings for 195+ countries from 1970 to 2023 — showing how much each country's temperature deviated from the long-term average each year.


Key Fields:

* Country – Name of the country
* Year – Year of recording (1970–2023)
* Anomaly_C – Temperature deviation in °C from baseline average
* Region – Continent/Region grouping (Asia, Europe, Africa, etc.)
* Decade – Decade grouping (1970s, 1980s... 2020s)
* Classification – Severity level (Extreme / Severe / Moderate / Slight / Negative)


5- Features / Highlights:


a- Business Problem:

Climate change is one of the biggest challenges of our time — yet most people don't have access to a simple, visual way to understand how temperatures have actually changed across the world. Raw data exists, but without a clear dashboard, it's hard to spot which countries are heating up the fastest, which decades saw the biggest jumps, and how severe the situation really is.


b-  Goal of the Dashboard:

 
The goal of this Heatwave Anomalies Dashboard is to provide one single, interactive report where anyone can:

* See global temperature anomaly trends at a glance using KPI Cards
* Explore year-by-year changes using Column and Line Charts
* Identify the most affected countries using Top 10 Bar Chart
* Understand decade-wise acceleration using Stacked Bar Chart
* Classify heatwave severity using Donut Chart
* Filter data dynamically using Year, Region, and Year Range Slicers


c- Walk Through of Key Visuals:


* KPI Cards (Top Row): Show Average Anomaly, Max Anomaly, Min Anomaly, Years Analyzed, and Countries Covered — instant snapshot of the global temperature situation in one glance


* Anomaly by Year (Column Chart): Shows how temperature deviation grew from 1970 to 2023 — the rising bars clearly tell the story of accelerating global warming


* Top 10 Countries (Bar Chart): Ranks the most affected countries by average anomaly — Bangladesh, Mongolia and Nepal lead the list — showing which nations face the highest climate risk


* Heatwave Classification (Donut Chart): Breaks down all records into Extreme, Severe, Moderate, Slight, and Negative categories — giving a clear picture of how severe the situation has become globally



* Region + Decade (Stacked Bar Chart): Compares how each region has changed across every decade — making it easy to see which regions are heating up the fastest over time


* Year-Wise Trend (Line Chart): A smooth trend line showing the clear and undeniable upward curve of global heating from 1970 to 2023 — impossible to ignore



* 3 Interactive Slicers (Region, Year, Year Range): Allow users to dynamically filter the entire dashboard — explore any specific region, year, or time period with just one click

  

d-  Business Impact & Insights:

* 🔴 2020s decade has the highest average anomaly of +1.78°C — clearly the hottest decade in recorded history
* 🌏 Asia and Africa show the steepest rise in recent decades — most vulnerable regions
* 📈 18.7% of all records fall in the Extreme category — number growing every decade
* 🌡️ The trend line shows clear, undeniable upward movement from 1990s onwards
* 🗺️ India, Brazil, and Australia consistently top the most-affected countries list


6-   Screenshot/ Demo:

* Show what the dashboard looks like.

<img width="906" height="506" alt="Heatwave Dashboard " src="https://github.com/user-attachments/assets/e7f7b28c-0d3c-4331-8c11-62438a02d75b" />


