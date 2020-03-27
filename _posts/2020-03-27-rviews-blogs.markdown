---
title: "Blog posts for RViews and RBloggers"
layout: post
date: 2020-03-27 15:00
tag: R, Python, RViews, RBloggers
image: false # https://koppl.in/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: ""
category: project
author: florianneverkroost
externalLink: false
---

During a conference last year, I was invited to write some blog posts for the RViews and RBloggers communities, 
highlighting some of the fantastic (new) capabilities of RStudio and replicating some of the graphics I
presented at the conference. I am proud to tell you that these blog posts have now been finalized and published,
and very happy to share them with you. All code is available on [this Github repository](https://github.com/fverkroost/RStudio-Blogs).

---

In the [first blog post](https://rviews.rstudio.com/2019/10/09/building-interactive-world-maps-in-shiny/), 
I show readers how to build interactive world maps in RShiny, and how to include dynamic input in the resulting dashboard. 
In [this file](https://github.com/fverkroost/RStudio-Blogs/blob/master/interactive_worldmap_shiny_embedded.Rmd) 
on my Github, I also show how to include interactive Shiny dashboards in RMarkdown files. The live app is published [here](https://fverkroost.shinyapps.io/interactive_worldmap_app/).

I also wrote a series of blog posts dedicated to classifying clothing categories from the Zalando Fashion MNIST data
using various machine and deep learning methods.

- In the [first post of this series](https://rviews.rstudio.com/2019/11/11/a-comparison-of-methods-for-predicting-clothing-classes-using-the-fashion-mnist-dataset-in-rstudio-and-python-part-1/), 
I show the reader how to build an artificial neural network and convolutional neural 
network in Python, and how to run this code easily in RStudio.
- In the [second post](https://rviews.rstudio.com/2020/03/03/predicting-clothing-classes-part-2/), 
I perform dimension reduction using principal components analysis to scale down the data to
avoid data redundancy and overfitting and to reduce computational cost.
- In the [third post](https://rviews.rstudio.com/2020/03/10/comparing-machine-learning-algorithms-for-predicting-clothing-classes-part-3/), 
I use the reduced data from the second post to estimate random forests and gradient-boosted trees. 
In this post, I also perform various diagnostic analyses and take measures to reduce overfitting.
- In the [fourth and final post](https://rviews.rstudio.com/2020/03/24/comparing-machine-learning-algorithms-for-predicting-clothing-classes-part-4/), 
I estimate support vector machines and compare all the models estimated throughout the series of blog posts.

---

I would love to hear what you think and how these posts have helped you upgrade your programming skills!
