# Effect-of-Roller-Coaster-Statistics-on-Ranking
This repository contains code for an analysis I performed into the extent to which roller coaster statistics affect its community ranking.

In theme park enthusiast circles, people commonly dismiss statistics as an important factor in how highly a roller coaster is rated, 
so I decided to analyse the effect that 5 different statistics (height, speed, length, number of inversions and opening year) have on a roller coaster's community ranking 
using data from Captain Coaster. When correlation analyses were performed, it was found that height, speed and to a lesser extent length were all significantly correlated 
with ranking. Speed had a particularly strong correlation, with its coefficient bordering on the threshold of a strong correlation. Inversions and opening year were less 
significantly correlated with ranking, meaning that neither have an overly significant effect in isolation. As such, the first stage of the analysis concluded that 
"statistics aren't everything" to some extent depending on the statistics you choose, but that some do have a definite positive effect on ranking on average.

Further to this, I also built regression models to determine how accurate raw statistics are as a predictor of a coaster's community ranking. I tested three model types; 
linear regression, random forest regression and a neural network. The random forest regressor returned the highest accuracy, being able to account for around 65% of the 
variation in rankings. Correlation-based feature filtering was also attempted, with height, speed and length alone being tested as predictors, but this did not add any benefit. 
These results prove that raw statistics are useful to an extent, but that they alone cannot provide a particularly accurate prediction of community ranking, with qualitative 
aspects of a roller coaster also playing a highly important role.

The analysis was performed in two separate notebooks. The first contains the correlation analyses, consisting of data visualisations and hypothesis testing to determine the
statistical significance of the correlation between various roller coaster statistics and community ranking, while the second contains the regression models built to test
the efficacy of raw statistics at predicting community ranking.

The raw dataset used can be viewed here: https://docs.google.com/spreadsheets/d/1OfxlATMBJJwN1VjW7sb0jKwIFywJcACbZYJHIxbjdVc/edit?usp=sharing

Both parts of the full analysis can be read here: 
https://coasterforce.com/forums/threads/statistics-arent-everything-to-what-extent-is-this-true-a-statistical-analysis-into-how-roller-coaster-statistics-affect-ranking.47515/



