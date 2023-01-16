# Practicum Project 5

## Video Game Sales Analysis

## Description 
You work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. You need to identify patterns that determine whether a game succeeds or not. This will allow you to spot potential big winners and plan advertising campaigns.

In front of you is data going back to 2016. Let’s imagine that it’s December 2016 and you’re planning a campaign for 2017.

Reference for the data name and description:
- Name: title of the game
- Platform: what console the game is on
- Year_of_release: the game's release year
- Genre: the type of the game
- NA_sales: (North American sales in USD million)
- EU_sales: (Europe sales in USD million)
- JP_sales: (Japan sales in USD million)
- Other_sales: (all other countries sales in USD million)
- Critic_score: maximum of 100, professional reviewed scores
- User_score: maximum of 10, user reviewed scores
- Rating: ESRB rating

Analyze the data: identify trends from the data on sales

## Conclusions

In planning for 2017, the focus of the campaign should be on modern platforms, with game genres including shooters, platformers, and sports, 'M' ESRB rated games, and highly scored professional critic reviews. Platforms typically have a lifespan of around 5-7 years, and it is best to focus on the most recent consoles, such as PS4 and XBox One to maximize sales, as these platforms have been trending upwards into 2016 and 2017. When looking at the type of games, generally shooters, platformers, and sports games have the highest average sales compared to other game genres. 'M' ESRB rated games have the highest sales in EU and NA regions and is second best in the JP region. In terms of reviews, higher professional critic scores tend to correlate with better sales, with user reviewed scores show to have little to no correlation to sales.

Here, I will describe the general process that went into analysis of the dataset. When plotting the top platform sales by year, it was evident that there are cycles of increasing and decreasing sales. This translated into about a lifespan of 5-7 years before sales went to 0. Because of this and the goal of the analysis to predict future trends, it was decided that data before 2010 was irrelevant to the analysis. From here, I broke down data of several variables and its effect on sales. These include the critic score, user score, genres, and ESRB ratings. In addition, sales were further separated into the different global regions and effects of the variables on the different regions were analyzed accordingly. Based from this analysis, there were clear trends that indicated what factors led to more sales and thus the conclusions that I described.