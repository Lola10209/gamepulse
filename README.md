# gamepulse
# GamePulse: Player Retention, CRM and User Acquisition Analytics

## Project Overview

GamePulse is a gaming analytics portfolio project that explores how player behaviour data can be used to understand retention, churn, user acquisition performance and CRM opportunities.

The project simulates a mobile gaming environment where players join through different acquisition channels, play sessions, complete levels, view ads, make purchases and either remain active or churn. The aim is to show how data can support better product, marketing and CRM decisions in a gaming business.

This project was designed to reflect the type of analysis used by gaming publishers, product teams, CRM teams and user acquisition teams.

## Business Question

How can a gaming company use player behaviour data to identify valuable players, reduce churn and improve CRM and user acquisition decisions?

## Tools Used

* Python
* pandas
* matplotlib
* SQLite
* SQL
* Power BI
* Jupyter Notebook
* GitHub

## Project Stages

### Stage 1: Data Setup and Initial Exploration

A simulated gaming dataset was created and explored using Python. The dataset included player IDs, countries, acquisition channels, device types, sessions, playtime, levels completed, purchases, retention and churn.

Key checks included:

* dataset shape
* column types
* missing values
* first rows of data
* basic player segment counts

### Stage 2: Retention and Churn Analysis

Retention and churn were analysed across the full player base, acquisition channels and countries.

Key metrics included:

* Day 1 retention
* Day 7 retention
* Day 30 retention
* churn rate
* revenue by channel
* retention by country

The analysis showed that early engagement was strong, but long-term retention dropped significantly by Day 30.

### Stage 3: CRM Player Segmentation

Players were grouped into CRM-style segments based on retention, engagement and purchase behaviour.

The segments included:

* High-Value Retained Player
* Loyal Engaged Player
* At-Risk Early Drop-off Player
* New or Casual Player
* Churned Player

This helped identify which players should receive loyalty rewards, onboarding support, win-back campaigns or personalised engagement.

### Stage 4: SQL Analysis

SQLite was used to analyse the dataset with SQL queries. The SQL analysis answered business questions around:

* total players and revenue
* retention by acquisition channel
* churn by country
* CRM segment performance
* high-value players
* at-risk players
* revenue by device type

This showed that the same business questions could be answered using both Python and SQL.

### Stage 5: Power BI Dashboard

A Power BI dashboard was created to visualise player retention, churn, acquisition performance, CRM segments and revenue.

The dashboard includes:

* total players
* total revenue
* Day 30 retention
* churn rate
* retention by acquisition channel
* churn by country
* CRM segment distribution
* revenue by CRM segment
* CRM action plan

## Key Insights

Organic and App Store Search produced stronger Day 30 retention, suggesting that players from these channels had stronger interest and were more likely to stay active.

High-Value Retained Players generated the highest revenue despite being a smaller group. This shows that a small number of loyal paying players can contribute strongly to overall monetisation.

Churned players were the largest segment, which shows that retention is a major business challenge. Some churned players still generated revenue before leaving, suggesting that the business should investigate why paying or semi-engaged players stopped playing.

Loyal Engaged Players had strong activity and retention but did not generate revenue. This creates an opportunity for targeted starter offers, achievement-based rewards or personalised conversion campaigns.

## Business Recommendations

The company should prioritise CRM campaigns for at-risk players before they fully churn.

High-value retained players should receive loyalty rewards, exclusive content and personalised offers.

User acquisition should not be judged only by install volume. Channels should also be assessed by Day 30 retention, churn rate and revenue quality.

Markets with high churn should receive stronger onboarding, localised messaging and re-engagement campaigns.

CRM teams should use different strategies for different player groups instead of sending the same campaign to all players.

## Project Outcome

This project demonstrates beginner-friendly but job-relevant skills in data cleaning, retention analysis, churn analysis, CRM segmentation, SQL querying, dashboard reporting and business insight generation.

It is relevant for Data Analyst Intern, Product Analytics Intern, CRM Analytics Intern, Gaming Data Analyst Intern, User Acquisition Analyst Intern and Business Intelligence Intern roles.
