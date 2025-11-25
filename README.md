# 🏥 COVID-19 Hospital Staffing Shortage Analysis

<p align="center">
  <img src="assets/banner.png" width="100%" />
</p>

This project analyzes hospital staffing shortages during the COVID-19 pandemic using Python, with a focus on data cleaning, exploratory analysis, visualizations, and PCA to identify hospital trends and operational patterns. All coding for this analysis was performed in Google Colab.

---

## 🔍 Project Overview

This project explores:

- Hospital staffing shortages  
- Admission and ICU strain  
- Bed usage and operational pressure  
- Clustering patterns using PCA  
- Key hospital-level COVID indicators  

The goal is to understand how COVID-19 impacted staffing pressure across U.S. hospitals using real-world data.

---

## 📈 Results

### ✔️ Key Insights

- Hospitals reporting frequent **staffing shortages** often showed higher patient load, ICU usage, and COVID admission spikes.  
- PCA revealed **distinct clusters** of hospitals experiencing similar operational stress.  
- Certain facilities consistently appeared as outliers, indicating unusually high or low COVID impact.  
- Histogram and boxplot analysis showed highly skewed distributions for admissions and shortage indicators.

### ✔️ Summary Observations

- Hospitals under heavy COVID load experienced significantly more staffing strain.  
- PCA reduced dozens of variables into simple components that clearly separated stressed vs. stable hospitals.  
- Visualizations revealed patterns not obvious in the raw dataset.

---

## 📉 PCA Visuals

This project uses PCA to reduce dimensionality and visualize hospital patterns.

The main plot generated:

- **Principal Component 1 (PC1)** – captures variation related to overall hospital load  
- **Principal Component 2 (PC2)** – captures variation related to staffing strain  
- **Scatter plot** shows grouping of hospitals by operational similarity  

PCA plot is saved as:
```
assets/pca_plot.png
```

## 📁 Project Structure
```
covid-hospital-staffing-analysis/
├── data/
│ └── COVID-19_.csv
├── src/
│ └── staffing_analysis.py
├── assets/
│ └── banner.png
└── README.md
```


---

## 🛠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-Learn (PCA)  
- Google Colab  

---

## 👤 Author

**Bhavya Pandya**
