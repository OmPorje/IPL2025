# 🏏 IPL 2025 Datasets

This folder contains datasets used for analyzing the IPL 2025 season. These datasets include match-level and ball-by-ball data to help uncover insights into team and player performance.

---

## 📁 Files Included

### 1. `matches.csv`
- **Rows**: 74
- **Columns**: 22
- **Description**: Contains match-level details such as teams, venue, toss results, and innings scores.
- **Sample Columns**:
  - `match_id`
  - `date`
  - `venue`
  - `team1`, `team2`
  - `toss_winner`, `toss_decision`
  - `first_ings_score`, `first_ings_wkts`

---

### 2. `deliveries.csv`
- **Rows**: 17,183
- **Columns**: 19
- **Description**: Ball-by-ball data of IPL 2025 matches, useful for granular analysis of player and team performance.
- **Sample Columns**:
  - `match_no`
  - `date`
  - `venue`
  - `batting_team`, `bowling_team`
  - `innings`, `over`
  - `striker`, `bowler`

---

## 📌 Usage

These datasets are used in the `IPL2025.ipynb` notebook to:
- Analyze team performance and win rates
- Track batting and bowling efficiency
- Visualize match trends using Python libraries

---

## 🧾 Note

Ensure both files are placed in the same directory as the notebook or update the file paths inside your code accordingly.


