# Recommendation-Engine-for-Items-Combo-Offers

This is a recommendation model which aims to provide the best combos of items to provide any offers on the set of products to improve the shop's profits.
It is a Market Basket Analysis using Apriori Algorithm

## Required Softwares

-> Python 3.x above

-> mlxtend library

-> Pandas library

-> Numpy library

-> sklearn Library


## To Run
-> Download all the files.

-> Open the Apriori_Algorithm.pynb file using jupyter notebook in Anaconda in your computer

-> Run all cells to execute and learn the recommendation Engine.


## Recommendation Engine Working

-> Firstly collected an Online Retails Store Data consisting of different Invoices with the items purchased. This Retail Store is based in many countries such as Australia, France, United Kingdom and many more.

-> Then I applied feature engineering and data cleaning techniques on the data using sklearn, pandas and numpy library to remove some unnecessary noise in the data and made the data suitable for learning different patterns among the items.

-> Converted all the items purchased as features, which can be easily trained on the Apriori algorithm to find the association rules.

-> Built the Recommendation Engine which learns the data using Apriori Algorithm by importing from mlextend.frequent_patterns library and selects the best combo of items, given the support, lift and confidence we want.


