# Bal-vs-LA-python

## Background
Socioeconomic mobility in the United States refers to the upward or downward movement of Americans from one social class or economic level to another, 
through job changes, inheritance, marriage, connections, tax changes, innovation, illegal activities, hard work, lobbying, luck, health changes or other factors.

In recent years, several studies have found that vertical intergenerational mobility is lower in the US than in some European countries.
US social mobility has either remained unchanged or decreased since the 1970s.[A study conducted by the Pew Charitable Trusts 
found that the bottom quintile is 57% likely to experience upward mobility and only 7% to experience downward mobility.

This project uses python to compare and analyze the individual income level for those grew up in lower socioeconomic class in Baltimore and Los Angeles respectively to
conclude about the different social mobility in these two cities.

## Business Question
How do people from lower socioeconomic class in Baltimore and Los Angeles perform in terms of their individual income? 

## Data Question
What are the similarities and differences between individual income for lower socioeconomic class in Baltimore and Los Angles, and what are the possible reasons behind these disparities? 

## Data Metrics
- mean individual income 
- median individual income
- standard deviation of individual income
- percentage of outliers: outliers of the two population who have extremelt high or extremely low income
- skewneww of individual income: refers to assymtery in the gaussian distribution of the two population samples, indicates the likelihood of an event falling in the tails of probability distribution.

## Data Source
[Oppurtunity Atlas](https://www.opportunityatlas.org)
 
## Data Analysis
We will use python to answer: what is the mean, median, standard deviation, percentage of outliers, skewness of the two population?

### Baltimore
- mean: 23248.80
- median: 22348.0
- standard deviation: 4761.92
- percentage of outliers: 1.16%
- skewness: -1.06
  
<img width="505" alt="Screen Shot 2020-11-22 at 22 22 13" src="https://user-images.githubusercontent.com/70663111/99926873-39a8f480-2d11-11eb-9029-042a871bc7bd.png">
The individual income of population in Baltimore is highly negatively skewed.



### Los Angeles
- mean: 26638.46
- median: 26183.0
- standard deviation: 4178.82
- percentage of outliers: 3.02%
- skewness: -0.96

<img width="461" alt="Screen Shot 2020-11-22 at 22 27 07" src="https://user-images.githubusercontent.com/70663111/99927042-e1262700-2d11-11eb-881a-b1f30d6c0b4d.png">
The individual income of population in Baltimore is moderately negatively skewed.


## Summary
In general, the mean and median of both population agree with the different living standards (income & expense level) in Baltimore and Los Angeles. Both cities have
larger median than mean because of outliers. In Baltimore, there is a smaller variety of individual income for those from lower socioeconomic class. It is more likely that a person's individual income is underperfoming compared
with her socioeconomic group in Baltimore than in Los Angeles despite the fact that the highest individual income from Baltimore is far greater than that of Los Angeles.

More analysis such as cluster analysis and linear regression can be used to find the possible cause and better compare the socioeconomic mobility in two cities.

## Python
1. Check head and tail and clean data by substracting rows with any empty element so following calculations can work.
2. Define an outlier function that detects outliers of the data.
3. Calculate population mean, variance, standard deviations, percentage of outlier.
4. Plot histogram of the two data sets.
5. Fit the data using with normal distribution and find the skewness of each population.
6. Print the results from step 3.
