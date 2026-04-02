# 🛡️ SafeCity – Crime Data Analysis (India)

A complete data analysis & visualization project exploring crime trends, hotspots, and victim patterns across major Indian cities using Python, Pandas, Plotly, and Folium.  
This project reveals insights that support crime prevention and decision-making.

---

## 📌 Project Overview

This project analyzes crime records across **30+ Indian cities**.  
It includes:

- 📍 **City-wise crime analysis**  
- 📊 **Crime category distribution**  
- 👤 **Victim demographics analysis**  
- ⏰ **Time-based crime patterns (year/month/hour)**  
- 🗺️ **Geospatial visualizations (heatmaps + interactive maps)**  
- 🔥 **Crime hotspots detection**  

The goal is to understand **when**, **where**, and **what types** of crimes occur most frequently.

---

## 📁 Dataset

**File:** `crime_dataset_india.csv`  
**Total Records:** ~40,000  

### Important Columns
- City  
- Crime Description  
- Crime Domain  
- Weapon Used  
- Victim Age  
- Victim Gender  
- Date of Occurrence  
- Time of Occurrence  
- Case Closed  
- Police Deployed  

Latitude/longitude coordinates were added manually for mapping.

---

## 🧹 Data Cleaning & Preparation

Steps performed:

- ✔ Removed missing/inconsistent data  
- ✔ Cleaned & standardized city names  
- ✔ Converted date/time into proper datetime formats  
- ✔ Extracted features: `year`, `month`, `hour`  
- ✔ Added geolocation data (latitude/longitude)  
- ✔ Dropped duplicates  
- ✔ Prepared dataset for EDA & mapping  

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Crime Frequency by City  
Bar charts showing cities with the highest reported crimes.

### 🔹 Crime Type Distribution  
Charts visualizing:
- Theft  
- Assault  
- Fraud  
- Cybercrime  
- Public intoxication  
- Vandalism  

### 🔹 Victim Demographics  
- Age distribution  
- Gender-based trends  

### 🔹 Time-Based Crime Patterns  
- Yearly trends  
- Monthly seasonality  
- Peak hours (evening & night)  

---

## 🗺️ Geospatial Visualizations

### 🔥 Crime Heatmap (Folium)
An interactive heatmap highlighting high-crime-density areas.  

Generated file:
```
crime_heatmap.html
```

Open the file in your browser.

---

### 🌍 Interactive Crime Map (Plotly Mapbox)
Visualizes crime distribution with:

- Hoverable details  
- Color-coded crime intensity  
- Zoom & pan controls  

---

## 📝 Key Insights

- Mumbai, Delhi, Chennai, and Hyderabad show **highest crime densities**  
- Crimes peak during **evening and late-night hours**  
- Most common crimes: **Theft, Assault, Fraud, Cybercrime**  
- Male victims appear more frequently  
- Cities show unique crime-domain patterns  

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|--------|
| Language | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Plotly |
| Mapping | Folium (Heatmaps), Plotly Mapbox |
| Notebook | Jupyter Notebook / VS Code |

---

## 🚀 How to Run the Project

### Clone the repository
```bash
git clone https://github.com/Nish232003/SafeCity-Crime-Data-Analysis.git
```

### Install dependencies
```bash
pip install -r requirements.txt
```

### Run the notebook
Open:
```
crimes-in-india-analysis.ipynb
```

### Generate & view heatmap
```python
m.save("crime_heatmap.html")
```

Open the HTML file in your browser.

---

## 📸 Screenshots
<img width="1884" height="875" alt="image" src="https://github.com/user-attachments/assets/06c8e554-680b-4e34-8f36-e0b7eafa2df7" />
<img width="1900" height="866" alt="image" src="https://github.com/user-attachments/assets/2f574d71-c439-4a15-8e77-de8b71598b54" />
<img width="1919" height="919" alt="image" src="https://github.com/user-attachments/assets/756c9190-da53-4c40-a7ec-8ae7f7686322" />


```

```

---

## 🤝 Contributions

Contributions and suggestions are welcome!  
Open an issue or submit a pull request.

---

## 👤 Author

**Nishita**  
GitHub: https://github.com/Nish232003

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub!
