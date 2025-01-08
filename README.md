# NBA Player Performance Analysis and Tiering

A comprehensive sports analytics project clustering NBA players into performance tiers and ranking them within clusters based on metrics like scoring, efficiency, and defense. The project leverages clustering algorithms (K-Means, DBSCAN, Hierarchical) and player ranking techniques to support strategic decision-making for teams and coaches.

This repository contains the **NBA Player Performance Tiering** project, a data-driven exploration of player performance in the NBA. The project clusters players into distinct performance tiers using unsupervised machine learning techniques and ranks players within each cluster to provide actionable insights for team strategies and roster optimization.

---

## 📜 **Project Overview**

The project analyzes multi-season NBA player statistics to group players into archetypes and rank them based on key performance metrics. By leveraging clustering algorithms and ranking techniques, this analysis helps teams identify consistent performers, emerging talent, and optimal roster constructions.

### **Objectives**
1. Cluster NBA players into performance tiers based on offensive, defensive, and efficiency metrics.
2. Rank players within each tier to identify standout performers.
3. Provide insights to improve team strategy, player evaluation, and talent development.

---

## 🚀 **Key Highlights**

### **Technical Approach**
1. **Data Preprocessing**:
   - Cleaned the dataset and created new features like "Points Per Minute."
   - Addressed missing values and normalized features using StandardScaler.

2. **Dimensionality Reduction**:
   - Reduced high-dimensional data to three principal components using PCA to retain variance and simplify clustering.

3. **Clustering Algorithms**:
   - **K-Means**: Achieved moderate silhouette scores (0.3116) with optimal K=5 using the elbow method.
   - **DBSCAN**: Outperformed other models with a silhouette score of 0.4352 (eps=1.0, min_samples=3).
   - **Hierarchical Clustering**: Provided two well-separated clusters with a silhouette score of 0.3772.

4. **Player Ranking**:
   - Developed a weighted aggregate scoring system incorporating metrics like Points, Assists, and Field Goal Percentage.
   - Ranked players within clusters and identified the best 5-man lineups for teams across seasons.

5. **Evaluation Metrics**:
   - Silhouette Score: Measures cohesion and separation of clusters.
   - Inertia: Evaluates compactness of K-Means clusters.

---

## 📊 **Key Findings**

1. **Top Clustering Results**:
   - DBSCAN provided the best clustering performance with 5 distinct clusters and the highest silhouette score (0.4352).
   - Hierarchical clustering revealed nested relationships among players, aiding granular analysis.

2. **Insights**:
   - Clustering identified archetypes such as high-scorers, defensive anchors, and efficient playmakers.
   - Ranking within clusters highlighted standout players across different archetypes.

3. **Team-Level Insights**:
   - Generated ranked rosters and identified the best 5-man lineups for each team and season.

---

## 🌟 **Impact and Implications**

This project provides actionable insights for:
- **Team Management**: Optimize rosters and identify undervalued players.
- **Player Evaluation**: Compare players within archetypes to highlight strengths and weaknesses.
- **Strategic Planning**: Construct ideal lineups based on performance metrics.

---

## 🛠️ **Technologies Used**

- **Programming Language**: Python
- **Libraries**: 
  - Pandas, NumPy for data preprocessing.
  - Scikit-learn for clustering and evaluation.
  - Matplotlib, Seaborn for visualization.
- **Machine Learning Techniques**:
  - K-Means, DBSCAN, Hierarchical Clustering.

---

## 💡 **Future Directions**
1.	**Enhanced Feature Engineering**:
   - Incorporate advanced metrics like Player Impact Estimate (PIE) or Real Plus-Minus (RPM).
2.	**Predictive Analytics**:
   - Use player archetypes to predict team success or evaluate trade scenarios.
3.	**Interactive Visualizations**:
   - Develop dashboards to explore player tiers and rankings dynamically.
4.	**Real-Time Analysis**:
   - Integrate live game data to provide real-time insights for coaches and analysts.
     
---

## 🔗 **Portfolio & Contact**

This project is part of my Data Science Portfolio, showcasing my expertise in sports analytics and machine learning. For inquiries or collaborations, feel free to contact me:
	•	Email: shayan.raja123@gmail.com
	•	LinkedIn: 
