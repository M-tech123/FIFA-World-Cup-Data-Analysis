<div align="center">

# 🏆 **FIFA World Cup Data Analysis Dashboard**

<img src="https://upload.wikimedia.org/wikipedia/en/3/36/FIFA_World_Cup_Logo.png" width="180"/>

### 📊 Power BI | 🐍 Python | 📁 Excel | 🌐 Data Cleaning & Visualization


---

</div>

## 📘 **Overview**
This project focuses on **analyzing FIFA World Cup data (1930–2018)** using **Power BI**.  
The dataset includes details about **matches, players, goals, teams, and tournaments**.  
The main objective is to uncover **hidden insights** about team performance, players, goals, and hosting countries throughout the tournament’s history.

---

## 🎯 **Project Objectives**
- 🧹 Clean and standardize multiple raw datasets.  
- 🧩 Build data relationships across 8 interconnected tables.  
- 📈 Create interactive dashboards for deep exploration.  
- 🤖 (Optional) Integrate AI chatbot to answer data-related questions.  
- 💡 Deliver meaningful insights about the FIFA World Cup’s evolution.

---

## 🧠 **Key Insights Extracted**
- Most successful countries and their winning trends.  
- Top scoring players and their performance across tournaments.  
- Effect of *home advantage* on match results.  
- Most frequent stadiums and hosting countries.  
- Trends of red/yellow cards and their effect on final results.  
- Analysis of goals by half, timing, and type (Open, Penalty, Own Goal).  

---

## 🧹 **Data Cleaning Process**
To ensure data accuracy and consistency, several cleaning operations were performed:

| Step | Description |
|------|--------------|
| 🧩 Merging Columns | Combined `home_team` & `away_team`, and also `win`, `lose`, `draw` into single descriptive columns |
| 🗑️ Removed Redundancies | Deleted duplicated columns like `replay` and `replayed` |
| 🪶 Spelling & Encoding Fixes | Fixed “quater-finals” → “quarter-finals” and replaced (â€“) with (-) |
| 🔠 Standardized Groups | Unified group names to letters (A, B, C) instead of numbers |
| 🧾 Validated Matches | Ensured each match appears twice (home & away) |
| 👥 Players File | Created `full_name`, split `list_tournaments`, extracted `position`, fixed invalid `birth_day` |
| ⚽ Goals File | Removed text columns, replaced 0 shirt numbers, merged goal types, added `goal_side` column |

---

## 🗂️ **Data Model**
The model connects all datasets through key fields:
matches 
┬─< goals
├─< team_appearances
├─< players
└─< tournaments




> Relationships were established directly in **Power BI**, ensuring dynamic filtering and cross-visual interaction.

---

## 📊 **Dashboard Pages**

| Page | Description |
|------|-------------|
| 🏠 Overview | General tournament stats (matches, stadiums, geography) |
| 🌍 Host Country Performance | Performance & impact of host countries |
| 📊 Group Stage Analysis | Team performance and group difficulty |
| ⚽ Match & Goal Insights | Match-level goal breakdown and timing |
| 👥 Teams & Players | Participation, performance, and personal stats |
| 🥇 Player Performance & Fair Play | Top scorers, cards, and player discipline |
| 📈 Trends & Comparisons | Long-term trends and geographic comparisons |

---

## 🧩 **Tools & Technologies**
| Tool | Purpose |
|------|----------|
| **Power BI** | Data modeling, visualization & dashboards |
| **Excel** | Data exploration and validation |
| **Python (optional)** | Used for data preprocessing |
| **Canva / PowerPoint** | Presentation design |
| **ChatGPT API (Optional)** | For AI-based data Q&A system |


## 🚀 **How to Use**
1. Open `Power BI` file: `FIFA_WorldCup.pbix`
2. Refresh the data connections (Excel or CSV sources)
3. Navigate between dashboard pages using tabs
4. Explore insights interactively with filters & slicers

---

## 🧠 AI Chatbot Integration**
An AI chatbot (built with Streamlit + GEMINI API) can answer natural language questions about the data.

Example questions:
- “Which team scored the most goals in 2014?”
- “Who was the top scorer in 2018?”
- “How many matches were played in South America?”

---



<div align="center">

### ⚽ *“Data tells the story of every goal, every match, and every legend.”*  

---

