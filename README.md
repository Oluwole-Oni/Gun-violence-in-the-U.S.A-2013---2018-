# **Gun-violence in the U.S.A Analysis**
## **Tableau Link:** https://public.tableau.com/views/GunviolenceintheU_S_A2013-2018/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
## **Objective**
To analyze patterns and severity of gun violence in the United States between 2013 and 2018 using data-driven methods. This project combines advanced exploratory data analysis and clustering in Python with interactive Tableau dashboards to identify geographic disparities, incident severity profiles, and the relationships between firearm involvement, injuries, and fatalities, while visually presenting key insights through well-curated, interactive dashboards.

## **Key Questions**
1. How have gun violence incidents evolved over time?   
2. Which states, cities, or counties have the highest number of incidents?   
3. Is gun violence evenly distributed across the United States?  
4. How do gun violence incidents differ in severity?  
5. Do incidents involving more guns result in more victims?  
6. What is the relationship between guns involved, injuries, and fatalities?
7. Can gun violence incidents be meaningfully grouped based on severity and firearm involvement?

## **Data** 
 Gun Violence dataset used in this project is an open-source Kaggle repository created by James KO. It contains over 260,000 recorded gun violence incidents in the United States from 
January 2013 to March 2018.

## **Tools**  
For this project the following python libraries are used;   
- Pandas for data analysis  
- Numpy for mathematical computation   
- OS as interface for interaction with the operating system.  
- Matplotlib.pyplot for visualization    
- Seaborn for visualization  
- folium for Choropleth and geospatial mapping in Python.  
- scikit-learn for Regression and clustering (k-means).  
- json / geopandas for Integration of spatial data for mapping.  
- Pylab to combine functionality plotting and numeric computing.  

## **Folders**  
01 Project Management: Contain the project brief.

02 Data: has two subfolders (Note: Data folder was not uploaded due to its large file size)
 - Original Data: Original dataset (with JSON spatial file for state mapping)
 - Prepared Data: Cleaned data and derived datas used for analysis.
  
03 Scripts: Python code for the analysis, executed using Jupyter notebooks, namely;
- 6.1 Sourcing Open Data
- 6.2 Exploring Relationships & Visualizations
- 6.3 Data Visualization with Folium
- 6.4 Supervised Machine Learning Regression Analysis
- 6.5 Unsupervised Machine Learning Clustering
- 6.6 Sourcing and Analyzing Time Series Data

04 Analysis: Contain all visualizations used for exploratory analysis and insight.

## **Note**  
This dataset was sourced from Kaggle and utilized for educational and analytical purposes as part of the CareerFoundry Data Analytics Program.
