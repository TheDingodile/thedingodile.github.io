---
layout: post
title:  "Tenderloin - Tender Spot for Crime?"
date:   2023-03-24 14:18:41 +0100
categories: jekyll update
full-width: true
---

**Introduction**

San Francisco (SF) is one of the cities in the USA with the highest crime rates. Particularly in the small district, Tenderloin, the sheer amount of crimes per year is shocking. 

Thanks to technological evolution, a newborn predictive policy has taken place in the data science sector. The implementation of huge crime databases allow law enforcement and researchers to adapt a better overview of “crime hot spots” and analyze the historical evolution of crimes. 

In this article we explore the crime history from 2003 to 2017 of the poorest district of San Francisco: Tenderloin. [A district that is “infamous for drugs, homelessness and crime”](https://sfstandard.com/criminal-justice/how-serious-is-tenderloins-drug-problem-heres-what-city-data-says/)

We have access to a database consisting of crimes from 2003 to 2017 over all of SF categorized by crime-type, location, time of incident, and much more. The dataset has more than 2 million incidents covered.

**Tenderloin - the “peak” of the city**

Let us start by giving the reader the opportunity to explore the dataset themselves. In this visualization the reader is able to get an idea of the distribution of all the crimes-types in SF. In particular, it is encouraged to compare Tenderloin's crime-density to any of the surrounding neighborhood districts, such as Southern, Northern and Central.
<iframe src="/bokeh.html"
    sandbox="allow-same-origin allow-scripts"
    width="150%"
    height="800"
    scrolling="no"
    seamless="seamless"
    frameborder="0">
</iframe>
What is most peculiar is the consistency at which Tenderloin scores higher than the other districts. And, impressively more so, the drug crime density of Tenderloins is more than 20 times higher than the second highest scoring one (Southern).
Indeed, as claimed by [this article](https://abc7news.com/sf-tenderloin-drug-arrests-narcan-homeless/11535735/) more than 85 percent of all drug-related arrests in SF happen in Tenderloin. (Although the article is from 2022)

So this is where the story leads us, into the enormous drug-market that exists in Tenderloin. The next questions to ask are: where in the Tenderloin does these drug incidents happen? Why particularly here? And are we seeing any changes over time?

**Where, why and when?**

According to [wikipedia](https://en.wikipedia.org/wiki/Tenderloin,_San_Francisco) the street “Turk street” is particularly infested.
In this next plot, we shall see how the distribution of drug-crimes varies inside Tenderloin. In addition, we show this visualization from 2008, where the drug-crimes were at its highest, till recent time.

![please work2](/drugcrimes.jpg)
It seems in 2008 drug incidents were just everywhere and that a big change has happened since then. In addition, it seems the northern and eastern part of Tenderloin has been almost cleared. As wikipedia claims, the drug-incidents now mostly happen on the infamous “Turk Street” and nearby. A full visualization over all the years can be seen [here](https://thedingodile.github.io/TimeHeatmap.html).

Finally, to further analyze this change over time, also in comparison to the rest of SF, we choose to include a plot that contains all this information.
(Use third plot).
We

