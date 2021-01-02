# reddit-hot-stocks
Open the files in Jupyter. I am using the Praw reddit API to scan the daily discussion and other latest posts to determine the sentiment.
Research shows that sentiment is a lagging indicator and cannot be used to predict future stock market prices.

call put options purchased in timeframe:
uses post history of pickbot to find what redditors have been buying. You can filter by dates. If you are seeing a call to put ratio of over 90% then you may hypothesize that the market is overbought. If the call to put ratio dips below 50% then you may find a good entry point for mid to long term call options.


recent number of gain or loss posts:
scans the last X posts and categorizes them by flair. One can easily see that even when stocks are going up, and everyone seems to be buying calls, there are still a large number of losses. This is likely the product of users trying to time the market and pick stocks using information that's priced in. Or they're just fomoing.
