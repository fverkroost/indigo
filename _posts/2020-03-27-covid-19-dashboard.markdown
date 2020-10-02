---
title: "Dashboard for COVID-19 statistics in the United Kingdom"
layout: post
date: 2020-03-27 16:00
tag: 
- R
- RShiny
- COVID-19
image: false
headerImage: false
star: true
category: blog
author: florianneverkroost
description: Dashboard for COVID-19 statistics in the United Kingdom
---


At the time of writing, the COVID-19 pandemic is keeping the world in its grip. 
Loads of numbers and statistics are popping up on the Internet, and with these numbers changing increasingly fast, 
it is hard to keep up to date on the most recent official statistics. Therefore, I decided to make this a bit easier and 
develop a Shiny dashboard to display the latest accurate numbers for the United Kingdom (UK) from official data from Public Health England (PHE).<sup>1</sup>

The dashboard contains several different plots. The first three show timelines of new daily and cumulative cases, deaths and hospital admissions, respectively. The fourth shows the daily new and cumulative number of tests by date and test type. The final tab shows the total number of cases across England by region. See the two screen shots below to have an idea of what the dashboard looks like. [This file](https://github.com/fverkroost/code-education-leisure/blob/main/covid-19-dashboard-app.R) on my [Github page](https://github.com/fverkroost) contains the code to create this dashboard.

![Screen shot of COVID-19 dashboard](https://raw.githubusercontent.com/fverkroost/fverkroost.github.io/master/assets/images/screen-shot-covid-19-timeline.png){: class="bigger-image" }
<figcaption class="caption">Screen shot of COVID-19 dashboard - Daily new and cumulative cases by UK nation </figcaption>

![Screen shot of COVID-19 dashboard](https://raw.githubusercontent.com/fverkroost/fverkroost.github.io/master/assets/images/screen-shot-covid-19-region.png){: class="bigger-image" }
<figcaption class="caption">Screen shot of COVID-19 dashboard - Daily new and cumulative cases by England region</figcaption>

---

<sup>1</sup> I am by no means trying to make any implications whatsoever about anything related to COVID-19 and do not take responsibility for any misinterpretations; I am merely visually displaying data published by PHE.


