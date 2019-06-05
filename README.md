# Bitcoin-Trader-RL

A custom OpenAI gym environment for simulating Bitcoin trades on historical price data with live rendering.

In this article, we've created a profitable cryptocurrency trading agent using deep reinforcement learning.

Data sets: https://www.cryptodatadownload.com/data/northamerican/

If you'd like to learn more about how we created this agent, check out the Medium article: https://towardsdatascience.com/creating-bitcoin-trading-bots-that-dont-lose-money-2e7165fb0b29

Later, we optimized this repo for massive profits using feature engineering and Bayesian optimization, check it out:
https://towardsdatascience.com/using-reinforcement-learning-to-trade-bitcoin-for-massive-profit-b69d0e8f583b


Project work: 

Adapt to smaller, more volatile cryptocurrencies
Test viability vs. market response
Add DMemory Module
  Identifies remembered patterns over time period
  Stores "valuable" (negative or positive or unique) patterns
  Trains network on recall speed
  Forward predicts patterns based off information feeds

Add sentiment analysis module
  Pulls data patterns from: 
    Twitter
    Blogs
    Adversarial Sources
    Official Releases
    News
