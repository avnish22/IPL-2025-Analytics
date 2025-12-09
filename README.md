# IPL-2025-Analytics
## 🎯 Business Problem: Zero-Emotion Mega Auction
IPL Mega Auctions mein selection aksar hype, reputation, aur galti se hue single-season spikes par based hota hai. Isse teams expensive mistakes karti hain.

This project solves that by developing an objective, data-driven framework to evaluate player impact and risk.
- Goal: Create a metric that balances a player's high output (Value/Threat) with their reliability (Consistency/Control) to identify the best Return on Investment (ROI).

## 📊 About the Dataset

The analysis uses publicly available data from the latest IPL season (Stats for Batters and Bowlers).
- Source: Cricket Statistics Websites (Simulated/Scraped data).
- Key Columns Used: Bat_Avg, Bat_SR, Wkts, Bowl_Eco, Death_Overs_ER, Runs, and Verified Matches count.

## 🛠️ Project Planning & Execution

The project followed a clear Data Mining and Visualization Pipeline:
a) Data Cleaning & Integration (Python/Pandas):

- Separate batting and bowling data were merged into a single, unified player profile.

- Crucial missing data, like the correct Matches played, was manually verified and updated.

b) Metric Engineering (Python/Pandas):

- Calculated four core normalized metrics (0 to 1 scale):

  - Consistency Score (Reliability)

  - Batting Value (Aggression/Output)

  - Control Score (Economy/Pressure)

  - Wicket Threat (Wickets per Match)

c) Final Metric: Calculated the Player Impact Rating (PIR). PIR combines the four core metrics (60% reliability, 40% output) to give a single, unified performance score for every player.

d) Visualization (Power BI) (70% Focus): Developed an interactive dashboard for quick decision-making.


## 🔑 Conclusion: The Answer
The project successfully delivered a zero-emotion, data-backed PIR Scorecard. The dashboard provides the definitive answer to the business problem by:

Identifying the most valuable players (high PIR) while mitigating the risk of investing in inconsistent performers (low Consistency Score).

## Key Visual Insights

### Full Dashboard View
<img width="591" height="328" alt=" " src="https://github.com/user-attachments/assets/b439bfed-0877-4b68-84ea-438f2c635fca" />
<img width="586" height="326" alt=" " src="https://github.com/user-attachments/assets/3014ac87-0d72-43bf-ac58-8a601c8fdffd" />
<img width="590" height="331" alt=" " src="https://github.com/user-attachments/assets/c543a49c-173b-484e-8226-294315691cdc" />
<img width="584" height="328" alt=" " src="https://github.com/user-attachments/assets/e82cc624-3a00-4790-a8d8-31e2f51f1849" />
<img width="584" height="325" alt="Full Page" src="https://github.com/user-attachments/assets/712f6174-573c-4a15-a259-1f546c3db13a" />


