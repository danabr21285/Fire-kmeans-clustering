# 🔢 K-means Clustering Analysis – FIRE Program

This project applies **K-means clustering** to analyze academic performance and testing outcomes among students in the FIRE (Focused Instructional Review & Enhancement) program. The goal was to identify underlying student profiles and examine how they relate to COMSAE performance.

---

## 🎯 Objectives

- Segment students into groups based on MCAT, GPA, COMSAE scores, age, and test-taking patterns
- Visualize the distribution and central tendencies of each cluster
- Inform program-level strategies for coaching, outreach, and support

---

## 📊 Variables Used

- `MCAT`  
- `MCAT Takes`  
- `Undergrad Science GPA`  
- `Age`  
- `COMSAE Score`

---

## 🧠 Methodology

- Variables normalized (mean = 0, SD = 1)
- Elbow method used to identify optimal number of clusters
- Final model: 4 clusters
- Cluster quality evaluated via:
  - Silhouette width
  - Variance explained
  - Dunn Index
- Profiles summarized in tables and bar charts

---

## 📷 Sample Outputs

- `elbow_plot.png` – Elbow method to select number of clusters  
- `Clusters.png` – Bar chart of students per cluster  
- `cluster_profiles_table.png` – Summary of means per cluster  
- `variance_explained_bar_chart.png` – Variance breakdown  
- `student_background_characteristics.png` – Related demographics

---

## 💡 Key Insights

- **Cluster 4**: Strongest academic profile (high MCAT & GPA, strong COMSAE scores)
- **Cluster 3**: Older students, fewer MCAT attempts, strong COMSAE despite risk markers
- **Cluster 2**: More MCAT attempts, lowest COMSAE performance
- **Cluster 1**: Slightly below average academic indicators

> Nearly **48.5%** of total variation was explained by the clustering solution.

---

## 📦 Files Included

- `fire_kmeans.R` – Main R script
- `FIRE Project(Clustering Analyses).pptx` – Final presentation summarizing the full clustering analysis (K-means + hierarchical)

---

## 🔗 Related Projects

- [FIRE Hierarchical Clustering](https://github.com/danabr21285/fire-program-clustering)
- [COMLEX Question Generator](https://github.com/danabr21285/comlex-question-generator)

---

## 👩‍🏫 Author

**Dana Brooks**  
Admissions Leader | Data Analyst | EdTech Strategist  
📧 danatallent@yahoo.com 
🔗 [LinkedIn](www.linkedin.com/in/dana-tallent-brooks-a15977a0)

---

> *“Data can help us spot trends—clustering helps us see the people behind them.”*
