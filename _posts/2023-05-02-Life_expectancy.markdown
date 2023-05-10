---
layout: post
title:  "Life expectancy in Japan - A global perspective"
date:   2023-05-01 14:18:41 +0100
categories: jekyll update
full-width: true
---

**Introduction**

Japan currently has one of the highest life expectancies in the world, with an average life expectancy of 84 years. The country has experienced a consistent increase in life expectancy over the last 60 years, propelling it to the top of the rankings. In this article, we explore the global development of life expectancy, focusing on Japan. Get ready for an interactive journey that takes you from a worldwide perspective deep into the fascinating story of Japan. How has life expectancy developed globally? What factors contribute to a longer life? How has Japan unlocked its potential for longevity? And is there a limit to the human lifespan? If these questions pique your interest, this article is for you. 

**The last 60 years globally**

This chapter examines the global development of life expectancy over the last 60 years. [During this period, the worldwide life expectancy has increased from 50 to 72 years.](https://www.macrotrends.net/countries/WLD/world/life-expectancy) This remarkable development is particularly due to many countries in Asia, Africa, and South America catching up with the Western world.

<iframe src="/world.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="600"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>
*Data source: [Kaggle (WHO)](https://www.kaggle.com/datasets/ulrikthygepedersen/life-expectancy?fbclid=IwAR0JO7W1_G3prS0O48OITDxvSeQPm64MtaUOIbfNjBCzcHttAUh_tC3xJME)*

We see how drastically Africa has improved over the period. Meanwhile, the countries leading the pack in 1960, like the Scandinavian countries, Australia, Japan, and Canada, are still at the top in 2020. However, the gap between the top and the bottom has been reduced significantly. This is a positive development for global health equity. Worth noticing is also the remarkable improvement in China, which has gone from a life expectancy of 33 years in 1960 to 78 years in 2020. We made the following bar chart to better illustrate the sheer magnitude of this development.

<iframe src="/bokeh.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>
*Sources: [Kaggle (WHO data)](https://www.kaggle.com/datasets/ulrikthygepedersen/life-expectancy?fbclid=IwAR0JO7W1_G3prS0O48OITDxvSeQPm64MtaUOIbfNjBCzcHttAUh_tC3xJME)*

Developing countries like China and Afghanistan have seen the most considerable improvement in life expectancy. Developed countries like Japan and the Scandinavian countries have also seen an improvement, but less drastic. As one could expect, pushing the boundaries of human longevity becomes harder and harder. The different mortality rates also give rise to quite different population structures. The population is much younger in developing countries, while in developed countries, the population is much older. This is illustrated in the following plot.


<iframe src="/age.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>
*Sources: [PopulationPyramid.net (UN data)](https://www.populationpyramid.net/)*

Countries like Japan and China have had quite a shift in terms of their population pyramid. Going from the structure that characterizes developing countries, with a falling slope for each year, to a more balanced, or even upwards-going distribution. Meanwhile, India is somewhere in-between these two models, and countries like Afghanistan are still in the developing stage. However, a population with most people around retirement age is scary as well, as the working population has to support the retired population. This is a problem that Japan is facing right now and is one of the reasons why Japan is [struggling with its economy.](https://www.imf.org/en/News/Articles/2020/02/10/na021020-japan-demographic-shift-opens-door-to-reforms)

**Infant mortality: the key to improving life expectancy in undeveloped countries**

As seen in the previous section, it would be considered lucky to live to the age of 30 during 1960 in some of the undeveloped countries in Africa and even China (Which was during The Great Leap Forward). The life expectancy in these countries is [comparable to the life expectancy in Europe in the 1800s](https://www.osfi-bsif.gc.ca/Eng/Docs/DEIP_Gallop.pdf). Similarly to that time in Europe, the low life expectancy is due to [high infant mortality](https://www.statista.com/statistics/1072803/child-mortality-rate-africa-historical/) and an increased risk of dying from infectious diseases. Clearly, if you are unfortunate enough to die as a child, you will drag down the average life expectancy by a large margin. In a country where people die at age 80 on average, it would take 4 people to live to the age of 100 just to outweigh the death of one child. The following plot demonstrates how reducing the infant mortality rate is the first and biggest decider for increasing life expectancy overall.

<iframe src="/Survival_rate.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="400"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>
*Sources: [Human Mortality Database (HMD)](https://www.lifetable.de/)*

The relatively less developed countries, like India, Brazil and South Africa, deisplay the same trend of a sharp drop in survival rate for the first 5 years of a child's life in 1960. In India, for example, you would have a 20 percent chance of dying before age 5. This trend is similar to what is seen in Denmark around 1900 (Which also is toggleable in the plot). After the first 5 years, the survival rate is flat until around 50, where it starts to drop again. The infant mortality rate is primarily a problem for the poorest countries and is often not the deciding factor of life expectancy between two developed countries. 



Thus, one could expect that the next major factor is improving the lives of those over 50 by investing in and advancing the medical field and building a society where everyone can access these tools. A natural question to ask is then: Does the life expectancy of a country correlate with the wealth and health expenditure of the country? In the next section, we explore this question.

**With wealth comes health?**

Moving forward to 2021, where the infant mortality death rate is relatively insignificant for developed countries, we aim to find factors that separate the countries with the highest life expectancy from the rest. We examine the correlation between life expectancy, health expenditure and GDP per capita.

![life_ex_health_ex_gdp](/life_ex_health_ex_gdp.jpg)
*Sources: [The World Bank](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD?fbclid=IwAR2Jf_Asqt1WWMuQ_S1bobud8Q36WcVEYDx4lF0RrdCprmiESBD0yyNaGDk)*

In both cases, there is a strong trend. However, we also see that the data resembles that of a logistic function, which we have drawn on the plot. And even a logistic function only partially encapsulates the countries with the most extensive wealth. This indicates that a country can only get so far (given the current technology) by having money and spending money on health care. Here we also highlighted Japan and other countries comparable to Japan in population size and development. Some interesting observations are that the USA is number one in spending money on healthcare while remaining relatively low in terms of life expectancy.
Meanwhile, some of the top countries in terms of life expectancy, like Japan and Italy, are at a lower level regarding GDP per capita or healthcare expenditure. Instead, they score average in these two categories compared to similarly developed countries. This indicates that there are other factors at play here.

**Exploring the Individual Factors: Investigating the Top Causes of Death in Japan, Germany, and Italy**

As of now, we have only investigated life expectancy from a societal or national standpoint. It is time to dive into individuals and look at lifestyle, diet and culture. We will explore the specific cause of death in different countries to determine these factors' effects. If we know the cause of death, we can relate this to the lifestyle of the people in that country. Here we show the top 10 causes of death in Japan, Germany, Italy and the United States.


![cause_of_death](/2x2.png)
*Sources: [WHO](https://www.who.int/data/gho/data/themes/mortality-and-global-health-estimates/ghe-leading-causes-of-death)*


These top 10 causes of death make up around 50 percent of all deaths in the country. [Globally speaking](https://www.who.int/news-room/fact-sheets/detail/the-top-10-causes-of-death), it is more or less the exact causes seen here constitute most deaths. Thus, seeing such a discrepancy in Isochaemic heart disease is quite significant. Some of the categories vary somewhat. Japan and USA, for example, has suicide (self-harm) as one of their top 10 causes of death. Indeed, even though Japan has the highest life expectancy, it is still beaten in quite some categories, mainly because strokes are frequent.

**Japan, a case study**

The Japanese have a culture of eating less red meat and more seafood and [plant foods](https://www.researchgate.net/publication/230029532_Comparative_study_of_vegetable_intake_in_Japan_and_the_United_Kingdom) such as soybeans and [tea](https://www.statista.com/statistics/507950/global-per-capita-tea-consumption-by-country/). This is also known as the [Washoku](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5852749/) diet and is known to have multiple health benefits. For example, on average, the Japanese eat less than half as much meat as Canadians. Instead, they replace the meat with seafood [which is associated with a lower risk of ischemic heart disease but an increased risk of stroke](https://observatoireprevention.org/en/2021/03/09/why-do-the-japanese-have-the-highest-life-expectancy-in-the-world/). In addition, [The risk of stroke doubles every 10 years after 50](https://www.cdc.gov/stroke/risk_factors.htm). Thus, it makes sense that the Japanese population, having a particularly large part of their population older than 50, is extra prone to strokes.

<iframe src="/plotly_time_consume_meattttttf.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="350"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>
*Sources: [OurWorldinData (UN FAO data)](https://ourworldindata.org/meat-production)*

Other risk factors of Ischaemic heart disease are [smoking, high blood pressure, high blood cholesterol, diabetes, overweight and obesity, poor diet, physical inactivity, and excessive alcohol use](https://www.cdc.gov/heartdisease/risk_factors.htm). Japanese has a low rate of obesity, with only around 4.8% for men and 3.7% for women. Canada, for comparison, has 24.6% for men and 26.2% for women, while those numbers are just over 35% in the USA. Paradoxically, the Japanese people are not exactly known to be exercising a lot, and the low obesity rate is thus likely to come mostly from healthy eating habits. In addition, they have a high rate of high blood pressure, which is likely due to the high [salt intake](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8727723/) from Japanese diet. Furthermore, the Japanese are known to be workaholics and prone to stress, which is also a risk factor for Ischaemic heart disease.

Comparison between the countries of these factors are illustrated in these next charts.

![physi](/factors.png)
*Sources: [WHO](https://apps.who.int/gho/data/node.main)*


<iframe src="/plotly_time_consume_nonf.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="350"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>
*Sources: [OurWorldinData (OECD Time Use Database data)](https://ourworldindata.org/time-use)*

Despite only exercising 30 percent of the time of Germans, the Japanese has by far the smallest obesity rate. As mentioned, this is a result of the diet, but it could also be related to the activity that comes from their work, which they spend significantly more time on than the other countries. However, this compromises the amount of time available for sleeping, and Japanese sleep much less than what is common in the west. Lack of sleep is a well-researched and well-known [risk factor for a wide range of mental and physical diseases](https://www.sciencedirect.com/science/article/pii/S1389945708700145). Whether sleeping only 7 hours and 22 minutes on average is enough is up for debate. 

Additionally, research has shown that having a [fulfilling social life](https://www.hsph.harvard.edu/news/hsph-in-the-news/active-social-life-longevity/) with a robust support network of family and friends plus living life with '[purpose](https://www.health.harvard.edu/blog/will-a-purpose-driven-life-help-you-live-longer-2019112818378)' can increase longevity. However, in recent years Japan has seen the prevalence of [loneliness](https://www.japantimes.co.jp/news/2018/11/10/national/media-national/japan-struggles-keep-loneliness-arms-length/), where [young people increasingly are disinterested in dating](https://phys.org/news/2020-11-japanese-increasingly-disinterested-dating.html). Furthermore, this development has only [increased after the COVID-19 pandemic](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8628601/).

Overall, it is clear that the Japanese are not particularly healthy in all categories. Each difference comes with it's upsides and downsides, so while we can see that Japan has a great life expectancy, it is nowhere near perfect. 


Thus, a natural question to ask is: is there a way you can live perfectly balanced between these risk factors? And if so, how long can you expect to live?

**Are we approaching immortality?**

One way to approach this question is to look at the roof of life expectancy. It's logical to assume there is some variance between how individuals live their lives, thus looking at the maximum age we should find some people who live a perfectly or nearly perfectly balanced life.

In this plot, we show the oldest confirmed human alive through time, and compare it to the life expectancy in Japan as well as the life expectancy of the top 10 percent in terms of longevity of the population in Japan.

![oldie](/oldest_man.png)

While the life expectancy is still on the rise in Japan, that is not the case for the life expectancy of the 10 percent fractile. Around the year 2000 this population group hit a life expectancy of 100 years, and it's been stale ever since. Indeed, looking at the age of the oldest man the same picture is seen. It seems likely that a perfect society with todays technology would be able to keep almost everyone alive till they are 100, however after that it's in the hands of genetics and fate. In fact, this is the same story that was told by the "chance of surviving to this age" fraction plot. We can imagine the line in this plot will be almost flat for the first years, and then it's going to be a sharp drop.

We are not immortal, and we are not approaching immortality. By nature, human beings are not supposed to live forever. We are optimized to live long enough to reproduce and raise our children, and then we are supposed to pass on the gift of life to other humans. However, we are approaching a society where almost everyone can live to be 100 years old, and that is a great achievement.

**conclusion**

In this article we saw how life expectancy has increased globally by 22 years since 1960. This has been mainly due to undeveloped countries in Africa and Asia catching up to the rest of the world by reducing particularly child mortality. However, the developed countries have also seen an increase in life expectancy, and Japan has has a steady and steep increase in life expectancy since 1960, and is now the country with the highest life expectancy in the world. We saw that GDP and health expenditure are good predictors for life expectancy, but only up to a certain point where other factors like diet, culture and lifestyle starts to matter more.

Then, we saw how Japan has few cases of deaths by Ischaemic heart disease. This has been particularly due to their diet, which consists of less red meat and more seafood than what is usually seen in the west. In addition, we saw that, despite not exercising that much, few Japanese people are obese, as they eat fewer calories and less meat, and keep themselves active by working. Many of these factors which works in favor of the life expectancy of Japan, also has downsides. For example, eating more seafood is associated with an increased risk of strokes, and working too much can cause stress and lack of sleep.

So while Japan has the highest life expectancy in the world, it is far from perfect. Given the current state of techonology, it seems unlikely that humans will be able to consistently live past 100 years old. However, the fraction that will get to experience such a long life keeps increasing. Maybe eventually we will be able to live forever, but for now we can only dream.

**References**

[https://www.clinicbarcelona.org/en/assistance/diseases/ischemic-heart-disease/risk-factors](https://www.clinicbarcelona.org/en/assistance/diseases/ischemic-heart-disease/risk-factors) (more factors for the Ischaemic heart disease)

[https://observatoireprevention.org/en/2021/03/09/why-do-the-japanese-have-the-highest-life-expectancy-in-the-world/](https://observatoireprevention.org/en/2021/03/09/why-do-the-japanese-have-the-highest-life-expectancy-in-the-world/) (Why Japan diet good, comparison between Canada and USA)

[https://data.worldbank.org/indicator/SP.DYN.IMRT.IN?locations=ZG](https://data.worldbank.org/indicator/SP.DYN.IMRT.IN?locations=ZG) (Infant mortality rate worldwide)

[https://ourworldindata.org/life-expectancy](https://ourworldindata.org/life-expectancy) (Inspiration for plots and data)

[https://www.worldlifeexpectancy.com/cause-of-death/coronary-heart-disease/by-country/](https://www.worldlifeexpectancy.com/cause-of-death/coronary-heart-disease/by-country/) (Cause of death by country)

[https://www.cdc.gov/stroke/risk_factors.htm](https://www.cdc.gov/stroke/risk_factors.htm) (Risk of stroke times 2 every 10 years after 50)

**All data sources**

[https://www.who.int/data/gho/data/themes/mortality-and-global-health-estimates/ghe-leading-causes-of-death?fbclid=IwAR081vAnkAIl9uqx9fAs4uHtVPJJMMZI4ah4Qv-_6I0aR5SupFtyHWkOf9A](https://www.who.int/data/gho/data/themes/mortality-and-global-health-estimates/ghe-leading-causes-of-death?fbclid=IwAR081vAnkAIl9uqx9fAs4uHtVPJJMMZI4ah4Qv-_6I0aR5SupFtyHWkOf9A) (Data on cause of death, data is from WHO)

[https://www.lifetable.de/](https://www.lifetable.de/) (All life-table data has been downloaded from here, internal sources can be found in link)

[https://www.kaggle.com/datasets/ulrikthygepedersen/life-expectancy?fbclid=IwAR0JO7W1_G3prS0O48OITDxvSeQPm64MtaUOIbfNjBCzcHttAUh_tC3xJME](https://www.kaggle.com/datasets/ulrikthygepedersen/life-expectancy?fbclid=IwAR0JO7W1_G3prS0O48OITDxvSeQPm64MtaUOIbfNjBCzcHttAUh_tC3xJME) (Life expectancy data for years 1960 to 2019 for many countries, data is from WHO)

[https://data.worldbank.org/indicator/NY.GDP.PCAP.CD?fbclid=IwAR2Jf_Asqt1WWMuQ_S1bobud8Q36WcVEYDx4lF0RrdCprmiESBD0yyNaGDk](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD?fbclid=IwAR2Jf_Asqt1WWMuQ_S1bobud8Q36WcVEYDx4lF0RrdCprmiESBD0yyNaGDk) (For GDP per capita and health expenditure per capita, data is from World Bank)

[https://www.populationpyramid.net](https://www.populationpyramid.net) (Population pyramid for all countries)











