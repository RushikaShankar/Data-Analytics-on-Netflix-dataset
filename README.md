# Data-Analytics-on-Netflix-dataset
# Data Analytics Project – Excel, Python, and Power BI

## Dataset Overview
This dataset contains information on the weekly Top 10 Netflix titles across multiple countries. It tracks rankings, longevity, and category for both Films and TV Shows over time.

Source: Netflix Top 10 data compiled weekly by country.
File Used: all-weeks-countries.xlsx
Sheet Used: Cleaned and processed as FactTop10 for analysis.

### Columns
#### Column Name	    and its             Description

week	:                        The starting date of the ranking week.

category	:                    Type of title — Films or TV Shows.

show_title	 :                 Name of the show or film.

season_title 	:                Season name if applicable (for TV Shows).

country_name	 :               Name of the country where the ranking is recorded.

country_iso2	  :              ISO-2 code of the country.

weekly_rank	  :                Rank of the title in that country for the given week (1–10).

cumulative_weeks_in_top_10	:  Total weeks the title has been in the Top 10 in that country.


## Project Overview
This project demonstrates end-to-end data analysis using three major tools: Excel, Python, and Power BI.
The goal was to perform Exploratory Data Analysis (EDA), build interactive dashboards, and extract meaningful insights from raw data by following industry-standard practices.

The project is divided into three modules:

+ Data cleaning & Dashboard Creation in Excel

+ EDA & Visualization using Python

+ Interactive Dashboard using Power BI

## Repository Structure
📁 Data-Analytics-Project

 ├── 📄 Excel_Project.xlsx      
 ├── 📄 Python_Project.ipynb     
 ├── 📄 PowerBI_Project.pbix     
 ├── 📄 README.md                
 └── 📄 Dataset.csv    

## Tools & Technologies Used
Excel – Data cleaning, pivot tables, charts, slicers, dashboard creation

Python – Pandas, Matplotlib, Seaborn for EDA and visualization

Power BI – Data modeling, DAX calculations, interactive dashboard

## Project Workflow
### 1️⃣ Excel – EDA & Dashboard
#### Data Cleaning: 
Removed duplicates, handled missing values, formatted data types

#### EDA:

- Created pivot tables and pivot charts

- Calculated descriptive statistics (mean, median, min, max, count)

- Identified trends and anomalies

#### Dashboard:

- KPIs, bar/line/pie charts

- Slicers for dynamic filtering

- Clear labels and visually appealing layout

### 2️⃣ Python – EDA & Visualization
#### Data Cleaning:

- Handled null values and outliers

- Converted data types

- Removed irrelevant columns

#### EDA:

- Dataset summary (shape, data types, statistical overview)

- Value counts and groupby aggregations

- Correlation analysis (heatmap)

#### Visualizations:

- Bar plots, line plots, histograms

- Box plots for outlier detection

- Heatmaps for correlation analysis

### 3️⃣ Power BI – Interactive Dashboard
#### Data Import & Cleaning: 
Using Power Query

#### EDA in Power BI:

- Visuals for trend analysis (bar, line, table)

- Filters and slicers for interactivity

#### Data Modeling:

- Relationships between tables using star schema

- Appropriate primary and foreign keys

#### DAX Calculations:

- Measures (SUM, AVERAGE, COUNTROWS)

- Conditional logic with IF and CALCULATE

#### Dashboard Design:

- Interactive KPIs, slicers, dynamic visuals

- Focus on usability and insights

## License
This project is for educational purposes as part of the MIT Data Analytics Training Program.
