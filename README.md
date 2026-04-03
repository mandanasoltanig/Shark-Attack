# 🦈 Overview
The Shark Attack Tourism Safety Analyzer helps tourism businesses 
identify the safest seasons and activities for water-based tourism 
by analyzing global shark attack incident data from the Global Shark 
Attack File (GSAF). It provides data-driven insights to help tourism 
operators protect their customers and make informed business decisions.

# 🛠️ Features
1. Season-based shark attack incident analysis
2. Activity-risk breakdown (swimming, surfing, diving, etc.)
3. Cross-tabulation of Season vs Activity
4. Safety ranking system for tourism recommendations
5. Data cleaning and wrangling of real-world GSAF dataset

# 🔑 Technologies Used
The project leverages fundamental Python concepts — see below

# 💡 Functions:
Organize data cleaning, filtering, and analysis into reusable blocks.

# 📂 Data Structures:
1. DataFrames — Core structure for storing and analyzing shark incident records
2. Series — Used for value counts per season and activity
3. Crosstab Tables — Used to map Season vs Activity relationships
4. Lists — Store column names and filter conditions

# 🌿 Control Flow:
1. If & else statements: Flag high-risk vs low-risk seasons
2. Groupby & Aggregation: Summarize incidents by season and activity
3. Data Filtering: Isolate relevant columns (Season, Activity, State)
4. Value Counts: Rank seasons and activities by incident frequency

# 🏖️ Business Hypothesis:
"Shark attack incidents are highest in Summer and lowest in Winter.
Swimming is the most common activity during attacks across all seasons.
Winter and Spring are the safest seasons recommended for water tourism."

# 📊 Safety Conclusion:
1. ✅ Winter  — Safest (69 incidents)
2. 🟡 Spring  — Low Risk (281 incidents)
3. 🟠 Fall    — Moderate Risk (325 incidents)
4. 🔴 Summer  — Highest Risk (404 incidents)

# 🔗 Link To Shark Attack Project :
https://docs.google.com/presentation/d/1M5gG_-IKfdad_FSNHanYoROSQBHZXYVaHXKmoVg5HZk/edit?usp=sharing
