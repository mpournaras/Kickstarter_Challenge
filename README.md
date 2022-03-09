# Kickstarter_Challenge Overview
This project was to analyze how different Kickstarter play campaign's outcomes fared in relation to their launch dates and funding goals.

# Analysis and Challenges
I started by cutting down the large Kickstarter dataset to just plays. While there is a wealth of data, there would be difficulty in analyzing the whole dataset as the customer is launching a play fundraiser, not a television show or music project. This allows me to focus on the data that relates to similar projects as the customer to limit noise and outliers.

The first thing I decided to look at was theater outcomes as a whole based on launch date. There was a filter for year, however I found it difficult to draw conclusions based on launch year and so found the launch data by month to be much more revealing. This is what it shows.

![Outcomes_based_on_launch](https://github.com/mpournaras/Kickstarter_Challenge/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

This following chart is theater outcomes filtered down to plays. This helps us filter out things like theater building projects and musicals. This describes the outcomes based on funding goals. This will allow us to see successful and not-so-successful budget ranges to possibly target.

![Play_Outcomes_based_on_Goals](https://github.com/mpournaras/Kickstarter_Challenge/blob/main/Resources/Outcomes_vs_Goals.png)

The challenge with this data is that with no plays being canceled, the chart values for success and failure mirror eachother.

# Results

Looking at the Outcomes Based on Launch chart we can determine 2 things:
1. Launching a fundraiser in the summer months starting in May provides the largest chance for success. May, June, and July have the 3 highest success rates of all the months.
2. December and January launches are by far the least successful, and have a higher likelihood of being canceled.

Looking at the Play Outcomes Based on Goal chart we can determine one thing... we can determine that low budget plays under $5000, and medium budger plays between $35,000 and $45,000 are most successful.

This parent dataset is limited based on the presence of a couple outliers, but with clever targets and filtering we were able to neutralize those issues.
I think in this case a stacked bar chart may be more helpful for looking at funding goal outcomes. I have included it below. I think it better illustrates the successful nature of the budget ranges mentioned above.

![Play_Outcomes_based_on_Goals](https://github.com/mpournaras/Kickstarter_Challenge/blob/main/Resources/Outcomes_vs_Goals2.png)
