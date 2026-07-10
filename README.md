# Quantitative-Trades-Performance-Analytics

## 📌 Project Overview
The **Quantitative-Trades-Performance-Analytics Dashboard** is an analytical tool built to help traders and financial analysts evaluate historical performance, dissect execution patterns and uncover behavioral edges. By tracking execution metrics across different time dimensions (Months, Days of the Week) alongside key risk-reward indicators, this dashboard transforms raw execution data into clear, actionable trading strategies.

This dashboard helps answer critical operational questions:
* Which months or days yield the highest capital efficiency?
* Is high trading volume positively correlated with net profitability?
* What does the distribution of winning vs. losing streaks look like and how balanced is the risk-to-reward profiling?

---

## 📊 Dashboard Visuals

### 1. Day Trade Analysis Page
Provides a high-level overview of core portfolio health, equity curve progression, and monthly trade allocations.
[Day Trade Analysis]<img width="1280" height="720" alt="overview_trades" src="https://github.com/user-attachments/assets/5163005d-d36e-4923-aa38-ef1b69deeb92" />



### 2. Performance by Day of Week Analysis Page
Breaks down micro-level behaviors, assessing efficiency, win/loss sizing, and seasonality shifts across different days.
[Performance by Day of Week Analysis]<img width="1280" height="720" alt="overview_trades" src="https://github.com/user-attachments/assets/63d90baf-2e4f-4c92-89b6-3f014a276f92" />


---

## 🎯 Key Metrics Tracked

* **Net Profit:** The total bottom-line return generated over the selected time frame.
* **Total Trades:** The absolute number of round-trip transactions executed.
* **Expectancy Per Trade:** The average amount expected to be won or lost per trade (Net Profit / Total Trades).
* **Win Rate:** The percentage of successful trades relative to total executed trades.
* **Profit Factor:** The gross profits divided by the gross losses, indicating the multiplier of strategy sustainability.
* **Profit Excl. Top/Bottom 5%:** A normalized profit metric that strips out extreme statistical outliers (windfalls and black-swan losses) to show core baseline performance.

---

## 💡 Core Insights & Observations (Based on 2026 Sample Data)

### ⚖️ Trade Allocation vs. Efficiency
* **Volume Does Not Equal Profit:** In the monthly view, **April** saw the highest execution volume (**43 trades**), yet only generated **$0.9K** in profit. Conversely, **March** had fewer trades (**36**) but brought in the peak net profit of **$1.5K**, indicating higher trade quality and setup efficiency during that period.
* **Weekday Variance:** **Tuesday** shows the highest volume of trades (**42**) but drops into a net loss of **-$0.5K**, highlighting an execution trap or overtrading behavior on that specific day. **Thursday** stands out as the most efficient day, netting **$1.4K** on balanced volume.

### 📉 Risk-Reward Mechanics
* **Asymmetrical Loss Profiles:** The *Average Net Profit / Loss by Day of Week* chart reveals that while **Tuesday** suffers from a massive average loss size (**-$56.0** vs an average win of **$42.2**), days like **Thursday** showcase ideal expectancy with large average wins (**$111.4**) overpowering tightly managed average losses (**-$45.0**).
* **Consistency vs. Volume:** While the *Total Winning vs. Losing Trades* bar chart indicates that losing trades frequently outnumber winning trades in absolute count (e.g., February and April), a healthy overall **Profit Factor of 2.1** demonstrates that the strategy relies on strong positive risk-reward skew (large wins, small losses) to remain highly profitable.

---

## 🚀 Tech Stack Used
* **Data Visualization / BI Tool:** Power BI / Excel *(Adjust based on your tool)*
* **Data Transformation:** Power Query
* **Modeling Language:** DAX (Data Analysis Expressions) for custom calculated columns and measures.

---

## 3. Links & Access
Live Link: 

**https://app.powerbi.com/groups/me/reports/c9bad196-4c97-485d-8ed9-d689371b84f2/3da49a5f76b4b386e416?experience=power-bi**
