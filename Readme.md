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

![Plot for GDP Distribution Across Continents[]{label="fig:Overall GDP Vs Child Mortality Vs Life Expectancy}](overall_life_gdp.png)
###### Figure 6: Overall Life Expectancy Vs GDP per Capita Vs Child Mortality Rate

We can observe that Life Exopectancy goes hand in hand with GDP per capita i.e. they've higher correlation. As expected negative relationship with Child Mortality,

Here's the distribution for each continent. 
The Life Expectancy for Africa value as well as range is relatively less than other three continents while it is relatively high for Europe.

![Plot for GDP Distribution Across Europe[]{label="fig:GDP Vs Child Mortality Vs Life Expectancy"}](europe_life_gdp.png)
###### Figure 7: Life Expectancy Vs GDP per Capita Vs Child Mortality Rate in Europe for each year


![Plot for GDP Distribution Across Asia[]{label="fig:GDP Vs Child Mortality Vs Life Expectancy"}](asia_life_gdp.png)
###### Figure 8: Life Expectancy Vs GDP per Capita Vs Child Mortality Rate in Asia for each year


![Plot for GDP Distribution Across America[]{label="fig:GDP Vs Child Mortality Vs Life Expectancy"}](america_life_gdp.png)
###### Figure 9: Life Expectancy Vs GDP per Capita Vs Child Mortality Rate in America for each year


![Plot for GDP Distribution Across Africa[]{label="fig:GDP across continents in different time"}](africa_gdp_life.png)
###### Figure 10: Life Expectancy Vs GDP per Capita Vs Child Mortality Rate in Africa for each year

At the same time, Child Mortality rate is very high in Africa as compared to other continents.

The common Trend to be observed is that GDP per Capita and Average Life Expectancy is increasing everywhere wherease Child mortality is decreasing. 


## Solution 4:

The two variables that I'm analyzing here are "Co2 Emission" and "GDP Per Capita". These variables are interesting to see in today's scenario where there is a divided opinion on Climate Change and Co2 Emission in each country.

The transformation are similar to previous problems:
(i) Identify the dataframe for Co2 emission.
(ii) Map it to Countries and Continent.
(iii) Merge it with already existing dataframe for GDP per capita.
(iv) Aggregate it for each continent for each year.

The opinion is that with increase in GDP per capita, continent's overall co2 emission per year should increase as demands for products will increase.


![Plot Co2 Emission Vs GDP Per Capita Distribution Across Africa[]{label="fig:Co2 emission vs GDP for Africa"}](africa_c02.png)
###### Figure 11: Co2 Emission Vs GDP per capita in Africa

In Africa, we can see that Co2 Emission over years is growing at similar rate to GDP per capita but on comparison with other continents, Africa has very high Co2 emission rate as compared to their GDP. This could be due to abundance of forest and thus activities such as deforestation.

![Plot Co2 Emission Vs GDP Per Capita Distribution Across Europe[]{label="fig:Co2 emission vs GDP for"}](europe_co2.png)
###### Figure 12: Co2 Emission Vs GDP per capita in Europe

Europe is an exciting case, as we can see it is defying the original trend of increase in Co2 emission with increase in GDP  per capita. In past few years, while thier GDP is increasing, their Co2 emission is decreasing.

![Plot Co2 Emission Vs GDP Per Capita Distribution Across America[]{label="fig:Co2 emission vs GDP for"}](america_co2.png)
###### Figure 13: Co2 Emission Vs GDP per capita in America

In America, we can see a spike around 1970, it shows that during 1960-1980, their Co2 Emission was growing abnormally high, which could be attributed to Cold War with USSR.
But Overall, it still is increasing, at a slower rate though.

![Plot Co2 Emission Vs GDP Per Capita Distribution Across Asia[]{label="fig:Co2 emission vs GDP for"}](asia_co2.png)
###### Figure 14: Co2 Emission Vs GDP per capita in Asia

In Asia, the growth of Co2 emission is steady with GDP per capita but it turns out to be the highest contributor of Co2 emissions than any other continent.


## Solution 5:

For this assignment, I've used a combination of static and interactive plots.

Static Plot:

Advantages of Static Plots over Interactive plots:
(i) It takes less time to generate a static plot than interactive plot.
(ii) It is useful to use in scientific or any other literature in print or pdf.
(iii) It is cheaper to build.
(iv) Easy to read when number of variables is low, interpretation is not complicated usually.


Advantages of Interactive Plots over Static Plots:
(i) Interactive plots are impressive and visually appealing.
(ii) Interactive plots gives the ability to user to control what to see on plot and what not.
(iii) It is very useful when there are multiple variables to observe.
(iv) Interactive plots makes it easier to understand when there are lots of data point in a variable, for example in the country data above, interactive plot will make it more readable.

