# 📞 911 Calls Data Analysis

## 📌 Overview
This project performs an in-depth exploratory data analysis (EDA) on real-world **911 emergency call data** from Montgomery County, Pennsylvania. The goal is to uncover patterns in emergency call frequency, types, and temporal/geographical trends to derive actionable insights.

---

## 🎯 Objectives
- Understand the structure and characteristics of the dataset  
- Analyze the frequency of different emergency types (EMS, Fire, Traffic)  
- Explore temporal patterns (hour, day, month)  
- Identify trends across different townships  
- Generate insights useful for emergency response planning  

---

## 📊 Dataset
- **Source:** [Kaggle – 911 Calls Dataset](https://www.kaggle.com/datasets/mchirico/montcoalert)  
- **Size:** ~1.5 million records  
- **Key Features:**
  - `lat`, `lng` – Geographic coordinates  
  - `desc` – Emergency description  
  - `zip` – Zip code  
  - `title` – Type of emergency  
  - `timeStamp` – Date and time of call  
  - `twp` – Township  
  - `addr` – Address  
  - `e` – Dummy variable  

---

## 🛠️ Tech Stack
- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**

---

## 🔍 Data Analysis Workflow

1. Data loading and preprocessing  
2. Data cleaning and handling missing values  
3. Feature engineering (extracting hour, day, month from timestamps)  
4. Exploratory Data Analysis (EDA)  
5. Visualization of trends and patterns  
6. Insight generation  

---

## 📈 Key Insights
- EMS-related emergencies are the most frequent type of 911 calls  
- Call volumes peak during evening hours  
- Noticeable variation in call frequency across days of the week  
- Certain townships consistently report higher emergency volumes  
- Seasonal trends affect emergency call patterns  

---

## 📊 Visualizations
This project includes:
- Count plots of emergency types  
- Time-series line charts for call trends  
- Heatmaps (hour vs day)  
- Township-based analysis  

---

## 🧠 Learnings
- Gained hands-on experience with **large-scale real-world datasets**  
- Improved skills in **EDA and data visualization**  
- Practiced **feature engineering on time-series data**  
- Learned to extract **actionable insights for decision-making**  

---

## 🚀 Future Improvements
- Integrate **GeoPandas** for advanced geospatial analysis  
- Apply **clustering algorithms** to detect emergency hotspots  
- Build an **interactive dashboard** using Plotly or Power BI  
- Deploy insights via a web application  

---

## 📁 Project Structure
