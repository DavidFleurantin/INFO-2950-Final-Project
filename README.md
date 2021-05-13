# INFO-2950-Final-Project: Playing With r/wallstreetbets :money_with_wings: :video_game:
Final Project for INFO 2950 (Spring 2021)

## Description
A short squeeze of the stock price of GameStop (GME), an American video game retailer, occurred during January 2021. The price spiraled rapidly out of control until lots of major hedge funds and other sellers lost lots of money. It is rumored on the internet that the subreddit [r/wallstreetbets](https://www.reddit.com/r/wallstreetbets/) caused the stock to initially short, thus propelling this extraordinary sequence of events to occur. We initially analyzed the correlation between the times of posts made on the subreddit mentioning GameStop and the times the actual stock's price changed IRL, but this returned no significant results. Deciding to pivot to a different research area, we as Reddit users thought about how some posts on Reddit get flagged for highly negative **sentiment**. Wanting to perform sentiment analysis of our own, we thought of doing an analysis on the sentiment of the GameStop-selected r/wallstreetbets posts we had, and training a model to predict the sentiment of other posts in the same group, if the analysis produced a significant enough result. Ultimately, our analysis did not return any significant findings. It seems that this internet myth is debunked through the power of data science and that this small subreddit was too insignificant, its language too tame, to influence the behemoth that is the stock market.

## Contributors
[Meredith Hu](https://github.com/meredithmhu) [David Fleurantin](https://github.com/DavidFleurantin)

## Repository Directory
~Please navigate to phaseV for the final instantiation of the project~
 * DataCleaningAppendix: contains code we used to construct and clean the datasets
 * OtherAppendix: contains findings from exploratory analysis we performed on initially, what was two datasets
 * phaseV.ipynb: an executed [Jupyter Notebook](https://jupyter.org/) containing our research project
 * reddit_wsb.csv: the main dataset used in the project
 * reddit_wsb_gme.csv: the discarded dataset, explored in OtherAppendix
