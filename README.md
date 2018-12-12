# Data-Manipulation-and-Analysis
Course work for SI 618 Data Manipulation and Analysis

### Motivation:
- Crypto currency is a new type of currency circulating in the market. With Bitcoin invented in 2009, now there emerges over 2,000 types of crypto currencies and has a total market value more than 110 billion [https://coinmarketcap.com]. The price movement is exciting like riding with roller coaster, but people really don't know much about this virtual asset.
- In this project, I will analyze the historical crypto trading dataset, to portrait its dynamic landscape, dig into features of crypto currencies, analyze if any patterns in their price movement.

### Interested Research Questions:
1. How is the market of crypto currency emerging? Which currency has a leading position in the market? Do they survive or die over time?
2. Explore the statistical characteristics of daily log return, how can we model it with distribution? Are different currencies show similar pattern?
3. Crypto currency are virtual assets, do they have correlation with real world financial assets, e.g. USD, Gold price, stock indices. Can we use regression models to explain the dynamics of Crypto by real assets?
4. What is the best currency to buy? Use Machine Learning techniques to select currencies with best performance.

### Dataset Source:
- From kaggle website, download dataset crypto-markets.csv, data updated on Dec 01, 2018
- URL: https://www.kaggle.com/jessevent/all-crypto-currencies
- Observations: 942,297, Variables: 13, Crypto Tokens: 2,071
- From Yahoo finance and quandl, use pandas_datareader to download daily data from 2017-01-01 to 2018-11-30 for USD, gold price and stock index. Merge with crypto dataset by date.
