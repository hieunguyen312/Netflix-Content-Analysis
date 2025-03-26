# 📊 Netflix Dataset Dashboard

## Work in Progress

This project analyzes and visualizes the Netflix content catalog using Python and Power BI.

## 🔧 Tools Used
- **Python (Pandas, NumPy)** in **Jupyter Notebook** for data cleaning and preprocessing  
- **Power BI** for building the interactive dashboard  
- **Excel** to store the cleaned dataset  

## 🧼 Data Cleaning Highlights
- Handled 8,790 entries from the Netflix dataset  
- Identified and replaced custom null values like `"Not Given"` in `director` and `country`  
- Dropped duplicate records  
- Split multi-value columns like `listed_in` (genres) and one-hot encoded them into individual columns  
- Exported cleaned data to Excel for further analysis  

## 📁 Files
- `notebook.ipynb` – Python data cleaning script (Jupyter Notebook)  
- `Cleaned_Netflix_Data.xlsx` – Cleaned dataset used for visualization  
- `Netflix_Dashboard.pbix` – Power BI file (interactive dashboard)  

## 📈 Dashboard Overview
The Power BI dashboard includes:
- Distribution of content by type, genre, and country  
- Trends over time (e.g., releases per year)  
- Popular genres breakdown  
- Missing metadata insights (e.g., missing director info)  

## 🚀 How to Use
1. Clone the repo or download the files  
2. Open the `.pbix` file using Power BI Desktop  
3. Optionally, explore or modify the Jupyter notebook for cleaning logic

 ### All of the files can be found in the repository
