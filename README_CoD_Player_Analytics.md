# 🎮 Call of Duty Player Retention & Engagement Analytics

### 📊 Overview
This project simulates *Call of Duty* multiplayer player telemetry data to analyze engagement, performance, and retention patterns. It demonstrates how data science can support game balance and player experience optimization—aligned with Activision Blizzard's Player Science and Mobile Analytics teams.

### 🧠 Objectives
- Explore player behavior metrics (kills, deaths, accuracy, sessions)
- Model **next-day player return probability**
- Simulate an **A/B test** for gameplay tuning (e.g., reduced weapon recoil)
- Export Tableau-ready dataset for visualization

### ⚙️ Tools & Techniques
- **Python:** pandas, numpy, scikit-learn, matplotlib, scipy
- **Modeling:** Random Forest Classifier
- **Testing:** A/B testing (t-test on retention rates)
- **Visualization:** Matplotlib + Tableau-ready CSV export

### 📈 Insights
- Higher engagement (sessions_last_7d) and skill (K/D ratio) correlate with stronger retention.
- Group B’s gameplay tweak increased retention by ~5% (statistically significant).
- Long-term engagement linked to rank progression and total playtime.

### 📁 Contents
- `CoD_Player_Retention_Analytics.ipynb` – full notebook (EDA, modeling, A/B test)
- `cod_player_data.csv` – simulated player telemetry data (10,000 sessions)

---
🕹️ *“Turning gameplay data into winning insights.”*
