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
![GIF for GDP Distribution Across Countries[]{label="fig:GDP across countries in different time"}](Gdp_per_capita.gif)
###### Figure 4: GDP per Capita for each country for each year

and here was can see the distribution of GPD per capita for each continent calculated by getting mean of GDP for given year for countries in that continent.
![GIF for GDP Distribution Across Continents[]{label="fig:GDP across continents in different time"}](gdp_continents.png)
###### Figure 5: GDP per Capita for each country for each year

We can observe that GDP per capita across has been low all the time while it is highest for Europe.
For America and Asia, they're following each other with time.

## Solution 3:

In this part, we'd to vizualize GDP Per Capita, Life Expectancy and Child Mortality.

Basic transrmation is similar i.e. mapping each data frame to country and continent and then merging them using time, country and continent as the key.

Here's the plot for overall GDP vs Life Expectancy Vs Child mortality around the world which is calculated by taking the mean values of all 3 variables for each year.

![GIF for GDP Distribution Across Continents[]{label="fig:Overall GDP Vs Child Mortality Vs Life Expectancy}](overall_life_gdp.png)
###### Figure 6: Overall Life Expectancy Vs GDP per Capita Vs Child Mortality Rate

We can observe that Life Exopectancy goes hand in hand with GDP per capita i.e. they've higher correlation. As expected negative relationship with Child Mortality,

Here's the distribution for each continent.
![GIF for GDP Distribution Across Europe[]{label="fig:GDP Vs Child Mortality Vs Life Expectancy"}](europe_life_gdp.png)
###### Figure 7: GDP per Capita for each country in Europe for each year

![GIF for GDP Distribution Across Asia[]{label="fig:GDP Vs Child Mortality Vs Life Expectancy"}](asia_life_gdp.png)
###### Figure 8: GDP per Capita for each country in Asia for each year


![GIF for GDP Distribution Across America[]{label="fig:GDP Vs Child Mortality Vs Life Expectancy"}](america_life_gdp.png)
###### Figure 9: GDP per Capita for each country in Americafor each year

![GIF for GDP Distribution Across Africa[]{label="fig:GDP across continents in different time"}](africa_gdp_life.png)
###### Figure 10: GDP per Capita for each country in Africa for each year


