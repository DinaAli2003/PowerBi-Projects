# 🏀 NBA Analytics Dashboard

An interactive **data analytics and visualization dashboard** designed to provide comprehensive insights into NBA game performance, team efficiency, historical trends, draft analytics, and player combine metrics.

This project transforms raw NBA data into a **structured data warehouse** and delivers actionable insights through **SQL analysis and Power BI dashboards**.

---

## 📊 Dashboard Overview

The dashboard integrates multiple analytical perspectives, enabling users to explore:

* League-wide performance metrics
* Team and game analytics
* Historical trends across seasons
* Player draft and combine data

It is built on a **star schema data warehouse**, ensuring efficient querying and scalable analytics.

---

## 📌 Key Metrics

| Metric                      | Value   |
| --------------------------- | ------- |
| **Total Games**             | 58,000+ |
| **Total Points**            | 12M+    |
| **Average Points per Game** | 205.55  |
| **Average Points per Team** | ~102.77 |
| **Home Win Percentage**     | 61.95%  |
| **Away Win Percentage**     | 38.05%  |
| **Average Field Goal %**    | 46.10%  |

---

## 🏆 Game Performance Analysis

* Home teams demonstrate a clear **competitive advantage**, winning nearly **62% of games**
* Average scoring:

  * Home teams: **104.61 points**
  * Away teams: **100.94 points**
* Close game analysis highlights competitiveness based on **point differentials**
* Historical trends show fluctuations in scoring patterns across different eras

---

## 📈 Team Analytics

### 🔝 Top Teams by Total Points

* Boston Celtics
* Golden State Warriors
* Los Angeles Lakers
* Philadelphia 76ers
* New York Knicks

These teams consistently rank among the top performers in total scoring across historical data.

### 📊 Team Performance Insights

* Win percentage and scoring efficiency analyzed per team
* Home vs away performance comparison
* Offensive and defensive rankings derived from scoring metrics
* Identification of **“clutch teams”** based on close-game wins

### 🎯 Shooting Performance

* League-wide FG% ≈ **46.10%**
* Comparative analysis highlights top shooting teams and efficiency patterns

---

## 🏅 Player Draft Analytics

### 📌 Key Draft Statistics

| Metric                 | Value   |
| ---------------------- | ------- |
| Total Draft Picks      | ~3,500+ |
| Total Drafted Players  | ~3,500  |
| First Round Picks      | 74      |
| Average Draft Position | 30.78   |

### 📊 Insights

* Draft distribution across rounds shows a higher concentration in later rounds
* Teams like **Sacramento Kings** and **Golden State Warriors** lead in total draft selections
* Draft data enables analysis of team strategies and talent acquisition trends

---

## 🏋️ NBA Combine Analytics

### 📏 Physical Performance Highlights

| Metric                | Value    |
| --------------------- | -------- |
| Highest Vertical Leap | 48.00"   |
| Fastest Sprint        | 2.96 sec |
| Average BMI           | 24.10    |

### 📊 Insights

* Analysis of player physical attributes (height, weight, BMI)
* Relationship between **height and performance metrics** (vertical leap, sprint speed)
* Identification of top-performing athletes in combine tests

---

## 📅 Historical & Season Trends

* Long-term analysis reveals **evolution of scoring patterns**
* Points per game show fluctuations across decades
* Competitive intensity (point differential) has generally increased over time
* Attendance and performance trends highlight league growth

---

## 🗄️ Data Architecture

This project is built using a **Data Warehouse with Star Schema design**:

### ⭐ Fact Tables

* `Fact_Game` → Game performance metrics
* `Fact_Draft` → Draft data
* `Fact_Combine` → Player physical data

### 📂 Dimension Tables

* `Dim_Player`
* `Dim_Team`
* `Dim_Date`
* `Dim_Game_Info`

### ✅ Benefits

* Optimized query performance
* Simplified reporting
* Scalable analytical model
* Seamless integration with Power BI

---

## 🛠️ Technologies Used

* **SQL Server (SSMS)** – Data storage & querying
* **SQL** – Data transformation & analytics
* **Power BI** – Dashboard visualization
* **SQLite** – Original dataset source

---

## 📊 Dashboard Features

* Interactive filtering by team, season, and player
* Drill-down capabilities for detailed analysis
* Multi-dimensional insights across:

  * Games
  * Teams
  * Drafts
  * Player performance

---

## 🚀 How to Use

* Navigate through dashboard sections (Game, Team, Draft, Combine, Season)
* Use filters to explore specific teams or time periods
* Hover over charts for detailed insights
* Compare metrics across multiple dimensions

---

## 📁 Data Source

* NBA datasets from Kaggle
* Historical game records, draft data, and combine measurements
* Data spans multiple decades of NBA history

---

## 👥 Team

* **Dina Ali** – Data preparation, modeling, and analytics
* Marwa Ahraf
* Nada Shady
* Nada Emad
* Developed as part of the **Digilians Initiative**

---

## 🏛️ Program

This project was developed under the **Digilians Initiative**,
supervised by the **Ministry of Communications and Information Technology (MCIT)**
in collaboration with the **Egyptian Military Academy**.

---

## 📌 Conclusion

The NBA Analytics Dashboard provides a **comprehensive and scalable analytical solution** for understanding basketball performance. By combining **data engineering, SQL analytics, and visualization**, the project delivers valuable insights into:

* Team strategies
* Game dynamics
* Player performance
* Historical trends


