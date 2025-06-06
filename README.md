# US Golf Course Access & Player Origins

This project explores the geographic accessibility of golf courses in tbe United States and how access may relate to the hometowns of top PGA and LPGA players.

---

## Repo Structure

### /cleaning/
This folder contains two notebooks:
- `gc_data.ipynb` — Scrapes global golf course data, locates missing latitudes and longitudes, and cleans values.
- `gc_data_rank.ipynb` — Gathers 2025 PGA and LPGA player rankings, stats, and hometown coordinates.

### /preprocessing/
This folder contains one notebook:
- `gc_proj.ipynb` — Prepares a final `.csv` of all U.S.-based PGA and LPGA players, their rankings, and counts of golf courses within various distances from their hometowns.

---

## Summary

The project is broken into three main stages:

### 1. Data Cleaning
- Standardized U.S. golf course data.
- Normalized and merged player data from PGA and LPGA tours.

### 2. Preprocessing
- Used the Haversine formula to calculate the number of golf courses within:
  - 10 miles  
  - 25 miles  
  - 50 miles  
  - 100 miles
- Created a final dataset ready for Tableau visualizations.

### 3. Visualization (In Progress)
The Tableau dashboard will explore:
- Geographic distribution of players by state  
- Course access vs. professional output  
- Course density vs. player hometowns  
- Proximity of players to their nearest golf course (spatial join analysis)

---

## Tools

- Python: `pandas`, `numpy`, `seaborn`, `scipy`
- Jupyter Notebooks (via Kaggle)
- Tableau (in progress)
- GitHub for version control

---

## Intention

- Determine whether top-ranked golfers tend to come from golf-dense areas  
- Compare PGA vs. LPGA player access to local golf courses  
- Visualize the relationship between regional golf infrastructure and professional talent development  
- Build an interactive dashboard to communicate insights

---

*Note: Tableau visualizations coming soon.*
