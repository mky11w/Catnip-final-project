# What is the Best Neighborhood in Pittsburgh?  
### By Team Catnip🌿  
*Makayla Chang mac1055@pitt.edu , Dylan Dimond dyd19@pitt.edu , Tingxu Chen tic128@pitt.edu*

---

## Overview

This project explores the question: **What is the best neighborhood in Pittsburgh?** Using a **data-driven, multi-dimensional approach**, we built a composite index to evaluate and compare neighborhood performance across the city.

We used three key public datasets:

- **Police Arrest Data** – to evaluate public safety  

- **311 Service Requests** – to gauge community responsiveness and livability  

- **Allegheny County Public Assets** – to assess access to essential community resources

Each dataset contributes to one submetric in our scoring system, allowing us to compare neighborhoods across **safety**, **resident concerns**, and **access to amenities**.

---

## Scoring Methodology

All submetrics were normalized to a **100-point scale**. We then calculated a composite score for each neighborhood using the following weights:

- **Safety Index** (Police Arrests) – 35%  
- **Responsiveness Index** (311 Calls) – 35%  
- **Amenity Index** (Public Assets) – 30%

The formula ensures a fair balance between infrastructure and lived experience, with a slight emphasis on basic quality-of-life factors like safety and responsiveness.

---

## Key Results

### **Top Neighborhood: North Oakland** 🎉  
- **Composite Score**: 88.32  
- **Safety Index**: 93.16  
- **Responsiveness Index**: 87.69  
- **Amenity Index**: 83.42  

North Oakland leads the pack with high scores across all categories — a strong indication of overall livability and service equity.

---

## Data Visualization

We included two primary forms of visualization:
- **Histogram** showing that the composite score distribution follows a roughly **normal curve**, suggesting statistical consistency.
- **Spatial choropleth maps** that highlight geographic disparities and the performance of each neighborhoods across the city.

---

## Highlights from Each Submetric

- **Police Arrests**: Neighborhoods like Central Northside and New Homestead showed the lowest arrest counts, signaling stronger perceived safety.
- **311 Calls**: Sheraden, Esplen, and New Homestead had minimal reported issues, suggesting higher satisfaction or lower disruption.
- **Public Assets**: Central Business District, Squirrel Hill South, and Shadyside ranked highest in access to parks, libraries, and health centers.

---

## Final Thoughts

While no single score can fully capture the lived experience of residents, our approach offers a **transparent, replicable framework** for understanding neighborhood-level conditions in Pittsburgh. It can serve as a foundation for **urban planning**, **policy-making**, and **community engagement**.

---
## 📁 Folder Structure

```
.
├── Appendix.ipynb
├── Catnip_Final_Report.ipynb
├── Dylan - Arrest Analysis
│   ├── ArrestData_updated.csv
│   ├── CensusCounts.csv
│   ├── PoliceArrestData.ipynb
│   ├── cleaned_arrested.csv
│   ├── correlation.csv
│   ├── result.csv
│   └── result.ipynb
├── Makayla - 311 data analysis
│   ├── 311_counts_by_neighborhood.csv
│   ├── Neighborhood boundaries
│   ├── draft.py
│   ├── filtered_311.csv
│   └── job.ipynb
├── README.md
└── tingxu_vibe_score
    ├── data
    ├── data_cleaned
    ├── data_score
    ├── heartmap_index.ipynb
    ├── notebook
    └── tingxu_final_score.csv

9 directories, 17 files
```
---

## Data Sources

- [Pittsburgh Police Arrest Data](https://data.wprdc.org/dataset/arrest-data)
- [311 Service Request Data](https://data.wprdc.org/dataset/311-data)
- [Allegheny County Public Assets](https://data.wprdc.org/dataset/allegheny-county-assets)
