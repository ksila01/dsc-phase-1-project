# Analyzing Movie Data for Microsoft
![Microsoft](https://github.com/ksila01/dsc-phase-1-project/blob/main/image%2010.png)
![Microsoft](https://github.com/ksila01/dsc-phase-1-project/blob/main/download.jpg)
## Project Overview

This project utilizes exploratory data analysis to explore trends such as production, release, and profitability of movie genres since 2015. The project will utilize various datasets with basic movie information and financial data. The project will visually display the results of the analysis to help Microsoft in making informed decisions when venturing into the movie industry
### Business Problem

Microsoft wants to diversify its business from just producing software programs to now creating its on movie studio that will store its original movie contents. The move is intended to help the giant tech remain competitive in the dynamic tech world. Thus, the analysis will provide recommendations on movie genres and release_month appropriate for the company to release its movies
### The Data

Data utilized in this project will include datasets from;
**imdb.name.basics.csv.gz
**imdb.title.basics.csv.gz
**tn.movie_budgets.csv.gz
* [IMDB](https://github.com/ksila01/dsc-phase-1-project/blob/main/download.png)

## Parameters

Since Microsoft is an international company, this analysis used the worldwide gross in terms of the production budget, profit, and profit margin. Also, since most movies were produced between 2018 to 2019, I included the current inflation rate of 0.297 to provide Microsoft with the best advice per the 2023 economy. Thus, the adjusted budget, adjusted profit, and adjusted profit margin have put into consideration the inflation rates

### Research Questions

1. **Which movies were most profitable since 2015 and what was their budget?.** 
2. **Which genres with most produced movies?.** 
3. **Which genres have the most user ratings? Do high ratings translate to high-profit margins?.** 
4. **What is the best time of the year to release a movie?** 

## Results

Avengers: Affinity Wars had the biggest return on investment in terms of the production budget and the profit it earned. The top 20 successful movies had a median production budget of 1.955 Billion Dollars and a profit margin of 85.7%
![Production_budget, profit vs Movies](https://github.com/ksila01/dsc-phase-1-project/blob/main/image%201.png)

Genres with most produced movies include Drama, Comedy, and Action
![most produced genres](https://github.com/ksila01/dsc-phase-1-project/blob/main/Image%203.png)

Genres with the highest ratings include Musical, History, and Sport
![Highest Ratings](https://github.com/ksila01/dsc-phase-1-project/blob/main/Image%204.png)

The highest rating does not necessarily mean the highest profit margin except for exceptional cases such as musicals which have the highest ratings and highest profit_margin
![Ratings Vs Profit](https://github.com/ksila01/dsc-phase-1-project/blob/main/Image%205.png)

Genres with the highest production costs include musical, adventure, and fantasy while those with the lowest production costs include war, horror, and mystery
![Highest and Lowest Production Cost](https://github.com/ksila01/dsc-phase-1-project/blob/main/Image%206.png)

Months with the most movie_releases are November, October, and December
![Highest Release Months](https://github.com/ksila01/dsc-phase-1-project/blob/main/Image%207.png)

The best month to release a movie best on the profit margins of the release month is July
![Best Release Month](https://github.com/ksila01/dsc-phase-1-project/blob/main/Image%208.png)

## conclusions

1. Given the findings from the above analysis, Microsoft can consider investing in Musical
genres since I don’t think the production budget will be a big challenge for the giant tech
company
2. Such a genre will make the organization have a good return on investments and
maintain its reputation
3. Alternatively, the company can choose low-budget movies such as horror which also
has high returns.
4. However, since the horror genre has the lowest ratings, it should be a secondary option after
musicals
