---
title: "Hashtag Community Detection on Social Networks"
layout: post
date: 2022-07-21 11:00
tag: trss, research
image: na.
headerImage: false
projects: true
hidden: true 
description: "Automated Hashtag Hierarchy Generation Using Community Detection and the Shannon Diversity Index, with Applications to Twitter and Parler"
category: project
author: afollmann
externalLink: false
---

Excited to share another piece of work I have spent a good deal of time on over the past year at TRSS - a paper on community detection of hashtags on networks. 

The main takeaways of the paper are that we introduced some novel metadata based entropy derivations to associate with hashtags, to group hashtags into like communities. Essentially, we are 
able to give each hashtag several entropy scores, along different axes of information (eg. other-hashtag co-occurrence, time of day of hashtag posting, number of users posting about said hashtag, etc)
My major contributions to this paper are: the word entropy metric, the communitiy detection quality heuristic for comparing community detection algorithms, and collecting + cleaning + preparing the Parler data. 

[Please read the paper here!]({{site.url}}/assets/documents/TwitterPaper.pdf)

