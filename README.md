# Injury Impact Insight: Elite Football Performance EDA

## 📌 Project Overview
This project provides a comprehensive **Exploratory Data Analysis (EDA)** investigating the frequency, nature, and impact of injuries on professional football players. [cite_start]By analyzing a multi-season dataset spanning 2019–2024 [cite: 1, 12, 20, 25, 31][cite_start], the study quantifies how injury layoffs correlate with individual performance ratings and team match outcomes across top-tier clubs like **Arsenal, Manchester United, Newcastle United, Everton, Brentford, and Burnley**[cite: 1, 43, 95, 127, 151, 166].

## 📊 Key Features & Insights
* [cite_start]**Injury Severity Analysis:** Calculation of recovery durations by comparing "Date of Injury" and "Date of Return" across different injury types, such as hamstring strains and cruciate ligament tears[cite: 1, 2, 5].
* [cite_start]**Performance Delta:** Comparative analysis of player performance ratings immediately before and after injury intervals[cite: 1].
* [cite_start]**Tactical Impact Tracking:** Evaluation of team performance (Goal Difference and Match Results) during a player's absence to identify the impact of missing key squad members[cite: 1, 138, 151].
* [cite_start]**Demographic Correlations:** Investigating the relationship between player age, FIFA rating, and susceptibility to specific injury categories[cite: 1].

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 📂 Dataset Description
[cite_start]The analysis utilizes a detailed dataset (`player_injuries_impact.csv`) containing over 650 records with the following attributes[cite: 1]:
* [cite_start]**Player Metadata:** Name, Team Name, Position, Age, Season, and FIFA rating[cite: 1].
* [cite_start]**Injury Data:** Specific injury type, Date of Injury, and Date of Return[cite: 1].
* [cite_start]**Match Performance:** Match results, opposition, goal difference (GD), and individual player ratings for the three matches before, during (missed matches), and after the injury period[cite: 1].

## 🚀 How to Use
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourUsername/Injury-Impact-Insight.git](https://github.com/YourUsername/Injury-Impact-Insight.git)
    ```
2.  **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Run the Analysis:**
    Open `EDA_Football.ipynb` in Jupyter Notebook or VS Code to view the data pipeline and visualizations.

## 📈 Sample Results
The project includes visualizations such as:
* [cite_start]**Injury Distribution:** Analysis of common injury types across different tactical positions[cite: 1].
* **FIFA Rating vs. Recovery:** Scatter plots investigating if higher-rated players have different recovery timelines.
* [cite_start]**Team Performance Heatmaps:** Visualizing dips in match results and goal differences during the absence of key defensive or offensive players[cite: 1].

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
**Developed by [Your Name]** *Data-driven insights into the beautiful game.*
