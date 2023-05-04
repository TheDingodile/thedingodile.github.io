---
layout: post
title:  "Life expectancy in Japan - A global perspective"
date:   2023-05-01 14:18:41 +0100
categories: jekyll update
full-width: true
---

**Introduction**

Japan is currently one of the countries with the highest life expectancy of all time. The country has had an consistent growth to the top in the last 60 years. In this article we explore the global development of life expectancy with focus on Japan. Get ready for an interactive journey going from a worldwide perspective deepdiving into the fascinating story of Japan. How has life expectancy developed globally? What causes people to live longer? How has particularly Japan unlocked this potential? Is there a limit to to human longevity? 

If these questions whet the appetite, this article is for you.

**The last 60 years globally**

We start off in a broad scope by showing the global development in the last 60 years. [During this period the world-wide life expectancy has increased from 50 years to 72 years.](https://www.macrotrends.net/countries/WLD/world/life-expectancy) This remarkable development is particularly due to many countries in Asia, Africa and South America catching up with the western world.

<iframe src="/world.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="600"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

We see how drastically Africa improves over the period. Meanwhile, the countries which are leading the pack in 1960, like the Scandinavia, Australia, Japan and Canada are still at the top in 2020. However, the gap between the top and the bottom has been reduced significantly. Worth noticing is also the unparalleled improvement in China, which has gone from a life expectancy of 33 years in 1960 to 78 years in 2020. To better illustrate the sheer magnitude of this development we made the following bar-chart.

<iframe src="/bokeh.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

It is the developing countries like China and Afghanistan that have seen the biggest improvement in life expectancy. The developed countries like Japan and the Scandinavian countries have also seen an improvement, but not nearly as drastic. As one could expect, it becomes harder and harder to push the boundaries of human longevity. The different mortality rates also gives rise to a quite different population structures. In developing countries the population is much younger, while in developed countries the population is much older. This is illustrated in the following plot.


<iframe src="/age.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="500"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

Countries like Japan and China has had quite the shift in terms of their population pyramid. Going from the structure that characterizes developing countries, with a falling slopes for each year, to a more balanced, or even upwards-going distribution. Meanwhile, India is somewhere inbetween these two models, and countries like Afghanistan are still in the developing stage. However, a population with mostly people around retirement age is scary aswell, as the working population has to support the retired population. This is a problem that Japan is facing right now, and is one of the reasons why Japan is [struggling with their economy.] (https://www.imf.org/en/News/Articles/2020/02/10/na021020-japan-demographic-shift-opens-door-to-reforms)

**Infant mortality: the key to improving life expectancy in undeveloped countries**

As seen in the previous section it would be considered lucky to live to the age of 30 during 1960 in some of the undeveloped countries in Africa and even China (Which was during The Great Leap Forward). The life expectancy in these countries is [comparable to the life expectancy in Europe in the 1800s](https://www.osfi-bsif.gc.ca/Eng/Docs/DEIP_Gallop.pdf). Similarly to that time in Europe, the low life expectancy is due to [high infant mortality](https://www.statista.com/statistics/1072803/child-mortality-rate-africa-historical/) and a high risk of dying from infectious diseases. Clearly, if you are unfortunate enough to die as a child, you will drag down the average life expectancy by a large margin. In a country where people die at age 80 on average, it would take 4 people to live to the age of 100 just to outweight the death of one child. This next plot demonstrates how reducing infant mortality rate is the first and biggest decider when it comes to increasing life expectancy overall.

<iframe src="/Survival_rate.html"
    sandbox="allow-same-origin allow-scripts"
    width="100%"
    height="400"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>

All of the relatively less developed countries, like India, Brazil and South Africa, displays the same trend of a sharp drop in survival rate for the first 5 years of a childs life in 1960. In India, for example, you would have a 20 percent chance of dying before the age of 5. This trend is similar to what is seen in Denmark around 1900 (Which also is toggle-able in the plot). After the first 5 years the survival rate is more flat until the age of around 50 where it starts to drop again. The infant mortality rate is primarly a problem for the poorest countries, and is often not the deciding factor of life expectancy between two developed countries. 





Thus, one could expect that the next major factor has to do with improving life of those over 50 years old by investing and advancing the medical field, and by building a society where everyone has access to these tools. A natural question to ask is then: Does the life expectancy of a country correlate with the wealth and health expenditure of the country? In the next section we explore this question.

**With wealth comes health?**

Moving forward to 2021 where infant mortality death rate is relatively insignificant for developed countries, we aim to find factors which seperate the countries with the highest life expectancy from the rest. We start by looking at the correlation between life expectancy, health expendure and GDP per capita.

![life_ex_health_ex_gdp](/life_ex_health_ex_gdp.jpg)

In both cases there is a strong trend. However, we also see that the data resembles that of an logistic function. And even a logistic function doesn't quite encaptulate the countries with the very largest wealth. This indicates that a country can only get so far (given the current technology) by having money and spending money on health care. Here we also highlighted Japan and some other countries which are comparable to Japan in population size and development. Some interesting observations are USA being number one in terms of spending money on healthcare, while remaining relatively low in terms of life expectancy. Meanwhile, some of the top countries in terms of life expectancy, like Japan and Italy, are not in the top in terms of GDP per capita or health care expenditure. Rather, they score average in these two categories compared to similarly developed countries. This indicates that there are other factors at play here.

**The importance of a healthy lifestyle**

As of now, we have only investigated life expectancy from a societal or national stand-point.

**Japan, a case study**

**Are we approaching immortality?**

**notes**

Stroke vs ischemic heart disease

Good links:

https://observatoireprevention.org/en/2021/03/09/why-do-the-japanese-have-the-highest-life-expectancy-in-the-world/

https://www.cdc.gov/stroke/risk_factors.htm (Risk of stroke times 2 every 10 years after 50)

https://www.clinicbarcelona.org/en/assistance/diseases/ischemic-heart-disease/risk-factors (factors for the disease)

**References**

(All data sources should be listen here)

https://data.worldbank.org/indicator/SP.DYN.IMRT.IN?locations=ZG (Infant mortality rate)

https://ourworldindata.org/life-expectancy (Inspiration for plots and data)

https://www.lifetable.de/ (All life-table data has been downloaded from here)






