# ml4t_MS2
homework for ML4T module 2

There are two parts of the instructions that were unclear.
The submissions for the various metrics (e.g., SMA, BB) could be run for individual
stocks, or could be run for the entire universe of the top 500 selected earlier in the
tutorial. Since the output of the analyses are data series that need to be visualized, it
didn't seem logical to generate 500 of them, even though the earlier parts of the tutorial
implied that they should be. I ran the metrics for the stock with the largest average daily
volume.

Logically, in the context of this tutorial, the Fama-French task should be to create a regression 
of a stock, or maybe of the portfolio of 500 stocks - this wasn't clear. To create the regression
equation, additional data series are necessary, e.g., risk-free interest rate, SMB, HML. It was
not clear to me whether this data was to be obtained from the Ken French data repository, or some
other source. I decided to submit my assignment with this part incomplete.
I did, however, run through the tutorials I was pointed to for estimating the FF model.
