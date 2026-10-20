# Steam Market & Player Insights Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=seaborn&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

## Project Overview
An end-to-end data analytics project examining the PC gaming market and user behavior on **Steam**. The project demonstrates a full Data Science & Analytics workflow: from raw data preprocessing and exploratory analysis to statistical hypothesis testing and designing advanced SQL data marts.

---

## Repository Structure
The project is structured into clear, logical modules following Clean Code practices:
- **`src/1_EDA.ipynb`** — Exploratory Data Analysis (EDA), data cleaning, price distribution research, and genre trends using `Pandas` and `Seaborn`.
- **`src/2_SQL.ipynb`** — SQLite relational database pipeline: creating a local database, writing advanced analytical queries using **CTEs (`WITH`)**, **window functions (`RANK()`, `SUM() OVER()`)**, and conditional segmentation (`CASE WHEN`).
- **`src/steam_market.db`** — Local database file (automatically generated when running the notebooks, excluded from Git tracking via `.gitignore`).

---

## Tech Stack
- **Languages:** Python, SQL (SQLite)
- **Data & Statistics:** Pandas, NumPy, SciPy (hypothesis testing)
- **Visualization:** Matplotlib, Seaborn
- **Tools:** Jupyter Notebook, Git, VS Code

---

## Key Findings & Business Insights

### 1. Market Distribution by Price Segments
- Approximately **50% of the market** consists of budget games priced under $5. This confirms low barriers to entry and intense competition within the indie segment.
- Free-to-play (*Free*) titles account for around 10% of the market, serving as the primary acquisition engine for driving mass engagement.

### 2. Player Engagement Paradox (Review Analysis)
Comparing average positive and negative reviews across price tiers revealed key behavioral patterns:
- Despite representing the largest volume of games, budget titles (under $5) accumulate the lowest average review count.
- **Key Insight:** User engagement and activity peak at two distinct extremes:
  * **Free Games (*Free*)** — driven by maximum audience reach and low adoption friction.
  * **Premium Segment (Over $15)** — players who deliberately buy higher-priced games demonstrate much stronger engagement, complete titles, and actively share feedback (yielding both higher positive sentiment and a proportional volume of critique).

---

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/SonteikaMaki/Repos_Steam_project.git](https://github.com/SonteikaMaki/Repos_Steam_project.git)
