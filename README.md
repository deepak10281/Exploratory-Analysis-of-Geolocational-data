# Exploratory-Analysis-of-Geolocational-data

This project performs an **explanatory analysis of geolocational data** to help users identify suitable accommodation areas based on nearby amenities and lifestyle preferences.  
Using **K-Means Clustering**, **Geolocation APIs**, and **Interactive Map Visualization**, the project groups different areas into clusters to make house/room location decisions easier and more data-driven.

---

## 🎯 Objective
To recommend ideal accommodation zones for new residents or travelers by:
- Identifying spatial patterns in location-based data
- Grouping areas with similar accessibility to amenities
- Providing interactive visualizations for decision-making

---

## 🛠️ Tech Stack

| Component | Tools Used |
|----------|-----------|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn (K-Means Clustering) |
| Mapping & Geo Visualization | Folium, Geopy, Foursquare API |
| Workspace | Google Colab / Jupyter Notebook |

---

## 📌 Workflow

1. **Data Collection** from user preference dataset + geolocation API  
2. **Data Cleaning** (handling NaN, scaling, feature extraction)  
3. **Exploratory Data Analysis (EDA)**  
   - Pair Plot
   - Box Plot
   - Distribution & Outlier Analysis
4. **Elbow Method** used to find optimal **K** for clustering  
5. **K-Means Clustering** applied to group locations  
6. **Interactive Map Visualization** created using Folium  

---

## 🌍 Key Result

| Cluster | Description | Ideal For |
|--------|-------------|-----------|
| **Cluster 0 (Green)** | High restaurants, gyms & cafes | Social & active lifestyle |
| **Cluster 1 (Yellow)** | Limited amenities | Budget accommodation |
| **Cluster 2 (Red)** | Gyms high, fewer food outlets | Fitness-oriented users |

Output includes **interactive map** showing these clusters geographically.

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/Exploratory-Analysis-of-Geolocational-data.git
pip install -r requirements.txt
