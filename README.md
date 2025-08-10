# Energy Commodity Prices and U.S. Producer Price Index (PPI) Analysis

#### -- Project Status: Completed

## Project Intro/Objective
The purpose of this project is to explore potential connections between global energy commodity prices—specifically crude oil, coal, and natural gas—and the U.S. Producer Price Index (PPI) from 1992 to 2016. Our goal is to identify trends, anomalies, and possible correlations that might inform deeper economic inquiry. This exploratory analysis serves as a foundation for future predictive modeling and economic forecasting work. By uncovering patterns in these historical relationships, we can better anticipate the economic impact of commodity market shifts.

### Methods Used
* Data Cleaning and Preparation
* Exploratory Data Analysis (EDA)
* Time Series Analysis
* Correlation Analysis
* Data Visualization

### Technologies and Packages
* RStudio
* tidyverse
* data.table
* lubridate
* ggcorrplot
* quantmod
* reshape2
* scales
* viridisLite

## Project Description
This project analyzes historical datasets for commodity prices and the U.S. Producer Price Index (PPI) to answer the research question:
**How do fluctuations in global energy commodity prices relate to changes in the U.S. PPI between 1992 and 2016?**

To explore how movements in global energy markets influence domestic production costs, this study examines monthly data from the International Monetary Fund (IMF) and the U.S. Bureau of Labor Statistics (via FRED) between 1992 and 2016. We focus on three major energy commodities—Crude Oil, Coal, and Natural Gas—and investigate their relationships with the U.S. Producer Price Index (PPI), a key indicator of producer-level inflation. Our analysis employs descriptive statistics, distribution plots, and time-series visualizations with static, lagged, and 12-month rolling correlation techniques. This multi-faceted approach allows us to assess both the strength and timing of these relationships, determining whether commodity prices tend to lead, lag, or move synchronously with changes in the PPI. By identifying periods when correlations strengthen, weaken, or reverse, we seek to better understand the predictive value of energy prices for inflation forecasting. Although the dataset provides valuable long-term insights, its interpretation is limited by the use of aggregated global prices, the exclusion of data beyond 2016, and the near-perfect correlation between Crude Oil and Natural Gas, which complicates interpretation.

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw data is located in `data/raw/` within this repo.
3. Processed data is in `data/processed/`.
4. EDA notebook files (`.Rmd` source file and rendered `.html` report)  are located in `notebooks/`.
5. To run the analysis interactively, open the R Markdown file in RStudio.

## Featured Notebooks/Analysis/Deliverables
* [EDA Analysis R Markdown File](notebooks/EDA.Rmd)
* [EDA Analysis HTML Report](notebooks/EDA.html)


## Team Contacts

| Name | GitHub Handle |
|------|--------------|
| Kimberly Cardinale | @kimcardinale |
| Noelle Crichton | @ncrichton|
| William Kong | @william-dk |

## Contact
* Feel free to contact team leads with any questions or if you are interested in contributing!
