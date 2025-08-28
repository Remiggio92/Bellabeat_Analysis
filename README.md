# Bellabeat_Analysis

## Project goal
Bellabeat data analysis of usage patterns and user retention with data from Fitbit, using Google Spreadsheet, Bigquery and Tableau.

## Key questions
1. What are the patters of using Bellabeat smart devices among different groups of users, having different activity level?
2. Are there correlations between different metrics such as physical activity level, sleep, and weight?
3. How long users stay active before they stop using Bellabeat smart devices?

## Methodology
- Data: Tables 'daily_activity', 'sleep_day', 'weight_log_info' in BigQuery;
- Tools: Google Spreadsheet, SQL (BigQuery), visualizations (Tableau), presentation (Google Slides).

## Results
- **Usage patterns**: 'High Activity' group has the highest number of steps, but uses sleep and weight functions rarely;
- **Activity on workday**: Higher activity on workdays for 'High Activity' group;
- **Correlations**: Weak correlations between steps, sleep and weight (e.g. 'corr_steps_sleep = -0.5' for 'Low Activity' group);
- **Retention**: 'Low Activity' has the lowest retention (62.5% after 30 days).

### Visualizations
- Usage patterns (sleep): ![Sleep by Activity Level](Sleep%20by%20Activity%20Level.png)
- Usage patterns (weight): ![Weight by Activity Level](Weight%20by%20Activity%20Level.png)
- Usage patterns (intensity): ![Activity Intensity by Level](Activity%20Intensity%20by%20Level.png)
- Activity on workdays:![Day of Week Trends](Day%20of%20Week%20Trends.png)
- Correlations: ![Correlation Heatmap](Correlation%20Heatmap.png)
- Retention: ![User Retention](User%20Retention.png)

## Presentation
https://docs.google.com/presentation/d/1hgBsWyJEXtg7IqUIITiEqUEjB3RISNTRQqB2jElIrM8/edit?slide=id.p#slide=id.p

## Recommentadions
- Gamification for 'Low Activity' group;
- Better steps, sleep and weight functions integration;
- Notifications to track users progress;
- Health benefits' campaigns.
