# fifa-modeling
Data analysis using data from FIFA, a soccer video game, to help with in game management. The two questions that were explored were: 

1. Can we create a model that can predict which kinds of players would be more suitable to play as a different position? Using a model like this would help players find new soccer players that would fit best into the positions they currently lack.
2. What are the most important factors in determining the potential rating for a player? The potential rating states how good a player might be in the future. If you were to know how to predict what this rating might be, then you could find the next Lionel Messi.

Included is an HTML file of the written data analysis that explains the data, our questions in greater detail, our results, and most importantly the statistical and analytical methods we used to come to those results. Be sure to download the file to view it properly. 
Also included is the RMD file of the code and the data used so that you can run in R Studio youself. 

This project and analysis gave me expierence in many parts of statistics and data analysis including but not limited to:

1. Data cleaning and scrubbing. Using the dplyr and tidyverse packages in R Studio, we created new variables based on what our analysis would need; cleaned the data by removing unnessesary text such as hyphens and underscores so we could properly utilitze the data to answer our questions; renamed and organized variables and object better so the analysis would be presentable in a paper. 
2. Variable selection. Using best subset method from the package leaps, we were able to determine which variables were the most important in explaining a players overall and potential. This required us knowing how to interpret the R^2 and Mallows CP to know which variables to select.
3. Linear Regression. Using the variables selected using the best subset method, we were able to perform a linear regression on the data, as well as interpret it in our paper. 
