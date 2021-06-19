# Periodical Cicadas and Human Behavior

## Table of Contents
* [Executive Summary](#executive-summary)
* [Biological Context for the Data](#biological-context-for-the-data)
* [Data Questions](#data-questions)
* [Known Issues and Challenges](#known-issues-and-challenges)
* [Technologies Used](#technologies-used)
* [Resources Cited](#resources-cited)

## Executive Summary

The emergence of Brood X periodical cicadas in 2021 is an exciting and widespread event.  What makes this year unusual is the size of the brood and the geographic range that it covers: we're talking about hundreds of billions of individuals.

Periodical cicada broods aside from Brood X also have big impacts.  We know that the sheer size of a brood population is enough to cause local ecological changes during emergence years.  Tree trunks grow more slowly, songbird and rodent populations increase in response to the abundance of cicadas as a food source, and the calls of some frog species are even interrupted.<sup>1</sup>

So what about the impact to humans?  We tend to socially classify periodical cicadas as loud, numerous, and more annoying than wondrous.  Does the presence of these insects lead to unusual human activity, perhaps driven by irritability and distraction?

This project will examine data reflective of localized human activity during periodical cicada brood emergences to try and find answers.


## Biological Context for the Data

 #### Emergence Time and Location:

We refer to periodical cicadas as being on a 13-year or 17-year cycle.  But this cycle is very location-specific!  In fact, nearly every year there is a population (“Brood”) emerging somewhere on their unique 13 or 17-year lifecycle.  This is what allows me to analyze the impact to human behavior: I will look at city or county-level data for the years prior to, during, and following a periodical cicada emergence.  
This map from the USDA should provide and impression of the variability in the time and location of Brood Emergences.<sup>2</sup>

<p align="center">
<img src="/assets/USDA_periodical_brood_map.jpg" alt="USDA map" width="500"/>
</p>

The analysis will focus only on the months of May and June for all relevant years.  Cicada emergence is responsive to soil temperatures and weather, and the correct conditions are typically reached in May in the United States.  Given the above-ground lifespan of periodical cicadas is limited to a few weeks, looking at the months of May and June allows for flexibility in season and individuality, while covering the duration of their collective 6-8 weeks above ground.<sup>3</sup>  Stragglers who emerge outside this range are not likely to be in high enough numbers to make a significant impact to human life.   

 #### The Sound:

First-hand accounts of periodical cicadas indicate that the noise they make is unparalleled, and that it's also likely to have an unwelcome physical encounter.  The noise, called 'chorusing' - and less kindly called 'shrieking' - reaches 90+ decibels, which is "like standing next to a food blender spinning at top speed or a gas-powered lawn mower."<sup>4</sup>  Having this as a constant background soundtrack seems ripe for a potentially distracting, disruptive and grating couple of weeks (once a cicada has emerged from the ground, the remainder of their lifespan is typically two weeks).  


## Data Questions
If we compare activity within the same timeframe before, during, and after the specific year of a periodical cicada emergence, can we observe any trends?  More specifically:
 - Are people more likely to misbehave during periodical cicada emergences, as evidenced by non-traffic citations and crime?
 - Is there an increase in traffic fatalities?
 - Does the populace demonstrate signs of general annoyance or irritation, as evidenced by complaints to cities via services like 311?

## Known Issues and Challenges
Science has not yet found a way to quantify the number of cicadas during a periodical emergence, nor the precise spatial boundaries of emergences.  This leads to a built-in assumption in my project that all periodical cicadas events are of the same magnitude within a local scale, and that these events can be compared equally across time and space.  
Leaning into citizen science and utilizing publicly available technologies will help with cicada data collections efforts moving forward.  However, the benefits of this additional data will be limited to recent years, as the technology (cell phones, tracking apps, etc.) has not been available until relatively recently.


## Technologies Used
 #### Data Cleaning
  - Python (Pandas)
  - Excel
  - Jupyter notebooks
 #### Visualizations
  - Tableau
  - Excel Pivot Charts for early analyses
 #### Other
  - VMWare Fusion virtual Windows machine

## Resources Cited
1. https://daily.jstor.org/cicadas-are-back/
2. Liebhold, A. M., Bohne, M. J., and R. L. Lilja. 2013. Active Periodical Cicada Broods of the United States. USDA Forest Service Northern Research Station, Northeastern Area State and Private Forestry.
3. https://www.cicadamania.com/cicadas/how-long-does-a-periodical-cicada-emergence-last/
4. https://www.washingtonpost.com/weather/2021/06/02/cicadas-sound-noise-weather/
