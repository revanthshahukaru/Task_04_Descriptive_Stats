# Task_04_Descriptive_Stats
Descriptive statistics of 2024 election social media data using Pure Python, Pandas, and Polars.

This analysis covers three datasets related to the 2024 US presidential election: Facebook Posts, Facebook Ads, and Twitter Posts. Each dataset reveals distinct patterns of activity and engagement strategies across the different platforms.

#### Facebook Posts

The analysis of 19,009 Facebook posts shows that engagement is highly concentrated, with a mean of 2,210 interactions per post but a very large standard deviation (~13,066), indicating that a small number of posts drive the majority of engagement.

    Content and Categories: The most frequent post type is 'Link', and the most common page category is 'PERSON' with 9,453 posts.

    Engagement Drivers: Posts from uncategorized pages ('') generate a significantly higher average of ~11,869 interactions, far surpassing official categories like 'POLITICIAN' (~309). As expected, 'Likes', 'Comments', and 'Shares' are all very strongly correlated with 'Total Interactions'.

    Temporal Trends: User interaction peaked on November 5th, 2024, aligning with the election period.

#### Facebook Ads

The dataset contains 31,907 ads, with ad spending peaking on October 27, 2024.

    Spending Patterns: The average ad spend is ~$1,653, but the high standard deviation (~$6,465) points to vastly different budget strategies among advertisers.

    Top Advertisers: 'HARRIS FOR PRESIDENT' is the most prolific advertiser with 9,687 ads and the top spender with over $15.1M in total. However, other groups like 'Hard Asset Heroes' and 'RBG PAC' employ a different strategy, with a much higher average spend per ad of $15,881 and $12,231 respectively.

    Correlations: There is a moderate positive correlation of 0.64 between an ad's estimated impressions and the total amount spent on it.

#### Twitter Posts

The analysis of 27,304 tweets shows that the 'Twitter Web App' is the most used client, responsible for 14,930 tweets.

    Engagement Dynamics: Tweets from 'Sprout Social' receive the highest average number of retweets (~3,525) and views (~1.5M), despite having fewer total tweets than the web app. This suggests it is used by accounts with high-influence.

    Metric Relationships: There is a very strong positive correlation (0.93) between likeCount and retweetCount. viewCount is most strongly correlated with quoteCount (0.89), suggesting quote-tweets are a major driver of visibility.

    Temporal Trends: The highest volume of daily tweets occurred on September 11, 2024, with 256 posts.