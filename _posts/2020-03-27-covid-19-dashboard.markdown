---
title: "Dashboard for COVID-19 statistics in the United Kingdom"
layout: post
date: 2020-03-27 16:00
tag: 
- R
- RShiny
- COVID-19
image: false
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: ""
category: project
author: florianneverkroost
externalLink: false
---

At the time of writing, the COVID-19 pandemic is keeping the world in its grip. 
Loads of numbers and statistics are popping up on the Internet, and with these numbers changing increasingly fast, 
it is hard to keep up to date on the most recent official statistics. Therefore, I decided to make this a bit easier and 
develop a Shiny dashboard to display the latest accurate numbers for the United Kingdom from official data from Public Health England (PHE).<sup>1</sup>

The dashboard contains several different plots. The first one shows a timeline of total and new cases as well as deaths in the 
United Kingdom (see screen shot below). The second and third tabs show the total number of cases across England by region respectively county. The fourth tab shows a timeline of total cases by country (England, Wales, Scotland and Northern Ireland). 

Check out the dashboard [here](https://fverkroost.shinyapps.io/COVID19intheUnitedKingdom/)!

![Screen shot of COVID-19 dashboard](https://github.com/fverkroost/fverkroost.github.io/blob/master/assets/images/screenshot-covid-19-dashboard.png){: class="bigger-image" }
<figcaption class="caption">Screen shot of COVID-19 dashboard</figcaption>

---

<sup>1</sup> I am by no means trying to make any implications whatsoever about anything related to COVID-19 and do not take responsibility for any misinterpretations; I am merely visually displaying data published by PHE.


