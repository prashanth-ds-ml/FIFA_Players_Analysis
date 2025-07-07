# ⚽ FIFA 20 Player Data Analysis

## 📌 Overview

This project presents an in-depth **exploratory data analysis (EDA)** of the FIFA 20 player dataset. With over 18,000 players and 110+ features, this dataset provides rich information about player attributes, positions, clubs, and nationalities.

The goal of this project is to:
- Understand how different attributes relate to player performance
- Compare clubs and countries based on collective player statistics
- Examine trends in wage, value, potential, and skill
- Visually uncover patterns that impact scouting, valuation, and team-building

---

## 🔍 What Was Done (Step-by-Step)

### 🧹 1. Data Loading and Exploration
- Loaded the `players_20.csv` dataset (~18,483 players)
- Explored data types, missing values, and dimensionality
- Reviewed key player columns: `short_name`, `age`, `overall`, `potential`, `wage_eur`, `value_eur`, `preferred_foot`, etc.

### 📊 2. Wage Distribution and Top Earners
- Extracted top-paid players and visualized salaries
- Found that a small group of elite players earns significantly more than others (e.g., Messi, Ronaldo, Hazard)

### 📈 3. Rating and Age Distribution
- Plotted overall rating histogram → most players fall between **65–75 rating**
- Age vs. Overall Rating: Ratings tend to rise with age until ~30, then taper off
- Potential vs. Age: Younger players hold higher potential ceilings (up to 95)

### 🧬 4. Attribute-Based Visualizations
- **Wage vs Overall Rating**: Clear positive correlation, with some outliers
- **Height & Weight vs Rating**: Taller/heavier players skew toward defensive/goalkeeping roles
- **Preferred Foot vs Shooting**: Compared shooting distributions of left-footed vs right-footed players

### 🌍 5. Nationality and Club-Level Breakdown
- Counted top 10 nationalities by number of players (e.g., Argentina, Brazil, Spain)
- Calculated **average overall rating** and **average age** per nationality
- Identified top-performing countries (e.g., Belgium, Portugal, Spain)

### 🏟️ 6. Club Performance by Attribute
Grouped clubs and computed their **average scores** for:
- Passing
- Dribbling
- Defending
- Crossing
- Long Shots
- Aggression

This gave a unique “style profile” per club:
- FC Barcelona → top passing
- PSG → top dribbling
- Manchester City → top long shots
- Atlético Madrid → top aggression

### 🇵🇹 7. Deep Dive into Portugal
Filtered all 344 Portuguese players and analyzed:
- Top 10 by **shooting** → Cristiano Ronaldo led clearly
- Top 10 by **passing** → Bruno Fernandes, Bernardo Silva among leaders
- Top 10 by **dribbling** and **defending** also reviewed

---

## 💡 Key Insights

### 🔝 Top Players by Wage
| Player            | Wage (EUR) |
|------------------|------------|
| Lionel Messi     | €560,000   |
| Eden Hazard      | €470,000   |
| Cristiano Ronaldo| €410,000   |

### 🧠 General Trends
- Most players are rated between 65 and 75
- Players peak around **age 28–30** in rating
- Wages and value are highly skewed toward the elite top 1%
- Physical attributes (height, strength) correlate with roles like defender or goalkeeper

### 🌐 Country-Level Insights
| Metric             | Top Countries                  |
|--------------------|--------------------------------|
| Most players       | Argentina, Brazil, Spain       |
| Highest avg rating | Belgium, Portugal, Spain       |
| Oldest avg age     | Uruguay, Greece, Russia        |

### 🏆 Club-Level Strengths
| Skill              | Top Clubs                       |
|--------------------|---------------------------------|
| Passing            | FC Barcelona, PSG, Man City     |
| Dribbling          | PSG, Real Madrid, Barcelona     |
| Long Shots         | Man City, Bayern, Juventus      |
| Aggression         | Atlético Madrid, Roma, Inter    |

### 🧭 Role-Based Patterns
- **Defenders** cluster around high physical & low sprint stats
- **Attacking midfielders** show high dribbling + passing synergy
- **Younger players** show higher potential but lower wage

---

## 📎 Dataset Reference
- FIFA 20 Complete Player Dataset  
- [Kaggle Link](https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset)

