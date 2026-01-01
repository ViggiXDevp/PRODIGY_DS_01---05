# Crime Data Visualization – Task 1 📊

## Overview 🌐
Visualized the distribution of crime-related variables using bar charts and/or histograms on the Indian Crimes Dataset from Kaggle.[web:10][web:11]  
Focused on understanding how crimes are distributed across categories (like gender or city) and continuous features (like age).[web:12]

## Dataset 📁
- **Name:** Indian Crimes Dataset[web:10]  
- **Source:** Kaggle (`sudhanvahg/indian-crimes-dataset`)[web:10][web:11]  
- **Example columns:** `city`, `crime_description`, `victim_age`, `victim_gender`, `weapon_used`, `crime_domain`.[web:12]

## What I Implemented ✅
- Loaded the dataset using `pandas` and inspected basic structure (rows, columns, data types).  
- Cleaned/filtered the data for the chosen variables (handled missing or invalid values where needed).  
- Plotted:
  - 📊 **Bar chart** for a categorical variable (e.g., distribution of `victim_gender` or `crime_domain`).  
  - 📈 **Histogram** for a continuous variable (e.g., distribution of `victim_age`).  
- Added titles, axis labels, and adjusted figure size/rotation for better readability.

## Tech Stack 🛠️
- **Language:** Python  
- **Libraries:** `pandas`, `matplotlib`, `seaborn`  
- **Environment:** Jupyter Notebook / Google Colab

## How to Run 🚀
1. Clone this repository and navigate into it.  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

