# 🍽️ Restaurant Geographical Analysis  

This project focuses on performing a **geographical analysis of restaurants** using location-based data. It explores how restaurants are distributed globally and within cities, while uncovering insights about cuisines, ratings, and costs.  

---

## 📌 Objectives  
- Visualize restaurant distribution using **latitude** and **longitude** coordinates.  
- Group restaurants by **city/locality** to analyze concentration.  
- Calculate statistics such as **average ratings, cuisines, and price ranges**.  
- Identify **patterns and insights** related to restaurant locations.  

---

## 📂 Dataset  
- The dataset contains restaurant details including **City, Latitude, Longitude, Cuisines, Ratings, and Average Cost for Two**.  
- Missing or duplicate values are cleaned before analysis.  

---

## 🛠️ Technologies Used  
- **Python (Pandas, NumPy)** → Data cleaning & preprocessing  
- **GeoPandas, Shapely** → Geospatial analysis  
- **Matplotlib, Seaborn** → Data visualization  
- **GeoJSON / Folium** → Map plotting  

---

## 📊 Key Visualizations  
1. **Top 10 Cities by Restaurant Count** – identifies food hubs.  
2. **Average Rating by City** – compares quality across regions.  
3. **Cost Distribution** – boxplot showing variation in dining cost.  
4. **Top 20 Cuisines** – most popular cuisines globally.  
5. **Global Distribution Map** – plots all restaurants on a world map.  
6. **High-Rated Restaurants (≥4.5)** – percentage analysis by city.  

---

## 🚀 Insights  
- Metropolitan areas host the **highest number of restaurants**.  
- Certain cuisines dominate specific localities, reflecting cultural demand.  
- Tourist and business hubs tend to have **premium, high-rated restaurants**.  
- Hidden gems exist in low-density regions with surprisingly high ratings.  

---

## ▶️ Running the Project  
```python
# Install required libraries
pip install pandas geopandas matplotlib seaborn shapely

# Run the script
python analysis.py

