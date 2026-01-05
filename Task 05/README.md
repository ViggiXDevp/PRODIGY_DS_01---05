# US Traffic Accident Analysis – Task 5 🚗📊

## Overview 🌐
Analyzed traffic accident data to identify patterns related to road conditions, weather, and time of day. Visualized accident hotspots and contributing factors using the US Accidents dataset from Kaggle.  
Focused on uncovering high-risk areas, weather impacts, and temporal patterns across 49 US states (2016-2023).

## Dataset 📁
- **Name:** US Accidents (2016 - 2023)  
- **Source:** [Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)  
- **Size:** ~7.7M records, 49 columns, 2.5+ GB  

**Example columns:**  
- Location: `Start_Lat`, `Start_Lng`, `City`, `State`, `County`  
- Time: `Start_Time`, `End_Time`, `Sunrise_Sunset`  
- Weather: `Temperature(F)`, `Weather_Condition`, `Visibility(mi)`, `Precipitation(in)`  
- Road: `Amenity`, `Bump`, `Crossing`, `Junction`, `Traffic_Signal`  
- Severity: `Severity` (1-4 scale)

## What I Implemented ✅
- Loaded and sampled the large dataset using `pandas` (handled 7M+ rows with chunking/sampling).  
- Cleaned data (dropped nulls, parsed timestamps, feature-engineered hour/day/month).  
- Plotted:
  - 🗺️ **Hotspot maps**: To show accident density by state/city.  
  - 📈 **Time patterns**: Accidents by hour-of-day, day-of-week, month.  
  - 🌤️ **Weather analysis**: Severity vs weather conditions, precipitation, visibility.  
  - 🛣️ **Road factors**: Count plots for junctions, traffic signals, bumps, etc. vs severity.  
- Added correlation heatmap and summary statistics for key factors.

## Tech Stack 🛠️
- **Language:** Python  
- **Libraries:** `pandas`, `matplotlib`, `seaborn`, `folium` (maps), `geopandas`  
- **Environment:** Jupyter Notebook / Google Colab (with Drive for large CSV)


***

**Note:** This dataset is **huge** (7M+ rows), so your notebook likely uses sampling or chunking – mention that in "What I Implemented" if applicable! 🚀
