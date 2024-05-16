Data Collection/Analysis Scripts

Note: These scripts take a substantial amount of time/resources to complete.

- data_exploration: Scrapes submissions from political, popular, and suspicious user subreddits from 9/2023 - 10/2023. These subreddits are defined in several .csv files.
- fetch_sus_usrs_post_history: Collect suspicious users post history to obtain user information who interacted with the suspicious users to better connect our network.
- get_subreddit_info: Collect subreddit attributes.
- get_usr_info: Collect user attributes. Script will need to be modified to point to the desired source of users.
- make_network: Parse scraped data to compile attributes as well as generate additional attributes such as sentiment analysis and identify network structure and finally generate a graphml network file.
                Requires files generated from above scripts (data_scraping).