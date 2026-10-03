# IPL_Machine_Learning_Project-
This is a folder of Machine Learning project which I have done during my internship.

 # IPL Data Analysis

## Project Overview

* Comprehensive Exploratory Data Analysis (EDA) of Indian Premier League (IPL) historical data.

* Focuses on extracting actionable insights into team dynamics, match strategies, venue impact, and individual player performance metrics.

* Designed to analyze match trends, victory distributions, and batting efficiencies across multiple seasons using Python data science libraries.


## Key Objectives

* Data Cleaning & Wrangling:Process raw datasets, handle missing or null values, format data types, and prepare clean DataFrames using Pandas.

* Team & Match Outcome Dynamics: Analyze win-loss patterns, win margins by runs versus wickets, and victory frequencies per franchise.

* Toss Strategy Analysis: Evaluate the impact of winning the toss on match outcome and assess tactical choices (batting vs. fielding first).

* Player Performance Evaluation: Identify key match-winners through "Player of the Match" distributions and calculate strike rates across high-impact batsmen.

* Venue & Location Trends: Study performance variation across different grounds and match locations.



## Tech Stack & Tools

* Programming Language: Python

* Data Processing Libraries: Pandas, NumPy
  
* Analysis Environment: Jupyter Notebook / IPython

* Version Control: Git, GitHub

---

## Dataset Details

 Source Files: `matches.csv` (Match-level details) and `deliveries.csv` (Ball-by-ball dataset)

    Primary Features Analyzed:
  * `season`, `city`, `date`, `venue`
  * `team1`, `team2`, `winner`, `result`
  * `toss_winner`, `toss_decision`
  * `win_by_runs`, `win_by_wickets`
  * `player_of_match`, `batsman`, `batsman_runs`

---

## Analysis Breakdown & Key Insights

### 1. Batting Efficiency & Strike Rate

* Aggregated total runs and total balls faced per batsman across seasons.

* Calculated individual strike rates: $\text{Strike Rate} = \frac{\text{Total Runs}}{\text{Total Balls}} \times 100$

* Ranked top performers based on strike rates to evaluate high-impact power hitters (e.g., AB de Villiers, YK Pathan, KA Pollard, DA Warner).

### 2. Toss Decision Impact

* Quantified victory rates based on winning the toss.

* Compared winning percentages when choosing to field first versus defending a target.

### 3. Victory Margins & Match Dominance

* Calculated summary statistics for matches won by runs (defending totals) versus matches won by wickets (chasing targets).

* Identified extreme outliers, such as the highest run margin and highest wicket margin victories.

### 4. Player Impact

* Segmented individual match awards to determine players with the highest "Player of the Match" accolades across tournament history.

---

## Project Structure

* `IPL_Analysis.ipynb`: Main Jupyter Notebook containing code, analytical workflows, and output tables.

* `matches.csv`: Primary dataset containing match metadata.

* `deliveries.csv: Detailed ball-by-ball match data.

* `README.md: Project documentation and summary.


 
