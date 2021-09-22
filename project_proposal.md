### Project Proposal - Board Game Price Prediction

#### Question/need:
* My goal in this project is to use board game data from boardgamegeek.com to find which features affect the price of games.
* This analysis would help in finding that lost gem, or criminally undervalued game that would allow users to find games they feel meet their individual gaming requirements, along with their budget.
* Game store owners would have incentives to market certain games: i.e., focus on certain genres, cult classics, or user ratings vs. professional ratings.

#### Data Description:
* I will be using publicly accessible data from boardgamegeeks.com which allows webscraping.
* Features that I will be gathering are the current rank of the game, year it was created, professional and user ratings, number of votes that went into user ratings, current available price of game from Amazon, playing time, number of players allowed, age recommendations, the complexity score, page views and all-time plays.
* These statistics are available on the website on each game's landing page

#### Tools:
* This information is being scraped from the website using Python/BeautifulSoup and then further data manipulation using Pandas. Scikitlearn will be used for linear regression modeling as well as visualizations using scikitlearn, matplotlib and seaborn as needed.

#### MVP Goal:
* A minimum viable product will be providing which board game features affect the price, along with visualizations of these relationships and the accompanying regression statistics.
