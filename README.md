## ☕ Mérida Coffee Shops Market Analysis

This project explores and analyzes coffee shop presence in Mérida (Yucatán, Mexico). It includes data extraction, cleaning, exploratory data analysis (EDA), and visualization using Python of the local coffee-shops in the city. The goal is to gain insights into the distribution, types, and characteristics of coffee shops.

---

### 🧰 Motivation

- I wanted a create my own real-world dataset and working with a API.

- Coffee culture is growing in the region and offers interesting spatial & business-insight analysis.

- This is a portfolio project to showcase:

    - Data extraction / scraping / gathering

    - Data cleaning & preparation

    - Exploratory analysis & visualization

---

### ⚙️ Methodology & Technical Stack

#### 1. Data Acquisition
* **Source:** Google Places API (Text Search & Place Details Services).
* **Technique:** Implemented a Geospatial Gridding Workflow to systematically partition the city 

#### 2. Data Processing & Engineering
* Cleaned raw data (748 records) to remove noise and non-relevant businesses.
* Engineered key features, including **Average Transaction Price (`avgPrice`)** and **Postal Code**, for segmented analysis.

#### **Technical Stack**
* **Language:** Python
* **Libraries:** pandas, numpy, Folium, matplotlib, seaborn
* **Environment:** Jupyter Notebooks

---

*Due to GitHub notebook limitations, it is recommended to view the notebooks from the following links to visualize the maps created in Folium*:

[Data Extraction Notebook](https://nbviewer.org/github/cj-chavarria/Merida-Coffee-Shops-Analysis/blob/main/data_extraction.ipynb)

[Exploratory Data Analysis Notebook](https://nbviewer.org/github/cj-chavarria/Merida-Coffee-Shops-Analysis/blob/main/coffee-shops-analysis.ipynb)