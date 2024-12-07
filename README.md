# PortfolioSimulator
Simulating portfolio returns

Features:
  1.Different inputs allow you to flexibly apply the simulator to your situation
  2. Different allocations between stocks and bonds across the lifecycle of an investor
  3. Graph plotting final portfolio sizes for each simulation using your inputs
  4. Table showing percentiles of portfolio outcomes displaying left tail risk
  5. Table showing the probability of the simulations that met the adjustable retirement goal
  6. Model always assumes annual rebalancing
  
Details:
  1. The data is historical annual US stock returns, 10-year bond returns, and annual inflation rate from the years 1928 to 2023
  2. The block bootstrap sampling method allows serially correlated data to remain serially correlated while also allowing randomness to remain in the data

Planned additional features
  1. Comparison tool to compare different parameters
  2. Post-retirement tool for assessing things like the "4% rule" and considering social security
  3. Adding features for different rebalancing schemes (annually, 5% out of balance, no rebalancing, etc)
  4. Better figures
