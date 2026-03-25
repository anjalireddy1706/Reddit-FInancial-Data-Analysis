# 📈 Reddit Data Analysis: Identifying Trends and User Engagement

## 📖 Overview

This project investigates the **r/InvestmentClub** subreddit to understand how *super users* shape community structure, drive engagement, and influence the flow of information across a financial online community.

Using a merged dataset of submissions and comments, the analysis combines **network graph construction**, **LDA topic modelling** and **temporal trend analysis** to map user influence and identify what drives spikes in engagement. A key finding is a dramatic surge in activity post-2020, traced back to real-world financial events - most notably the GameStop short squeeze. The study centres on three core questions: who are the most central users, what do they talk about and when does engagement peak?


## 📌 Key Findings

| Finding | Detail |
|---|---|
| **Top super user** | `Zurevu` — highest betweenness, closeness, and degree centrality |
| **Most discussed topic** | General stock/investment discussion (5,461 mentions) |
| **Warren Buffett topic** | Peaked in 2019, continued rising through 2021 |
| **Rich Club Coefficient** | Reaches 1.0 for users with degree ≥ 7, indicating tight-knit super user clusters |
| **Sensitivity analysis** | Removing just 10% of high-degree users drops the largest connected component from 10% → 1% |
| **Z-score spikes** | Values of 1.939 and 1.691 indicate event-driven surges in Warren Buffett mentions |
| **Post-2020 spike driver** | GameStop short squeeze triggered the largest engagement surge in subreddit history |
