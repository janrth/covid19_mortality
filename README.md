# covid19_mortality

I have pulled monthly mortality UN data, which is available here http://data.un.org/Data.aspx?d=POP&f=tableCode%3A65.
My goal was to predict monthly mortality for a whole year. I picked Italy as a country and made my forecast for 2018. First I developed a baseline model using monthly average 
numbers from previous years, followed by an SARIMA model, where I tuned some parameters. In the end I compared the two models. The SARIMA model was better in most of the errors 
I calculated.

As I am not an expert in time-series analysis, I just wanted to see if I would be able to train an (S)ARIMA model an outperform some simple baseline model. A use case for this 
would be to calculate excess deathes for a specific period. This could be covid19 in 2020 for Italy by comparing the time-series prediction against the observed deathes per months.
