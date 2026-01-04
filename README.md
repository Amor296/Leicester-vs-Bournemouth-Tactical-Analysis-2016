# 🦊 Leicester City 2016: The Tactical Blueprint (Kanté & Mahrez)

This project provides a deep-dive data analysis into the tactical synergy between **N'Golo Kanté** and **Riyad Mahrez** during Leicester City's historic 2016 Premier League season. Using **StatsBomb** event data, we visualize how defensive solidity was transformed into attacking efficiency.

## 📋 Project Overview
The goal of this analysis is to decode the "Low Block & Counter-Attack" strategy used by Claudio Ranieri, focusing on:
1. **Defensive Solidity:** How Kanté acted as a defensive anchor.
2. **Attacking Efficiency:** How Mahrez served as the creative engine.

---

## 🛠️ Project Structure
The analysis is divided into three main notebooks:

### 1. `01_data_exploration.ipynb`
* Initial data fetching and cleaning using `statsbombpy`.
* Setting up the match environment (Leicester City vs. Bournemouth, 2016).

### 2. `02_defensive_solidity.ipynb`
* **Defensive Gravity Center:** Visualizing the team's "Low Block" through Kanté's average position.
* **Heatmaps & Intensity:** Mapping Kanté’s 40+ defensive interventions across the pitch.

### 3. `03_attacking_efficiency.ipynb`
* **Creative Influence:** Mapping Mahrez's "Golden Wing" and his tendency to cut inside.
* **Passing Networks:** Analyzing Mahrez's 78% pass success rate and vertical progression.
* **1vs1 Mastery:** Evaluating dribbling performance in high-value zones.

---

## ⚽ Key Tactical Insights
* **The "Black Hole" Effect:** Kanté's defensive gravity center proves that Leicester invited pressure deep into their half before reclaiming the ball.
* **Transition Speed:** The synergy between a deep defense and Mahrez's high-density creative zones allowed for lethal counter-attacks.
* **Efficiency over Possession:** The data confirms that tactical discipline (Low Block) and specialized roles (The Architect vs. The Destroyer) were the keys to Leicester's success.

---

## 🚀 Tech Stack
* **Language:** Python
* **Data Source:** [StatsBomb Open Data](https://github.com/statsbomb/open-data)
* **Libraries:** `pandas`, `matplotlib`, `seaborn`, `mplsoccer`, `statsbombpy`

## 📈 Visualizations
* **Tactical Heatmaps** (Kernel Density Estimation)
* **Pass Maps** (Arrow Distributions)
* **Spatial Centroids** (Gravity Center Analysis)

---

## 👨‍💻 Author
**[Amr Alaa , Amor296]**
*Football Data Enthusiast | Python Developer*
