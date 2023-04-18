# Comparison of Value at Risk of stock indices computed with different methods

This is an academic project, hence written in polish language.

# Summary in english

In the project, VaR was determined for three stock market indices from January 1, 2006 to December 31, 2021. Each of the three methods used allowed for obtaining different plots, but all showed an increase in VaR and ES in key moments for the global economy, such as the crisis in 2008 year and the lockdown caused by the COVID-19 pandemic in 2020. In addition, each of the indices recorded its individual highs and lows, most likely caused by events in the local markets.
The model that - based on charts - works best in crisis situations is the historical simulation method that takes into account the heteroscedasticity of returns. The other two methods "remember" rapid changes in the market longer, while not reacting to them strongly enough at the beginning of their occurrence.
On the basis of backtests, which examined the quality of VaRu determination for each of the methods, it can be assumed that the Monte Carlo method is the worst of the methods. At the same time, it is worth noting that these tests were based only on the number of exceptions (calculated in various ways) and did not take into account whether VaRu exceedances were independent over time. Perhaps conducting the Christofferson test for all three methods would indicate their strengths or weaknesses that are not visible in the current comparison.
