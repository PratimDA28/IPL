# 🏏 IPL Exploratory Data Analysis (EDA) Project

Welcome to the **IPL EDA Project**, where cricket meets data! This project dives deep into IPL (Indian Premier League) statistics from 2008 to 2024, uncovering trends, insights, and performance metrics that both cricket fans and data enthusiasts will enjoy. 🎉

---

## 📘 Downloads

- [Download Visualization PDF](#) – Summary of all visualizations 📄  
- [Download EDA FULL VIEW HTML](#) – Full EDA code with interactive charts  
- [Download EDA FULL VIEW PDF](#) – In-depth visual summary  

---

## 📂 Project Structure

### 1. Data Collection
- Data sourced from Kaggle.
- Covers IPL matches from **2008 to 2024**.
- Some discrepancies corrected for accuracy.

### 2. Data Cleaning
- Handled missing values and fixed naming inconsistencies:
  - `Delhi Daredevils` ➜ `Delhi Capitals`
  - `Royal Challenger Bangalore` ➜ `Royal Challengers Bangalore`
  - `M Chinnaswamy Stadium, Bengaluru` ➜ `M Chinnaswamy Stadium`
  - …and more.

### 3. Libraries Used
- `pandas`
- `plotly`
- `plotly.express`

---

## 📚 Project Overview

We analyzed IPL data to answer **24+ key questions**, including:

### 🔹 Match & Stadium Analysis
- Which stadium hosted the most matches?
- What’s the total runs scored across seasons?
- Venue-wise toss-win vs. match-win analysis.

### 🔹 Toss & Win Trends
- Who won the most tosses?
- What decisions were taken post-toss?
- Which teams performed best after winning the toss?

### 🔹 Team Performance
- Tournament winners & number of titles.
- Head-to-head records.
- Lucky venues for each team.
- 200+ runs scored or defended by teams.

### 🔹 Player Performance
- 🏏 **Top batsmen** by total runs.
- 🎯 **Top bowlers** by total wickets.
- 🔬 **In-depth analysis of Virat Kohli**:
  - Run trends, dismissals, favorite opponents, innings comparison, etc.
- 🧠 **Bowler deep dive: Yuzvendra Chahal**:
  - Wickets by season, effectiveness, favorite venues, and batsmen.

### 🔹 Milestones & Records
- Most 200+ scores.
- Biggest victories by run margin.
- Most balls played, sixes, and fours.
- Highest strike rate during death overs.
- Most ‘Man of the Match’ awards.

---

## 🛠️ Key Features

### 🏟️ Stadium Insights
- **Wankhede Stadium** hosted the most matches: **118**

### 👨‍💻 Player Highlights
- **Virat Kohli** scored 973 runs in 2016 – Highest in a season.
- **Chris Gayle** – King of Sixes with 359 hits over the ropes.
- **Yuzvendra Chahal** – Top wicket-taker with 205 wickets.

### 🏆 Team Stats
- Most Titles: **CSK & MI (5 titles each)**
- CSK has 200+ runs in **32 matches**

### 💥 Special Moments
- **MI’s 146-run win over DC in 2017** – Biggest margin win.
- **MS Dhoni** leads with **42 stumpings**

---

## 📊 Visualizations

Built using **Plotly Express** and **Plotly Graph Objects**:

- **Line Charts** – Season-wise total runs
- **Bar Graphs** – Top players by runs, wickets, titles
- **Pie Charts** – Dismissal types, boundary breakdowns
- **Box Plots** – Innings-wise score distribution by team

---

## 🔧 How to Use the Project

### Prerequisites
- Python 3.x
- Required Libraries:
  ```bash
  pip install pandas plotly
