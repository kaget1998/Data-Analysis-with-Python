# 🎵 Spotify Songs Exploratory Data Analysis (2015–2025)

## 📌 Project Overview
This project performs **end-to-end Exploratory Data Analysis (EDA)** on a large Spotify songs dataset (2015–2025) to understand **song popularity trends** and how various **audio features influence popularity**. The analysis is carried out using **Python, Pandas, and Seaborn**, with a focus on clean data processing and insightful visualizations.

---

## 🎯 Objectives
- Analyze factors influencing song popularity  
- Identify trends in music characteristics over time  
- Perform feature engineering on real-world data  
- Create advanced and meaningful visualizations using Seaborn  

---

## 📂 Dataset Information
- **Source:** Spotify music dataset  
- **Records:** 85,000+ songs  
- **Key Features:**
  - popularity
  - danceability
  - energy
  - loudness
  - tempo
  - explicit
  - release_date
  - genre
  - stream_count

---

## 🛠️ Tools & Technologies
- **Language:** Python  
- **Libraries:** Pandas, Seaborn, Matplotlib  
- **Environment:** Jupyter Notebook  

---

## 🔧 Project Workflow
1. Data loading and inspection  
2. Data cleaning and missing value handling  
3. Feature engineering (`release_year`, `year_group`)  
4. Univariate, bivariate, and multivariate analysis  
5. Advanced data visualization  
6. Insight generation and conclusions  

---

## 📊 Visualizations Used
- **Histogram:** Popularity distribution  
- **JointPlot:** Danceability vs Popularity  
- **Violin Plot:** Popularity by explicit content  
- **FacetGrid:** Popularity trends across year groups  
- **Heatmap:** Correlation between audio features  

---

## 📈 Key Insights
- Danceability and energy positively influence popularity  
- Explicit songs show slightly higher median popularity  
- Energy and loudness are strongly correlated  
- Music popularity trends evolve significantly over time  

---

## 🧠 Skills Demonstrated
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Data Visualization (Seaborn)  
- Debugging & problem solving  
- Analytical thinking and storytelling  

---

## ⚠️ Challenges & Solutions
**Challenge:**  
- Encountered a `KeyError` due to a missing `release_year` column  

**Solution:**  
- Inspected dataset schema and derived `release_year` from `release_date`, enabling accurate time-based analysis  

---

## 🚀 Future Enhancements
- Build a machine learning model to predict song popularity  
- Genre-wise and country-wise analysis  
- Interactive dashboards using Power BI or Tableau  

---

## 📁 Project Structure
├── Spotify_Seaborn_EDA_Project_Fixed.ipynb
├── spotify_2015_2025_85k.csv
└── README.md

yaml
Copy code

---

## 🏁 Conclusion
This project demonstrates a complete EDA workflow on a real-world dataset, highlighting the ability to clean data, engineer features, create advanced visualizations, and extract actionable insights.

---

⭐ If you found this project helpful, feel free to star the repository!
