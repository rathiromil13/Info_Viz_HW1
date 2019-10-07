# HW-1


## Solution 1:

My score in quiz was 4/13. I think I was being pessimist regarding a lot of questions especially regarding Population Distribution and Life Expectancy.

Overall, many questions were interesting. I decided to explore the population distribution across countries and continents and vizualize it. The question was regarding the distribution of population around major continents.

To perform this task,I mapped Population Data with Country and Continent Data. Then, some column names were adjusted to make sure they're meaningful and not too long.
Aggregation was done by taking the mean population for current year for both countries as well as continents.

![Plot for Polulation Distribution Across Continents[]{label="fig:Population for Continents"}](population_continent.png)
###### Figure 1: Population Distribution Across Continents

It clearly shows Asia has the highest population (~ around 4BN) among all continents. Now let's us look at distribution across countries

![Plot for Polulation Distribution Across Countries[]{label="fig:Population for Countries"}](population_countries.png)
###### Figure 2: Population Distribution Across Countries

It shows that majority of population resides only in India and China. Leaving these two countries aside, overall population is considerable low.

Now let's look at Population Density:
![Plot for Polulation Density[]{label="fig:Population Density"}](pop_density.png)
###### Figure 3: Population Distribution Across Countries

The corresponding plot shows some interesting results
(i) Africa has the lowest population density
(ii) Europe and Asia are very close in terms of average population density.


## Solution 2:

For this problem, I selected GDP per Capita Data adjusted in US Inflated price so that the scale remains same for all countries.

The basic transformation are similar, mapping GDP data to Country and Continents data so as to get their proper names.
Percentage Change in GDP for similar countries across different year was also calculated and stored in a new column named "pct_gdp_change"

The following GIF was obtained from Distribution of GDP per capita for each country for each year.
![GIF for Polulation Distribution Across Countries[]{label="fig:GDP across countries in different time"}](Gdp_per_capita.gif)
###### Figure 4: GDP per Capita for each country for each year
