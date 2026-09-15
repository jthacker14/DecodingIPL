# 🏏 IPL Data Wrangling & Exploratory Analysis 🏆

## 👩‍💻 Authors
* **Ishita Kaur Sahni** (S058)
* **Jiya Thacker** (S071)

---

## 🎯 Project Objective
The primary goal of this project is to showcase a complete data analysis workflow using an Indian Premier League (IPL) dataset! We cover everything from sourcing the data to performing rigorous data cleaning, preprocessing, and conducting exploratory data analysis (EDA). Finally, we bring the insights to life through dynamic bar, pie, and line charts.

---

## 📊 The Dataset
* **Source:** The dataset (`ipl_dataset.csv`) was sourced directly from Kaggle and contains detailed match-by-match results.
* **Size:** The raw dataset started with 951 rows and 12 columns. After dropping matches washed out by rain or lacking a result, our clean dataset contains 933 rows.
* **Key Features:** It tracks competing teams, final scores, toss winner and choice, match winner, victory margin, Man of the Match, and stadium details.
* **Cleaning Highlights:** We dropped the `full_scorecard` column (as it contained irrelevant URLs) and engineered a brand-new feature, `toss_win_game_win`, to track if the toss winner actually won the match!

---

## 🛠️ Tools Used
* **Environment:** Python (Jupyter Notebook) 🐍
* **Data Manipulation:** Pandas and NumPy 🔢
* **Visualisation:** Plotly and Matplotlib/Seaborn 📉

---

## 💡 Key EDA Findings
* **🏏 Scoring Averages:** The average score for the team batting first is approximately **162.5 runs**, while the chasing team averages **149.3 runs**.
* **🪙 Toss Decisions:** Toss-winning captains overwhelmingly prefer to **field first (62.4%)** compared to batting first (36.5%).
* **⚖️ Toss Advantage:** Despite the huge preference to field, winning the toss offers only a marginal statistical advantage—the toss winner wins the game just **51.5%** of the time.
* **👑 Top Teams:** **Mumbai Indians** and **Chennai Super Kings** are historically the most dominant and successful franchises in terms of total match wins.
* **🏟️ Top Venues:** **Wankhede Stadium** in Mumbai is the most frequent venue (hosting over 100 matches), followed by Eden Gardens and M Chinnaswamy Stadium.
* **⭐ Top Players:** Individual impact awards are highly concentrated among specific legends, with **AB de Villiers** and **Chris Gayle** bagging the most 'Man of the Match' titles.
* **📈 Match Margins:** While many games are nail-biters with low victory margins, sporadic extreme spikes show that completely one-sided blowouts are a regular feature of the IPL.
* **🔄 Rolling Averages:** A 10-match rolling average for the team batting first reveals that "in-form" team scores oscillate consistently within a central band of around **160 runs**.

---

## 🚀 Future Work
Future analyses could dive even deeper by incorporating player-specific statistics or venue data to evaluate how performance changes by location. Ultimately, this cleaned dataset serves as the perfect foundation for building a **predictive machine learning model** to forecast match winners based on the toss, venue, and team form!
