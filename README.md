# PortfolioOpimization
Constructing and Optimizing Green Portfolio

For this expiriment i constructed portfolio using constituents of SP500 stocks. I rely on classical mean-variance portfolio optimization theory usnig historical mean returns of the stocks based on their daily adjusted closing prices and applying Ledoit Wolf shrinkage to covariance matrix. The stock prices ranges from 2014-01-01 till 2016-09-01.

I am also using The Robeco Total Sustainability Rank Envoronmental score to construct green portfolio: in addition to traditional constraints the weighted sum of environmental score of stocks included in the portfolio should be more or equal some seted treshold. The score ranges from 0 to 100: the higher the score - more environmetally friendly stock/portfolio is.

I compare the performance of green and  nongreen portfolios based on various scenarios.

The notebook has typos and  need some upgrades: nicer code, pictures and etc.
