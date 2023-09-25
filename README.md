# Churn Analysis of Top 30 Subreddits
This project was undertaken during the MSCA 37014 5 Python for Analytics course in Winter 2024. The work represents the collective effort of Mariam Adeyemo, Mia Song, Nida Ulhaq Fitriyah, and Rolamjaya Hotmartua.

### Data
1. RC_2012_year_cohort.feather
- data from January 2012 to November 2012
- `author` which contains the user name of the person writing the comment
- `created_utc` the timestamp of the comment.
- `subreddit` which contains the name of the subreddit where the author posted a comment.
- This file is too large for direct upload. For access, please contact the author directly.
2. ChurnAnalysis.ipynb

### Objective
Our primary aim was to visualize user engagement patterns within the top 30 subreddits over time.

### Methodology
- Establishing a Baseline: We used day 0 as our reference point, representing initial user engagement.
- Engagement Calculation: For subsequent days, we calculated the percentage of authors who commented relative to day 0. This was done by determining the number of new reddits created each day post day 0 and dividing this number by the total reddits from day 0.0
- Visualization: Based on our calculations, we constructed a 'retention curve' to graphically represent user engagement for these top 30 subreddits over time.
