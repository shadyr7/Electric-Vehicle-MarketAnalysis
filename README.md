# Electric Vehicle (EV) Market Segmentation in India (2001–2024)

This project presents a detailed analysis of India's electric vehicle (EV) market from 2001 to 2024. Using publicly available datasets, we explore trends in sales, infrastructure, and manufacturer performance. The analysis applies machine learning techniques to segment Indian states based on EV market maturity.

---

## Objectives

- Analyze EV sales trends across vehicle categories (2W, 3W, LMV)
- Compare infrastructure and production capacity across states
- Segment Indian states using K-Means clustering
- Visualize key metrics using PCA, bar charts, and line plots
- Generate strategic insights for investment and policy planning

---

## Datasets Used

- `ev_cat_01-24.csv` – Year-wise sales by vehicle category
- `Ev_by_place.csv` – State-wise EV sales, production, infra, and market share
- `OperationalPC.csv` – Number of public charging stations per state
- `Vehicle-Class-All.csv` – Total registrations by vehicle class
- `ev_sales_by_makers_and_cat.csv` – Sales by manufacturer and category
- `EV-Maker-by-Place.csv` – Manufacturer presence by location

---

## Tools and Libraries

- Python (Jupyter Notebook)
- pandas, numpy – data cleaning and manipulation
- matplotlib, seaborn – visualizations
- scikit-learn – clustering, scaling, PCA

---

## Key Visuals and Analysis

- EV sales trends from 2001 to 2024 by category
- Cumulative category share analysis (2W, 3W, LMV)
- Top states by charging station deployment
- K-Means clustering applied to market share, production capacity, infra, and sales
- PCA projection of state clusters
- Normalized cluster-wise feature comparison
- State-wise sales distribution by cluster

---

## Market Segmentation

States were grouped into the following segments based on clustering results:

- Mature EV Markets
- High-Growth States
- Transitional Markets
- Underdeveloped States

---

## Report

A detailed PDF report is available in the repository:  
`AadityaSinhaEV_Market_analysis.pdf`

