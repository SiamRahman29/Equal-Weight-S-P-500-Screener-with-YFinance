# Equal-Weight-S-P-500-Screener-with-YFinance

The S&P500 index fund is the most famous index fund of the American stock market, and maybe even the whole world. But this index fund is not weighted. This project the fund taking each stock's market capital and prices into account to tell you how many of which stock you should buy with your capital to gain a weighted version of this index fund

##Acknowledgements and Notes

This project was built with the help of this tutorial: https://www.youtube.com/watch?v=xfzGZB4HhEE&t=5916s

The tutorial itself was outdated as IEX Cloud does not provide its Sandbox API since late-mid 2022. So, I tried Alpha Vantage first to overcome the difficulty. Alpha Vantage limits users to only 5 API calls per minute so could not complete the project with Alpha Vantage (however, may be Alpha Vantage can be used if only batch calls are used).

Finally, I used YFinance. It worked but I have not been able to use batch calls. The fundamental flow is the same as the tutorial. Check out the file starting with "ExtremeNoted" for a walk through the entire thing. It is really messy, but the mess was part of the journey.

Also, for the recommended trades file given: the portfolio_size was 100,000,000
We had to rename BRK.B to BRK-B and BF.B to BF-B. Otherwise, Yfinance will not be able to find them

I will try to add the batch call part as well.
