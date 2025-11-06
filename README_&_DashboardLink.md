# Shoalhaven Water Flood Risk and Ponding Analysis

This project investigates the environmental and infrastructure factors associated with localised surface flooding (“ponding”) in the Shoalhaven region.  
The analysis supports data-driven decision-making for Shoalhaven Water, focusing on drainage planning and flood-risk mitigation.

---

## Project Overview

This repository contains the full workflow from raw data audit to exploratory analysis and final visualisation.

| Stage | File / Resource | Description |
|--------|-----------------|--------------|
| 1 | [`1_Data_Audit.ipynb`](1_Data_Audit.ipynb) | Audits and cleans the original *urban pluvial flood risk* dataset. The notebook checks data types, missing values, outliers, and category consistency; renames columns for clarity; and exports a cleaned version (`data/cleaned_flood_data2.csv`) for downstream use. |
| 2 | [`2_Exploratory_Analysis.ipynb`](2_Exploratory_Analysis.ipynb) | Performs exploratory data analysis on the cleaned dataset. Includes descriptive statistics, boxplots, rainfall-elevation comparisons, and correlation checks linking ponding status with soil type, drainage proximity, and rainfall intensity. |
| 3 | [Interactive Tableau Dashboard](https://public.tableau.com/views/GlobalPondingStatusParvaTS/Dashboard1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link) | Presents the global spread of ponding hotspots in a simple interactive Tableau Public dashboard |

---

## How to Run in Google Colab

Both notebooks are configured to run directly from this GitHub repository.

| Notebook | Link |
|-----------|------|
| Data Audit | [Open in Colab](https://colab.research.google.com/github/PaneerChilliDry/ParvaTSApplication_Shoalhaven_Water_Project/blob/main/1_Data_Audit.ipynb) |
| Exploratory Analysis | [Open in Colab](https://colab.research.google.com/github/PaneerChilliDry/ParvaTSApplication_Shoalhaven_Water_Project/blob/main/2_Exploratory_Analysis.ipynb) |

Each notebook begins with a short setup cell that automatically clones this repository so that relative file paths (for example, `data/cleaned_flood_data2.csv`) resolve correctly.  
After opening in Colab, select **Runtime → Run all**; no manual path edits are required.

---

## Tech Stack
| Component | Tools |
|------------|-------|
| Data Wrangling | Python - Pandas, NumPy |
| Visualisation (EDA) | Matplotlib, Seaborn |
| Dashboard | Tableau Public |
| Environment | Google Colab / Jupyter Notebook |

---

## Author
**Parva Teli-Shah**  
Bachelor of Information Technology (Data Science) & Economics – Macquarie University  
President, Macquarie University AI & Data Science Society (MQAIS)  
[LinkedIn](https://www.linkedin.com/in/parva-teli-shah-b4b28121a/) | [GitHub](https://github.com/PaneerChilliDry)

---

This repository was prepared as part of an application to Shoalhaven Water to demonstrate applied data-science capability in data auditing, exploratory analysis, and geospatial visualisation.
