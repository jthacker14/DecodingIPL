# 🏏 IPL Data Wrangling & Exploratory Analysis 🏆

## 👩‍💻 Authors
* **Ishita Kaur Sahni** (S058)[cite: 6]
* **Jiya Thacker** (S071)[cite: 6]

---

## 🎯 Project Objective
The primary goal of this project is to showcase a complete data analysis workflow using an Indian Premier League (IPL) dataset![cite: 6] We cover everything from sourcing the data to performing rigorous data cleaning, preprocessing, and conducting exploratory data analysis (EDA).[cite: 6] Finally, we bring the insights to life through dynamic bar, pie, and line charts.[cite: 6]

---

## 📊 The Dataset
* **Source:** The dataset (`ipl_dataset.csv`) was sourced directly from Kaggle and contains detailed match-by-match results.[cite: 6]
* **Size:** The raw dataset started with 951 rows and 12 columns.[cite: 6] After dropping matches washed out by rain or lacking a result, our clean dataset contains 933 rows.[cite: 6]
* **Key Features:** It tracks competing teams, final scores, toss winner and choice, match winner, victory margin, Man of the Match, and stadium details.[cite: 6]
* **Cleaning Highlights:** We dropped the `full_scorecard` column (as it contained irrelevant URLs) and engineered a brand-new feature, `toss_win_game_win`, to track if the toss winner actually won the match![cite: 6]

---

## 🛠️ Tools Used
* **Environment:** Python (Jupyter Notebook) 🐍[cite: 6]
* **Data Manipulation:** Pandas and NumPy 🔢[cite: 6]
* **Visualisation:** Plotly and Matplotlib/Seaborn 📉[cite: 6]

---

## 💡 Key EDA Findings
* **🏏 Scoring Averages:** The average score for the team batting first is approximately **162.5 runs**, while the chasing team averages **149.3 runs**.[cite: 6]
* **🪙 Toss Decisions:** Toss-winning captains overwhelmingly prefer to **field first (62.4%)** compared to batting first (36.5%).[cite: 6]
* **⚖️ Toss Advantage:** Despite the huge preference to field, winning the toss offers only a marginal statistical advantage—the toss winner wins the game just **51.5%** of the time.[cite: 6]
* **👑 Top Teams:** **Mumbai Indians** and **Chennai Super Kings** are historically the most dominant and successful franchises in terms of total match wins.[cite: 6]
* **🏟️ Top Venues:** **Wankhede Stadium** in Mumbai is the most frequent venue (hosting over 100 matches), followed by Eden Gardens and M Chinnaswamy Stadium.[cite: 6]
* **⭐ Top Players:** Individual impact awards are highly concentrated among specific legends, with **AB de Villiers** and **Chris Gayle** bagging the most 'Man of the Match' titles.[cite: 6]
* **📈 Match Margins:** While many games are nail-biters with low victory margins, sporadic extreme spikes show that completely one-sided blowouts are a regular feature of the IPL.[cite: 6]
* **🔄 Rolling Averages:** A 10-match rolling average for the team batting first reveals that "in-form" team scores oscillate consistently within a central band of around **160 runs**.[cite: 6]

---

## 🚀 Future Work
Future analyses could dive even deeper by incorporating player-specific statistics or venue data to evaluate how performance changes by location.[cite: 6] Ultimately, this cleaned dataset serves as the perfect foundation for building a **predictive machine learning model** to forecast match winners based on the toss, venue, and team form![cite: 6]