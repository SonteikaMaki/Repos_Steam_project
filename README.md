# Steam Market & Player Insights Analysis

## Project Overview
An end-to-end data analytics project examining the Steam video game market. The study covers data cleaning, exploratory data analysis (EDA), statistical hypothesis testing, and advanced SQL data mart generation using window functions and conditional aggregation.

---

## Repository Structure
The project is structured into clear modules in accordance with clean code principles:
* **`src/1_EDA.ipynb`** — Exploratory Data Analysis, missing value handling, price distribution analysis, and genre trends using Pandas and Seaborn.
* **`src/2_SQL.ipynb`** — SQLite relational database setup, complex analytical queries using Common Table Expressions (CTEs), window functions (`RANK()`, `SUM() OVER()`), and conditional segmentation (`CASE WHEN`).
* **`src/steam_market.db`** — Local SQLite database file (generated automatically upon running the notebooks, excluded from Git tracking via `.gitignore`).

---

## Tech Stack
* **Languages:** Python, SQL (SQLite)
* **Data & Statistics:** Pandas, NumPy, SciPy
* **Data Visualization:** Matplotlib, Seaborn
* **Tools:** Jupyter Notebook, Git, VS Code

---

## Key Findings & Business Insights

### 1. Market Distribution by Price Segments
* Approximately 50% of the market consists of budget games priced under $5. This highlights low barriers to entry and intense competition within the indie segment.
* Free-to-play titles account for around 10% of the market, serving as a primary driver for mass user acquisition.

### 2. Player Engagement Paradox (Review Analysis)
Comparing average positive and negative reviews across price tiers revealed critical behavioral insights:
* Despite budget titles (under $5) representing the largest market share, they record the lowest average review counts.
* Key Insight: User engagement and review volume peak at two distinct ends of the spectrum:
  * Free Games: Driven by maximum user reach and low adoption friction.
  * Premium Segment (Over $15): Players making higher financial commitments are significantly more engaged, completing games and actively leaving feedback (resulting in higher positive sentiment as well as proportional critical feedback).

---

## How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/SonteikaMaki/Repos_Steam_project.git](https://github.com/SonteikaMaki/Repos_Steam_project.git)
