# NHS Referral-to-Treatment (RTT) Wait Times Analysis

**Dataset:** February 2025 NHS RTT Data Extract  
**Author:** [Your Name Here]

## Project Overview

This project explores NHS Referral-to-Treatment (RTT) wait times using real-world open health data. The goal is to reveal patterns in waiting time distribution, spotlight long-waiting patient backlogs, and compare performance across NHS providers. The analysis is presented in a clear, stepwise Jupyter Notebook suitable for recruiters and technical reviewers.

## Key Analysis Steps

- **Data cleaning and preparation**
- **Exploratory Data Analysis (EDA):** Wait time distributions, binning, and filtering
- **Long-waiter analysis:** Cumulative numbers and share of patients waiting >21 weeks
- **Provider-level insights:** Mean wait times, provider ranking by long-wait backlog
- **Data storytelling:** Focus on clear, readable visualizations and honest presentation of results

## Main Findings

- ~35% of patients are waiting more than 21 weeks for treatment
- Significant variation exists across NHS Trusts in both mean wait time and long-waiter backlogs
- Clear communication and visualization techniques are critical to real-world health analytics

## Limitations

- Data reflects only a single month (February 2025); seasonal or long-term trends are not captured
- Specialty-level or diagnosis-level breakdowns are not included in this analysis
- Predictive modelling and time series analysis are possible next steps but not yet implemented

## Next Steps / Future Work

- **Predictive Modelling:** Use historical RTT datasets to forecast future wait times and identify risk factors for long waiting
- **Time Series & Trend Analysis:** Explore wait time changes over months or years
- **Deeper Stratification:** Break down results by specialty, age, or region for richer insights
- **Interactive Visualizations:** Build dashboards for dynamic exploration by NHS stakeholders

## How to Run

1. Clone this repository and ensure you have Python 3.x, pandas, and matplotlib installed.
2. Place the `NHSwaitingtimes.csv` dataset in the project directory.
3. Open and run the notebook in JupyterLab or VS Code.

## Contact

Questions or feedback?  
Feel free to reach out via [GitHub Issues](https://github.com/) or [LinkedIn](https://www.linkedin.com/).

---


