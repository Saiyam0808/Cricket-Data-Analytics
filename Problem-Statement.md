# 🏏 Problem Statement: Cricket Data Analytics

## 🎯 Objective

The aim of this project is to analyze player performance data across multiple cricket categories (e.g., Openers, Finishers, Anchors, Fast Bowlers, All-Rounders) and build a **data-driven Power BI dashboard** that:

- Evaluates individual player contributions using stats like strike rate, economy, average, etc.
- Assists in **automated team selection** by filtering the best-performing players by role.
- Provides interactive visualizations to explore performance insights by category and match role.
- Supports strategy planning by identifying player suitability for various match situations.

## 📊 Categories Analyzed

The dashboard evaluates the following cricket roles:

- 🧨 **Power Hitters & Openers**  
  ![Openers](images/power_hitters_and_openers.jpg)

- 🛡️ **Anchors**  
  ![Anchors](images/anchors.jpg)

- 🔚 **Finishers**  
  ![Finishers](images/finishers.jpg)

- 🌀 **All-Rounders**  
  ![All Rounders](images/all_rounders.jpg)

- ⚡ **Fast Bowlers**  
  ![Fast Bowlers](images/fast_bowlers.jpg)

## 🏁 Final Outcome

The outcome is a Power BI dashboard that:

- Enables dynamic selection of players to form the **Best Playing XI**  
  ![Final XI](images/pick_final_11.jpg)
- Visualizes performance across different formats or time ranges.
- Helps selectors or enthusiasts make informed decisions based on actual performance data.

## 📂 Dataset & Tools Used

- Collected via web scraping from [ESPNcricinfo](https://www.espncricinfo.com/)
- Cleaned & analyzed using **Python**, **Pandas**
- Dashboard built with **Power BI**
- Output exported as `.pbix` file

## 🔗 Files in This Repo

- [T20-data-processing.ipynb](./T20-data-processing.ipynb): Jupyter notebook for scraping & cleaning
- [T20-csv-files](./T20-csv-files/): Cleaned dataset
- [T20 Cricket Analytics Dashboard.pbix](./T20%20Cricket%20Analytics%20Dashboard.pbix): Power BI Dashboard file
- [Problem-Statement.md](./Problem-Statement.md): This file
- [Screenshots](./Screenshots/): Contains player category visuals used in dashboard


---

> This project demonstrates the power of sports analytics in optimizing team performance and enabling strategy-backed decision-making in cricket.
