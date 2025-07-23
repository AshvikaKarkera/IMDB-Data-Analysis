# 🎬 IMDb Data Analysis Dashboard

An interactive and visually compelling Power BI dashboard that dives deep into the world of IMDb movies and TV shows.
This project uncovers fascinating insights across decades of entertainment — from how ratings correlate with popularity, to which countries and languages dominate the film industry. Explore trends in genres, discover top-rated titles, and visually analyze global content patterns. Whether you're a data enthusiast or a cinephile, this dashboard brings storytelling and analytics together in one dynamic visual experience.

---

## 📸 Dashboard Preview

### Analysis View  
<img width="1142" height="645" alt="image" src="https://github.com/user-attachments/assets/077af4b8-533b-411a-9e0e-1001152def68" />


### Exploration View  
<img width="1147" height="645" alt="image" src="https://github.com/user-attachments/assets/c8d4bb10-9834-4bca-a413-0b042e7c98ca" />

---

## 🧰 Tools & Technologies

- **Python** (pandas, matplotlib/seaborn) – for data cleaning & exploratory analysis  
- **Jupyter Lab / Notebook** – interactive EDA  
- **Power BI** – dashboard design & visuals  
---

## 📊 Dashboard Tabs Overview

### 1. Analysis  
- **Correlation: Ratings vs Votes** – Explore how vote count affects ratings  
- **Releases by Year** – Count of titles released over time  
- **Rating Distribution Over Time** – Track rating trends across decades  
- **Category Breakdown** – Proportion of Movies vs Episodes  

### 2. Exploration  
- **Top 5 Movies & TV Shows** – Highest-rated titles  
- **Top 5 Genres** – Most common content genres  
- **Top 5 Languages** – Title count by language  
- **Releases by Country** – Global release distribution visualized on a map  

---

## 🧹 Data Preprocessing Steps

1. Loaded raw IMDb dataset  
2. Handled missing/null values and type conversions  
3. Extracted release year and content category  
4. Aggregated stats for genres, languages, country distributions  
5. Exported processed data (`imdb_processed.csv`) for Power BI integration  

---

## 🚀 How to Use / Recreate

1. Clone or download this repository  
2. Run `IMDb.ipynb` to generate cleaned data  
3. Open `IMDb.pbix` in Power BI  
4. Recreate visuals using fields like:  
   - `Rating`, `Votes`, `Year`, `Genre`, `Language`, `Country`, `Category`  
5. Apply dark-themed visuals and navigation toggle between “Analysis” & “Exploration” tabs  

---
## 📜 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for more details.

---

## 👨‍💻 Author

**Ashvika Karkera**  
Email: [ashvikavk@gmail.com](ashvikavk@gmail.com)  
GitHub: [@AshvikaKarkera](https://github.com/AshvikaKarkera)
