# Data Science Reflection 2


Every year tens of billions of dollars is spent on sports gambling worldwide. However, there is a saying in gambling that “the house always wins”, meaning that for the most part, casinos and the Vegas oddsmakers earn more money than they payout. An example of this is the often used 10 to win 9 odds. Oddsmakers will often set wagers where you can bet $10 and if you win the bet you win $9. So, even if the two teams are equally skilled, and it seems like nobody has an advantage, the house will still win more money than it loses in the long run. Still, this does not stop tens of millions of Americans and people worldwide from trying betting on sports every day. But, what if there was a way to use data science that eliminated the chance aspect of sports betting, and could in some way give you a statistical advantage? Wouldn’t that make sports betting a worthwhile endeavor? 
  
 This is where data science comes into play. “One of the common machine learning tasks, which involves predicting a target variable in previously unseen data, is classification. The aim of classification is to predict a target variable (class) by building a classification model based on a training dataset, and then utilizing that model to predict the value of the class of test data ...  Sport prediction is usually treated as a classification problem, with one class (win, lose, or draw) to be predicted.” This example of machine learning is good to identify because it is similar to a lot of the data science methods used in sports betting. The goal of most of them is to create an algorithm that can predict the winner of a game based off of previous statistics from the season. However there is one main issue with this, and that is that the oddsmakers often have access to similar methods, and set spreads that aren’t even. This means that instead of having the odds set at 10 to win 9 and having an even spread (both teams are equally favored), the oddsmaker can set the spread to favor a team. For example, if you were betting on the NBA finals game 2 on Friday, the money line is set at -8 for the Lakers. This means that if you bet $10 on the Lakers to win the spread, not only do they have to win, but they have to win by more than 8 points for you to make money. This example is how the oddsmakers use data science to ensure the house always wins; by making spreads thats goals are to make the betting chances even, and making the risk higher for the gambler than the house. 
  
 Now, you may be asking yourself how data science is effective in sports betting if oddsmakers are using it to beat gamblers. But, there is another way in which machine learning is effective to help the gambler. “What we have seen above is that bookmakers make a profit by controlling the payout. In order to do so they have to set the odds accordingly. For this, they need to know the probabilities. An omniscient bookmaker who gets all probabilities spot on cannot be beaten (in the long run). But bookmakers are not omniscient and therefore there are two ways in which they can be beaten, purely based on estimating the probabilities better. 1) If you consistently assess the probability better than the bookmaker, by such a margin that you make up for the leeway they have built into the payout. 2) If you only bet on those games where you know the bookmaker made a mistake and the odds are ‘fair’.” Thus, the goal of machine learning methods in sports gambling should not be centered around predicting what team will win, or what play will do better, but instead around finding the mistakes of the oddsmaker that give you a statistical advantage. The goal is to use a machine learning model with a custom loss function — with the objective to identify shortcomings in the bookmaker odds and make profit. 

See the loss function below:

![Screen Shot 2020-10-01 at 2 22 36 PM](https://user-images.githubusercontent.com/60228369/94859521-a8995980-0402-11eb-887a-aa1a05233b0e.png)


“This loss function ensures that what we are optimizing is not how well we can predict the outcome of a game, but rather our winnings. Note that as a consequence of our custom loss function, the predicted probabilities are not representative of the true probabilities, since when the model thinks the bookmakers are off it will push the probabilities towards the extremes (0 or 1)
in order to bet more.”

In closing, being successful in sports betting is not about being able to predict the sports games correctly but instead identify when oddsmakers have made errors placing the odds in your favor. Machine learning in sports betting is best utilized in order to identify statistical errors, rather than predict the outcomes of games. 


## Bibliography:
1) Bunker, Rory P., and Fadi Thabtah. “A Machine Learning Framework for Sport Result Prediction.” Applied Computing and Informatics. No longer published by Elsevier, September 19, 2017. https://www.sciencedirect.com/science/article/pii/S2210832717301485. 

2) Bartles, Richard. “Beating the Bookies with Machine Learning.” KDnuggets. Accessed October 1, 2020. https://www.kdnuggets.com/2019/03/beating-bookies-machine-learning.html.



