# IITM_TDS_PROJECT1This repository contains data about GitHub users in Hyderabad, India
 with over 50 followers and their repositories.



1. `users.csv`: Contains information about 505 GitHub users in Hyderabad with over 50 followers
2. `repositories.csv`: Contains information about 36203 public repositories from these users
3. `gitscrap.py`: Python script used to collect this data


## Interesting Insight

Key Insights from Data Analysis: Upon analyzing the scraped data, one of the most surprising findings was the correlation between the number of forks and repository longevity. Repositories with higher fork counts tend to show consistent activity and maintenance, which often correlates with longer-term project relevance.

Recommendations for Developers: Developers can increase their project’s visibility by focusing on documentation quality and encouraging contributions from newcomers. Open issues and welcoming contribution guidelines significantly increase engagement rates, leading to a more robust project lifecycle.

## Data Collection

- Data collected using GitHub API
- Date of collection: 2024-10-30
- Only included users with 50+ followers
- Up to 500 most recently pushed repositories per user
