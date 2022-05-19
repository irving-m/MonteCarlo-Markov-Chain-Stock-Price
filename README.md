# MonteCarlo-Markov-Chain-Stock-Price
This algorithm consists of a Monte Carlo simulation applied to a Markov Chain that describes a random path price, representing a stock price.
It draws random samples from a given probability density function, forming a vector of these random samples. 
After, the vector is transformed via some operations and plugged into a vector of prices. Since these prices have been generated through a random and independent process,
they will be a Markov Chain, somewhat resembling the random movement of the stock price of certain firm.
Afterwars, this process is repeated an arbitrary number of times, and they can be drawn with ggplot, as to gain a visual grasp of the model findings. 
