# Week 5 Exercises: Statistics for Data Science

### Part 1: Differences in Means
1. In this question, we'll use the penguins dataset. Read this into a DataFrame named `penguins`. We're only going to focus on two of the species, adelie and chinstrap, so filter down to these two using the following code:
```
penguins = penguins[penguins['species'].isin(['Adelie', 'Chinstrap'])]
```
a. Take a look at the distribution of body mass for these two species. What do you notice?

b. Test the hypothesis that the distribution of body masses is different for these two species. Do this by using the difference in means as your test statistic. What conclusion do you reach? Use the 0.05 significance level.

c. Challenge question: Test whether there is a difference in the standard deviation of body mass between the two species. Hint: You'll need to run a permutation test for this. Use the difference in standard deviations as your test statistic. What conclusion do you reach now? Use the 0.05 significance level.


### Part 2: Tests for Dependence
1. In this question and the next, you'll be looking at shooting data from NBA games that took place during the 2014/2015 NBA season. We'll be working with data from one particular player, Steph Curry, who is widely regarded as one of the greatest shooters in NBA history. You have been provided a dataset, curry_shooting.csv, which contains all shots that Steph Curry took during the 2014/2015 NBA season. Read this dataset into a DataFrame named `shots`.

The SHOT_RESULT column indicates whether a particular shot was successful, and the PERIOD column shows which quarter (1-4) or overtime period (5) the shot took place. In this question, we'll explore whether the PERIOD and SHOT_RESULT columns are independent or dependent.

a. Create a cross-tabulation to look at Curry's makes/misses vs. game period. What do you notice?

b. Run a hypothesis test for whether Curry's makes/misses and game period are dependent.

c. In the NBA players can earn more points for a successful basket that is made from behind the 3-point line. The type of shot (2-pointer vs 3-pointer) is indicated by the PTS_TYPE column. Test whether PTS_TYPE and SHOT_RESULT are dependent for Steph Curry.

2. In the week 3 exercises, we examined the relationship between rain_today, rain_yesterday, and day_of week. Now, let's perform hypothesis tests to see if the observed dependence we saw holds up to a statistical test. Read in the data from bna_rain.csv into a DataFrame named bna_rain.

a. Test whether rained_today and rained_yesterday are dependent.

b. Test whether rained_today and day_of_week are dependent.

### Part 3: Test for Correlation
Read in the file shifted_BNA_temps.csv into a DataFrame named bna. 

1. In week 2, we saw that there was a moderate positive correlation between TMAX and TMAX_LY. Run a hypothesis test to see if this correlation is statistically significant.

2. In week 2, we saw that there was a very small positive correlation between TMAX and TMAX_3MO. Run a hypothesis test to see if this correlation is statistically significant.