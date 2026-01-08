# Sports Analytics: NBA Player Performance, Similarity, and Outlier Analysis

## Intro

This project applies **sports analytics and data visualization techniques** to analyze **NBA player performance** using season-level and per‑36‑minute statistics. The goal is to understand how player scoring profiles, shot selection, and overall impact vary across the league, and to identify similarity structures and outliers among players.

The analysis combines **interactive Tableau visualizations**, **Python-based analytics**, and methods such as **PCA, MDS, and Local Outlier Factor (LOF)** to replicate professional-style sports analytics workflows.

---

## Research Questions

The project is guided by the following questions:

- How do NBA players differ in scoring style and efficiency?
- How has shot selection (2PT, 3PT, FT) evolved over time?
- Which players have similar statistical profiles across multiple performance dimensions?
- Which players stand out as statistical outliers relative to the league?
- How do PCA and MDS differ in how they represent player similarity?

---

## Data Sources

The analysis is based on data from the **Kaggle NBA / ABA / BAA player-season statistics dataset**, including:

- Regular season player totals
- Per‑36‑minute normalized statistics
- Career cumulative scoring data

---

## About the Data

Key attributes used in the analysis include:

- Player name, season, and position  
- Points, rebounds, assists  
- 2PT, 3PT, FT makes and attempts  
- Per‑36‑minute statistics  
- PCA and MDS coordinates  
- Local Outlier Factor (LOF) scores  

---

## Assignment Requirements Addressed

### Visual Exploration

- Career cumulative scoring trends  
- Shot type share by season  
- Player shot profile scatterplots  

### Analytics

- PCA projection of player similarity  
- MDS projection using Manhattan distance  
- Outlier detection using LOF  

---

## Key Findings

- NBA player performance forms a continuosu spectrum rather than strict clusters.
- Three‑point reliance has increased dramatically since the late 1970s.
- PCA captures broad variance, while MDS emphasizes dissimilarity.
- A small number of players exhibit extreme statistical profiles.

---

## Tools & Technologies Used

- Tableau  
- Python  
- Pandas / NumPy  
- Scikit‑learn  
- Jupyter Notebook  

