## Welcome to Zack's Arena

Hello, Welcome to my Githbub website! I will be posting BDA-594 Web Exercise solutions on this webiste. 

## Premier League Match Report 2019-2020

[Premier League 19/20 dataset](https://www.kaggle.com/ekrembayar/premier-league-match-reports-20192020 ).

The above mentioned dataset is a publicly available Premier League dataset on Kaggle maintained by Ekrem Bayar. Premier League also known as English Premier League is a top tier soccer league in England where 20 teams compete for the title every year. The given dataset is a collection of the key data points of the Premier League 2019-20 season. 

The following is an overview of the dataset:

 | Usage | Public |
 | Provenance | Ekrem Bayar |
 | Columns | 33 |
 | Rows | 760 |
 | Update Frequency | Annually |
 | Last Updated on | 8th August 2020 |



The following are the metadata details of the dataset:


The given dataset can help conduct a detailed performance analysis at the end of the season to help prepare for the upcoming season. The analysis on this dataset can not only help improve team performance but also can also help scout potential young players. The idea of data analysis in Soccer is relatively new and has a huge potential to disrupt the way the football clubs conduct their scouting and analysis.

The following are the potential applications of the Premier League 19/20 Dataset: 

  1. Player analysis
  2. Team analysis
  3. Smart Scouting
  4. Scores Prediction






As mentioned earlier, the concept of Sports Analytics is relatively new for the football industry. But over the last decade, there has been a significant increase in the usage of analytics in soccer. The majority of the credit goes to the writer Micheal Lewis and his book “Moneyball: The art of winning an unfair game”. The book introduces the concept of Sports Analytics and how Oakland Athletics, a baseball team and its general manager Mr. Billy Beane along with Peter Brand used sports analytics techniques to conduct smart scouting of players. Using this strategy, Oakland Athletics secured a 20 games winning streak between August and September 2002.

The above dataset can help answer some of the most basic questions like:

  1. Who has scored the most number of goals?
  2. Who has made the most assists?
  3. Which player has the most number of red cards? 
  4. Which player has the most number of yellow cards?
  5. Which goalkeeper has kept the most number of clean sheets?

The dataset can also help answer some of the advanced questions question such as:

  1. Which player has overperformed on the basis of expected goals & assists?
  2. Which player has underperformed on the basis of expected goals & assists?
  3. Who has the best shot conversion rate in the league?
  4. What is the style of play of a particular team? ( This can be determined by examining the type of passes made by the team. For example: If a team has a lower percentage of possession and more long passes compared to short passes, then the likelihood of them playing on the counter attack is pretty high. Similarly, if a team has more ball possession and higher number of close range passes then it is likely that the team’s style of play is based on 3 P’s i.e, Possession, position and passing.

Sometimes, only numbers can be misleading and further in depth analysis would be needed to determine the root cause of it. To explain it further, let's study the example of Newcastle United’s 2011/2012 premier league season in which they finished 5th on the table. Here’s how the point table looked like for the top 6 teams:

| Club | Matches Played | Won | Draw | Lost | Points |
| Manchester City | 38 | 28 | 5 | 5 | 89 |
| Manchester United |38 |28 | 5 | 5 | 89 |
| Arsenal | 38 | 21 | 7 | 10 | 70 |
| Tottenham |38| 20 | 9 | 9 | 69 |
| Newcastle United | 38 | 19 | 8 | 11 | 65 |
| Chelsea | 38 | 18 | 10 | 10 | 64 |

**Note**: After looking at the above table it seems as if Newcastle played better than Chelsea. But is that the case? Let's dig a bit deeper to find the answers.
We will introduce three new attributes i.e, Goals Scored, Goals Conceded, Goal Difference (Goals Scored -  Goals Conceded). Here's how the new table looks like:

| Club | Matches Played | Won | Draw | Lost | Goals Scored | Goals Conceded | Goal Difference | Points |
| Manchester City | 38 | 28 | 5 | 5 | 93 | 29 | 64| 89 |
| Manchester United |38 |28 | 5 | 5 | 89| 33 |56 | 89 |
| Arsenal | 38 | 21 | 7 | 10 | 74| 49 |25 | 70 |
| Tottenham |38| 20 | 9 | 9 | 66 | 41| 25 | 69 |
| Newcastle United | 38 | 19 | 8 | 11 | 56 | 51 | 5 | 65 |
| Chelsea | 38 | 18 | 10 | 10 | 65 | 46 | 19 | 64 |

From the above table we can see that, although Newcastle secured 65 points and the 5th Place, their attacking and defensive contributions were below par compared to the remainder of top 6 teams (Goal difference of only 5 ). Hence, we can say that the points table doesn't always go hand in hand with the actual team performance.
**The Premier League 2019/20 Dataset** will help us find more of such inconsistencies and will allow the managers to make better informed decisions.

## R and Data Mining: Examples and Case Studies

[ R and Data Mining: Examples and Case Studies ](https://cran.r-project.org/doc/contrib/Zhao_R_and_data_mining.pdf).


The above-mentioned book is written by Yanchang Zhao and was published by Elsevier in December 2012. The book majorly focuses on the usage of R for various data mining applications. The reason why I chose this book is because it introduces the basic definition of Data Mining, various data mining techniques along with real world applications. The author concisely describes how data mining applications can be broken down into six major phases i.e, business understanding, data understanding, data preparation, modeling, evaluation and deployment. What I like the most about the book is that the author not only covers the theoretical aspects of data mining but also provides hands-on experience of R programming on various datasets.The book begins with introducing how data can be imported and exported from various data sources into the R environment. Next it introduces how we can examine the data in terms of dimensionality as well as the structure of the data and use various plots to further 
The author also introduces the readers to various datasets that can be analysed using various R packages such as lattice, ggplot, rpart amongst others. The author very neatly describes how and when different kinds of plots should be used based on the types of data points available.
I believe that this information is very crucial as the usage of inappropriate graphs or plots can lead to misrepresentation of information which might lead to a catastrophe.

Author also sheds light on various types of machine learning algorithms such as Regression, Clustering, Decio Trees and Outlier Detection along with their usage and their effectiveness on various kinds of data. I believe that this section is very useful for a person who aspires to be a data scientist as it is crucial to understand the working of algorithms and also selecting the one that would best fit the given use case.

 Overall I believe that this book is very comprehensive and is a good starting point for the people who want to get started with data science with R programming. The book explains each chapter in detail along with hands-on exercise for the same. 
